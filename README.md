# 🚀 Hello Hugo – Railway Template

This is a minimal Hugo static site deployed on [Railway](https://railway.app), using [Nixpacks](https://nixpacks.com) for lightweight, dependency-free setup.

## 🌐 Features

- ✅ Instant deployment with Hugo pre-installed (via Nixpacks)
- ✅ No Dockerfile required
- 🌍 Dynamic \`baseURL\` from Railway’s public URL
- 🌟 Production build with Hugo and static serving via Caddy

---

## 🛠️ File Structure

\`\`\`
.
├── content/
│   └── _index.md
├── nixpacks.toml
├── railway.json
└── README.md
\`\`\`

---

## 🚀 Deploy

// TODO insert link
---

## 👋 Notes

- Hugo is installed dynamically using Nixpacks — no manual install or image needed.
- \`RAILWAY_PUBLIC_DOMAIN\` is used to generate correct absolute URLs during build.
- Caddy serves your production-ready static files from the \`public/\` folder.
