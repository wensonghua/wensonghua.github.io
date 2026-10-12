宝宝绘画批量编辑尺寸 — 可分享网页包（类似 birme）

用法：
1. 用浏览器打开 index.html
2. 或放到任意静态服务器 / GitHub Pages

URL 参数示例：
  index.html?target_width=720&target_height=1280
  index.html?target_width=1080&target_height=1920&ratio=9:16
  index.html?ratio=1:1

target_width + target_height → 固定像素输出，并按宽高设裁剪比例（可用 ratio 覆盖）
