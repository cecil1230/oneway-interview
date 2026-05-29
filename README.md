# 🎥 单向视频面试系统

一个纯前端、零后端的单向视频面试网页，可部署到 **GitHub Pages** 免费使用。

## 特点

- ✅ **完全免费** — 只需 GitHub 账号，无需服务器
- ✅ **纯前端** — 所有录制在浏览器完成，不上传第三方服务器
- ✅ **摄像头+麦克风检测** — 自动检测设备是否正常
- ✅ **准备倒计时** — 每题有准备时间，倒计时结束自动开始录制
- ✅ **限时录制** — 每题有限定回答时间，时间到自动停止
- ✅ **回看重录** — 可预览并重录不满意的回答
- ✅ **下载保存** — 所有视频可下载到本地
- ✅ **移动端适配** — 手机、平板也能用

## 当前面试题（4题，英文）

| # | 问题 | 准备 | 回答 |
|---|------|------|------|
| 1 | Please introduce yourself in 30 seconds. | 30s | 30s |
| 2 | Which track interests you more? Computer Intelligent Control or Biopharmaceutical System Design? Why? | 30s | 2min |
| 3 | What specific aspect of that field do you hope to explore during the 3-week program? | 30s | 2min |
| 4 | What's your expectation to the Camp itself? | 30s | 2min |

## 快速部署到 GitHub Pages

1. 去 https://github.com/new 创建一个新仓库（如 `oneway-interview`）
2. 上传 `index.html`
3. **Settings → Pages** → Source 选 `main` → 文件夹 `/ (root)` → Save
4. 等 1-2 分钟，你的面试页面就上线了

## 使用流程

1. 打开网页 → 自动检测摄像头和麦克风
2. 输入姓名 → 点击「开始面试」
3. 阅读英文题目 → 点击「开始回答」→ 30秒准备倒计时 → 自动录制
4. 时间到自动停止 → 点击「下一题」
5. 全部完成后，回顾所有回答，不满意的可重录
6. ✅ 提交 → 下载所有视频到本地

## 自定义题目

编辑 `index.html` 中 `QUESTIONS` 数组即可。

## 隐私说明

- 所有视频数据仅存储在浏览器内存中，不上传任何服务器
- 关闭页面后数据丢失，请务必下载保存

## 浏览器推荐

Chrome / Edge / Firefox 最新版。
