# 🌱 Sanmitra — Your Digital Nutrition Label

> *"You check the nutrition label on every food you eat. Your mind deserves the same protection."*
> — Anurag Sharma, Creator

**Sanmitra** (Sanskrit: सन्मित्र — *True Friend*) is a free, AI-powered tool that analyses any YouTube video, podcast, or article and generates a **Digital Nutrition Label** — before you consume it.

🔗 **Live App:** [https://anuragsharmasuccess-eng.github.io/sanmitra/]  
👤 **Built by:** [Anurag Sharma](https://www.linkedin.com/in/anuragsharmapro/) — AI Product Leader · Author · Coach

---

## 📸 What It Does

Paste any content URL. Sanmitra reads it, fact-checks the claims, and gives you:

- **Sanmitra Score** — an overall credibility score out of 100
- **6 Nutrition Dimensions** — Speaker Credibility, Factual Accuracy, Emotional Manipulation, Commercial Transparency, Source Quality, Audience Safety
- **Claim-by-Claim Fact Checks** — every major claim marked TRUE / PARTIAL / FALSE / UNVERIFIED
- **Personal Values Alignment** — scored against filters *you* choose (Evidence-based, Scientific accuracy, Mental health safe, etc.)
- **Compliance Checks** — regulatory and ethical framework flags
- **Plain-English Verdict** — Sanmitra's honest summary of whether the content deserves your trust

---

## ⚡ Quick Start

### For Users
1. Open the app: **[yourusername.github.io/sanmitra](https://yourusername.github.io/sanmitra)**
2. Click **🔑 API Key** in the top-right header
3. Paste your free Anthropic API key (see below to get one)
4. Paste any YouTube, podcast, or article URL
5. Click **Analyse Content →**

### Getting a Free API Key
1. Go to [console.anthropic.com](https://console.anthropic.com/settings/keys)
2. Sign up (free) → **API Keys** → **Create Key**
3. New accounts include free credits — enough for dozens of analyses
4. Your key is stored **only in your browser session** — never on any server

---

## 🛠️ How It Works

```
User pastes URL
       ↓
Claude AI uses web_search to fetch the content & transcript
       ↓
Claims are identified and fact-checked in real time
       ↓
6 dimensions scored (0–100) against your personal values
       ↓
Digital Nutrition Label rendered with full reasoning
```

**Tech stack:**
- Pure HTML + CSS + Vanilla JavaScript — zero dependencies, zero build step
- [Claude Sonnet](https://www.anthropic.com/claude) via Anthropic API with `web_search` tool
- Runs 100% in the browser — no backend, no database, no server

---

## 🎯 Features

| Feature | Details |
|---|---|
| 🔍 Real transcript analysis | Claude fetches and reads actual content — not just metadata |
| ✅ Claim fact-checking | 4–6 key claims verified per analysis |
| 🎛️ Personal values filter | 10 value toggles — your score, your filter |
| 📊 Animated nutrition label | Visual bars, scores, and colour-coded flags |
| 📜 Transcript viewer | Full excerpt with claim highlights |
| ⚖️ Compliance framework | Checks against media, advertising & safety standards |
| 🕐 Analysis history | Recent scans saved in session for quick re-access |
| 📋 Share results | Copy label, post to X (Twitter), or share on LinkedIn |
| ⭐ Feedback widget | Rate the app and send feedback directly to Anurag |
| 📱 Responsive | Works on mobile, tablet, and desktop |
| 🌙 About page | Built-in SPA routing — no page reload needed |

---

## 🚀 Self-Hosting (For Developers)

No build process needed. Clone and open.

```bash
git clone https://github.com/yourusername/sanmitra.git
cd sanmitra
open index.html   # or just double-click it
```

That's it. Add your API key in the UI and you're running locally.

### Deploy to GitHub Pages
1. Fork this repository
2. Go to **Settings → Pages**
3. Source: `main` branch, `/root` folder
4. Save — live in ~2 minutes at `yourusername.github.io/sanmitra`

### Deploy to Netlify (60 seconds)
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag `index.html` onto the page
3. Done — instant live URL

---

## 🔐 Privacy & Security

- **Your API key** is stored in `sessionStorage` only — it clears when you close the tab
- **No analytics** — no tracking, no cookies, no third-party scripts
- **No backend** — the app makes API calls directly from your browser to Anthropic's servers
- **No data stored** — analysis results exist only in your browser session

---

## 🧠 The Philosophy

Media literacy tools have historically been the domain of journalists, academics, and experts. Sanmitra is built on four principles:

1. **Truth before comfort** — if a video spreads misinformation, the label says so
2. **Your values, your score** — you define the filter, Sanmitra does the analysis
3. **Show the evidence, not just the verdict** — every score comes with full reasoning
4. **Access is a right, not a privilege** — free, no login, runs in any browser

---

## 📬 Feedback & Contact

Found a bug? Have an idea? Want to collaborate?

- ⭐ **Rate the app** — use the feedback widget in the bottom-right corner
- 💼 **Connect on LinkedIn** — [linkedin.com/in/anuragsharmapro](https://www.linkedin.com/in/anuragsharmapro/)
- 📧 **Email** — anuragsharma.success@gmail.com

If Sanmitra has helped you think more clearly about content you consume, consider sharing it with someone who would benefit.

---

## 📄 License

This project is open for personal and educational use. If you build on it or share it publicly, a credit to the original creator is appreciated.

---

<div align="center">

**🌱 Sanmitra — Know what you consume. Protect what you believe.**

*Powered by [Claude AI](https://www.anthropic.com/claude) · Built by [Anurag Sharma](https://www.linkedin.com/in/anuragsharmapro/)*

</div>
