# 电子科大70周年校庆·同学30周年聚会 动线图

9月26日沙河校区聚会动线交互地图。单文件版（Leaflet+数据全部内联），浏览器打开即用，手机/电脑均可。

## 访问入口

**https://kevinmw.github.io/reunion-map/reunion-map-standalone.html**

（jsDelivr 的 /gh 服务出于安全对 HTML 返回 text/plain，不能直接打开网页，仅可作 JS/CSS/图片等资源的 CDN——本页面已全部内联，无需外部资源。）

## 包含功能

- 方案A全天动线（12段：游览+回水镇茶话会晚餐+可选KTV）
- ▶ 逐步/连续行进动画，模拟时钟+当日时间表
- 点击右上角 📍 进入坐标校正模式（拖拽"约"站点取坐标）

## 重新部署

1. 覆盖本目录 `reunion-map-standalone.html`
2. `gh api repos/kevinmw/reunion-map/contents/reunion-map-standalone.html -X PUT --input <base64-payload>`（或用 git push）
3. 等约1分钟，URL 不变自动更新
