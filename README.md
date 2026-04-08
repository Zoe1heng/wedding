# Wedding Invitation 💍

婚礼电子请柬 — 亚B日本风格

## 部署方法

### GitHub Pages（推荐）

1. 在 GitHub 创建新仓库，比如 `wedding`
2. 把整个项目推上去：

```bash
cd wedding-site
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/你的用户名/wedding.git
git push -u origin main
```

3. 进入仓库 Settings → Pages → Source 选 `main` 分支 → Save
4. 等1-2分钟，访问 `https://你的用户名.github.io/wedding/`

### Vercel / Netlify

直接拖拽整个 `wedding-site` 文件夹到 [vercel.com](https://vercel.com) 或 [netlify.com](https://netlify.com) 即可。

## 自定义内容

打开 `index.html`，搜索替换以下占位符：

| 占位符 | 替换为 |
|--------|--------|
| `Groom` | 新郎英文名 |
| `Bride` | 新娘英文名 |
| `2 0 2 5 . 0 0 . 0 0` | 婚礼日期 |
| `二〇二五年 〇月〇日` | 日文日期 |
| `00:00` | 实际时间 |
| `会場名` | 会场名称 |
| `住所をここに記載` | 会场地址 |
| `〇月〇日まで` | RSVP截止日期 |

## 项目结构

```
wedding-site/
├── index.html          ← 主页（19KB）
├── README.md
└── images/
    ├── restaurant-selfie.jpg
    ├── photo-booth.jpg
    ├── night-walk.jpg
    ├── heart-hands.jpg
    ├── fine-dining-heart.jpg
    └── fine-dining-table.jpg
```
