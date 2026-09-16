# 网页背景音乐（BGM）清单

> 更新时间：2026-09-15
> 用途：CoCo 个人主页悬浮球「音乐播放」功能的曲库候选

## 曲库（6 首，可直接使用）

全部为 **Kevin MacLeod**（incompetech.com）的作品，授权为 **CC BY 4.0**（可自由使用，包括商用，唯一要求是在网页某处署名作者与来源）。全部为纯音乐、无歌词、节奏舒缓不喧宾夺主，时长均超 1 分钟。

### 保留的两首

| 文件 | 时长 | 码率 | 风格 |
|---|---|---|---|
| `At Rest.mp3` | 2:12 | 320k | 安静的钢琴独奏，带一点沉思感 |
| `Wholesome.mp3` | 6:03 | 320k | 温暖的木吉他+钢琴，明亮但不吵 |

### 新增的古典风格

| 文件 | 时长 | 码率 | 风格 |
|---|---|---|---|
| `Gymnopedie No 1.mp3` | 3:07 | 320k | 萨蒂名作，极简钢琴，最经典的"安静 BGM"之一 |
| `Canon in D Major.mp3` | 5:55 | ~263k(VBR) | 帕赫贝尔卡农，弦乐，平稳庄重 |
| `Dance of the Sugar Plum Fairy.mp3` | 1:59 | 320k | 柴可夫斯基《胡桃夹子》，钢片琴，轻盈梦幻 |
| `Fairytale Waltz.mp3` | 1:39 | 256k | 童话圆舞曲，弦乐柔和摇曳 |

> 风格对照：「潮鸣」系的安静钢琴 → At Rest / Gymnopedie；「青石巷」东方路线本轮按你的要求未保留；古典弦乐 → 卡农 / 圆舞曲。

## 署名要求（CC BY 4.0）

在网站任意位置（页脚或"关于"）加一行即可：

```
Music: "At Rest", "Wholesome", "Gymnopedie No 1", "Canon in D Major",
"Dance of the Sugar Plum Fairy", "Fairytale Waltz"
by Kevin MacLeod (incompetech.com), licensed under CC BY 4.0
```

## 接入方式（下个版本做）

悬浮球里的「音乐播放」目前是占位。建议实现为：

1. 把本目录放到站点目录（`bgm/`，与 `index.html` 同级）；
2. 悬浮球点开 → 曲目列表 → 点击播放，`audio` 元素循环播放；
3. 默认音量 30% 左右、淡入 2 秒，切歌交叉淡入淡出；
4. 浏览器自动播放限制：必须由用户首次点击后才能出声（悬浮球按钮正好充当这个交互）；
5. 这 6 首是免费授权，可以安全提交到 GitHub；但你自己持有的版权音乐（如潮鸣）**不要**提交到公开仓库。

## 备选资源站（以后想换口味）

- incompetech.com（本清单来源，CC BY）
- musopen.org（古典乐录音，公有领域）
- pixabay.com/music（免费可商用，无需署名）
- YouTube Audio Library（需 Google 账号）

*注：freepd.com 已于 2025 年关站；imsyy.top 的 BGM 走网易云音乐 API（Meting），在线引用有稳定性与版权风险，不建议照搬。*
