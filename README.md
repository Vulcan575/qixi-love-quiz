# 🌻 七夕恋爱答题闯关

给女朋友准备的七夕小程序合集，纯前端单文件 HTML，双击即玩，无需联网（音效用浏览器内置合成）。

## 玩法

- 共 8 道专属甜题，答对解锁结局
- **躲猫猫选项**：错误答案会一直逃跑，只有真正的答案才点得到 😝
- 通关后逐字打出情书 + 撒花庆祝

## 文件

| 文件 | 版本 |
|------|------|
| `fangan1-xindong-bianlidian.html` | 心动便利店（第一版） |
| `fangan2-lianai-dati-chuanguan.html` | 答题闯关 · 奶油手绘版 |
| `fangan2-lianai-dati-chuanguan-xingkong.html` | 答题闯关 · 星空银河版 |
| `fangan2-lianai-dati-chuanguan-xiangrikui.html` | 答题闯关 · 向日葵粉粉版（Y2K 潮流风，2026，当前部署版） |
| `fangan2-lianai-dati-chuanguan-gongqijun.html` | 答题闯关 · 宫崎骏漫画风（蓝天白云绿山坡 + 草坡小房子，2026） |
| `fangan2-lianai-dati-chuanguan-tianshixing.html` | 答题闯关 · 天使星星辰港湾（深夜星空 + 金色沙丘 + 天使托猫剪影 + 玻璃手办盒，2026，最新版） |

## 部署

- GitHub Pages / Cloudflare Pages 均可直接托管
- 部署目录：`deploy/`（内含 `index.html`）

## 定制

打开对应 HTML，修改顶部脚本：

```js
const YOU = '大笨蛋';   // 你的昵称
const HER = '小可爱';   // 她的昵称
const QUESTIONS = [ ... ];  // 题库
const LETTER = [ ... ];     // 情书
```

---

❤ 大笨蛋 出品
