# 风起晴野 · 动态立绘（NFC 第二页）

晴天山谷、飞鸟掠空、天光洒落、金色浮尘。

与 `reze-live-portrait`（雨夜蕾塞页）并列的第二个 NFC 页面。

## 本地预览

直接双击 `index.html`，或：

```powershell
cd C:\Users\Lawson\Desktop\NFC\valley-live-portrait
python -m http.server 8080
```

浏览器打开 `http://localhost:8080`。

## 发布到 GitHub Pages

推荐放进已有的 `nothing` 仓库作为子目录（一个仓库、两个 NFC 链接）：

```powershell
cd C:\Users\Lawson\Desktop\NFC\reze-live-portrait
# 把 valley-live-portrait 复制进仓库根目录下的 valley/
git add valley
git commit -m "Add valley live portrait"
git push
```

Pages 地址即：`https://issaclfl.github.io/nothing/valley/`
（用户名大小写以仓库 Settings → Pages 显示的 URL 为准）

也可以单独建仓库，步骤同蕾塞页 README。

## 写入 NFC

1. 手机安装 NFC 写入类 App（如 NFC Tools）
2. 写入 **URL / Web Link** 记录：本页的线上地址
3. 贴到卡片/挂饰上，用手机背面一贴即可打开

## 说明

- **音乐**：`assets/bgm.mp3` 为《打火机》Penny～吉隆坡的天气它是翻云又覆雨，
  换歌直接覆盖同名文件即可（HTML 不用改）
- 底图 `assets/bg.jpg` 为 1664×936 原生分辨率，208KB，无需再压缩
- 竖屏按 cover 居中裁剪（不旋转），人物位于画面中偏右，手机竖屏正好框住人物
- 页面顶部的「AI生成」标记请保留
- 素材与音乐仅供个人使用，勿公开传播版权素材
