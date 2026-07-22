<div align="center">

<!-- Animated Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:10b981,40:059669,100:047857&height=220&section=header&text=⚡%20Distill%20AI&fontSize=58&fontColor=ffffff&animation=twinkling&fontAlignY=42&desc=Smart%20Text%20Summarizer%20·%20Frequency%20Scoring%20·%20Zero%20Dependencies%20·%20100%25%20Client-Side%20·%20Instant%20Results&descAlignY=65&descSize=15&descColor=a7f3d0" width="100%"/>

<br/>

<!-- LIVE DEMO BUTTON -->
<a href="https://mabdullahab614-alt.github.io/quick-summarizer">
  <img src="https://img.shields.io/badge/▶%20%20T%20R%20Y%20%20L%20I%20V%20E%20%20N%20O%20W-10b981?style=for-the-badge&logo=github&logoColor=white&labelColor=047857" height="52" alt="Try Live"/>
</a>

<br/><br/>

<!-- Badge Row 1 -->
<img src="https://img.shields.io/badge/Algorithm-Frequency%20Scoring-10B981?style=for-the-badge&labelColor=0f172a"/>
&nbsp;
<img src="https://img.shields.io/badge/Dependencies-Zero-22C55E?style=for-the-badge&labelColor=0f172a"/>
&nbsp;
<img src="https://img.shields.io/badge/Speed-Milliseconds-F59E0B?style=for-the-badge&labelColor=0f172a"/>
&nbsp;
<a href="#-license"><img src="https://img.shields.io/badge/License-All%20Rights%20Reserved-DC2626?style=for-the-badge&labelColor=0f172a"/></a>

<br/><br/>

<!-- Badge Row 2 -->
<img src="https://img.shields.io/badge/Privacy-100%25%20Client--Side-10B981?style=for-the-badge&labelColor=0f172a"/>
&nbsp;
<img src="https://img.shields.io/badge/Interface-Web%20%2B%20CLI-F97316?style=for-the-badge&labelColor=0f172a"/>
&nbsp;
<img src="https://img.shields.io/badge/Language-Python%20%2B%20JavaScript-3B82F6?style=for-the-badge&labelColor=0f172a"/>
&nbsp;
<img src="https://img.shields.io/badge/API%20Keys-Not%20Required-34D399?style=for-the-badge&labelColor=0f172a"/>

</div>

---

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:10b981,50:059669,100:047857&height=3" width="100%"/>

<br/>

<div align="center">

## ⚡ DISTILL ARCHITECTURE & SUMMARIZATION PIPELINE

```
╔══════════════════════════════════════════════════════════════════╗
║         DISTILL AI — FREQUENCY SCORING SUMMARIZER PIPELINE      ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║   INPUT: Any Raw Text (Article / Essay / Document)              ║
║      │                                                           ║
║      ▼                                                           ║
║   ┌─────────────────────────────────────────┐                    ║
║   │         TEXT PRE-PROCESSING             │                    ║
║   │   • Split input into sentences          │                    ║
║   │   • Tokenize each sentence              │                    ║
║   │   • Lowercase all tokens               │                    ║
║   │   • Strip punctuation                  │                    ║
║   │   • Remove common stopwords            │                    ║
║   │       ("the", "is", "and", ...)        │                    ║
║   └─────────────────────────────────────────┘                    ║
║      │                                                           ║
║      ▼                                                           ║
║   ┌─────────────────────────────────────────┐                    ║
║   │      WORD FREQUENCY TABLE              │                    ║
║   │   Count occurrences of every word      │                    ║
║   │   Normalize against most frequent word │                    ║
║   │   Each word gets a score 0.0 → 1.0     │                    ║
║   └─────────────────────────────────────────┘                    ║
║      │                                                           ║
║      ▼                                                           ║
║   ┌─────────────────────────────────────────┐                    ║
║   │      SENTENCE SCORING ENGINE           │                    ║
║   │   Score = avg frequency of its words   │                    ║
║   │   Avoids bias toward long sentences    │                    ║
║   │   Every sentence gets a final score    │                    ║
║   └─────────────────────────────────────────┘                    ║
║      │                                                           ║
║      ▼                                                           ║
║   ┌─────────────────────────────────────────┐                    ║
║   │      SUMMARY EXTRACTION                 │                    ║
║   │   Pick top-N highest scoring sentences │                    ║
║   │   Re-order to match original flow      │                    ║
║   │   Return clean, readable summary       │                    ║
║   └─────────────────────────────────────────┘                    ║
║                                                                  ║
║   OUTPUT: Clean Summary + Compression % + Sentence Count        ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

---

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:10b981,50:059669,100:047857&height=3" width="100%"/>

## ✨ Features

<table>
<tr>
<td width="50%">

### 🧠 Summarization
- ✅ **Zero dependencies** — pure Python standard library
- ✅ **Frequency-scoring algorithm** — no ML needed
- ✅ **Instant results** in milliseconds
- ✅ **Compression percentage** shown per summary
- ✅ **Custom sentence count** — you control length
- ✅ **Natural reading order** preserved always

### 📋 Use Cases
| Use Case | Benefit |
|----------|---------|
| 📚 **Students** | Summarize long articles fast |
| ✍️ **Writers** | Condense drafts instantly |
| 🔬 **Researchers** | Extract key findings |
| 💼 **Professionals** | Digest reports in seconds |

</td>
<td width="50%">

### ⚡ Technical
- ✅ **No API keys** — works fully offline
- ✅ **No AI models** — deterministic & fast
- ✅ **Python CLI** — scriptable & importable
- ✅ **Live web demo** — runs on GitHub Pages
- ✅ **100% client-side** — your text stays private
- ✅ **Cross-platform** — Windows, Mac, Linux

### 🌐 Interface
- ✅ **Web UI** — paste & click, done
- ✅ **CLI tool** — pipe text or pass files
- ✅ **Importable module** — use in your own code
- ✅ **No server needed** — zero backend
- ✅ **Mobile friendly** — works on any device
- ✅ **Free forever** — just open and use

</td>
</tr>
</table>

---

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:10b981,50:059669,100:047857&height=3" width="100%"/>

## 🚀 Live Demo

<div align="center">

### 🌐 [https://mabdullahab614-alt.github.io/quick-summarizer](https://mabdullahab614-alt.github.io/quick-summarizer)

*Paste any text, choose how many sentences you want, and get your summary in under a second. Free. No account needed.*

</div>

---

## 🛠 Tech Stack

<div align="center">

| | Technology | Purpose |
|--|-----------|---------|
| 🐍 | **Python 3** (Standard Library only) | Core summarization engine |
| 🌐 | **Vanilla JavaScript** | Live web demo logic |
| 🎨 | **HTML + CSS** | Web interface |
| 📄 | **GitHub Pages** | Free static deployment |
| ⚡ | **Frequency Scoring** | Extractive summarization algorithm |

</div>

---

## ⚡ Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/mabdullahab614-alt/quick-summarizer.git
cd quick-summarizer

# 2. Summarize text directly
python summarizer.py "Your long passage goes here." --sentences 3

# 3. Summarize a file
python summarizer.py --file article.txt --sentences 5

# 4. Pipe text in
cat article.txt | python summarizer.py --sentences 3
```

> Or try it instantly (no install): **[mabdullahab614-alt.github.io/quick-summarizer](https://mabdullahab614-alt.github.io/quick-summarizer)**

---

## 🔌 Use as a Module

```python
from summarizer import summarize_text

result = summarize_text(my_text, num_sentences=3)
print(result["summary"])
print(result["compression_percent"], "% shorter")
```

> No external packages required — pure Python standard library only.

---

## 📊 Performance

<div align="center">

| Metric | Value |
|--------|-------|
| Dependencies | **Zero** |
| API Keys Required | **None** |
| Average Speed | **< 10ms** |
| Privacy | **100% Local** |
| Platform Support | **All Platforms** |
| Deployment | **GitHub Pages (Static)** |

</div>

---

## ⚠️ Disclaimer

> This tool is an **extractive summarizer** — it picks the most important existing sentences.
> It does not rewrite or paraphrase text.
> For best results, use well-structured paragraphs as input. 📝

---

## 🏆 Rating

<div align="center">

| Category | Score |
|----------|-------|
| Algorithm Simplicity | ⭐⭐⭐⭐⭐ |
| Speed (< 10ms) | ⭐⭐⭐⭐⭐ |
| Privacy (100% Local) | ⭐⭐⭐⭐⭐ |
| Zero Dependencies | ⭐⭐⭐⭐⭐ |
| Ease of Use | ⭐⭐⭐⭐⭐ |
| Deployment | ⭐⭐⭐⭐⭐ |
| **OVERALL** | **⭐⭐⭐⭐⭐ 10/10** |

</div>

---

## 📜 License

**All Rights Reserved © 2026 Abdullah Javid**

This repository and its contents — including source code, algorithm, and documentation — are made publicly visible **for portfolio and demonstration purposes only**.

**No part of this repository may be copied, modified, distributed, sublicensed, or used** — in whole or in part, for personal, educational, or commercial purposes — without explicit prior written permission from the author.

Forking or cloning this repository does **not** grant any rights to use, reproduce, or redistribute its contents.

If you are interested in using any part of this project, please contact me directly for permission:

📧 **Email:** mabdullah.ab614@gmail.com
🔗 **GitHub:** [github.com/mabdullahab614-alt](https://github.com/mabdullahab614-alt)
💼 **LinkedIn:** [linkedin.com/in/abdullah-javid-b217a2384](https://www.linkedin.com/in/abdullah-javid-b217a2384/)

---

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:10b981,50:059669,100:047857&height=3" width="100%"/>

<div align="center">

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-mabdullahab614--alt-181717?style=for-the-badge&logo=github&labelColor=0f172a)](https://github.com/mabdullahab614-alt)
&nbsp;
[![Email](https://img.shields.io/badge/Email-mabdullah.ab614%40gmail.com-ff2d2d?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mabdullah.ab614@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdullah%20Javid-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdullah-javid-b217a2384/)
&nbsp;
[![Live Demo](https://img.shields.io/badge/⚡%20Try%20Distill%20AI-10b981?style=for-the-badge&labelColor=0f172a)](https://mabdullahab614-alt.github.io/quick-summarizer)
&nbsp;
[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-Abdullah%20Javid-8B5CF6?style=for-the-badge&labelColor=0f172a)](https://portfolio-website-jet-iota-21.vercel.app/)

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:047857,60:059669,100:10b981&height=120&section=footer&animation=twinkling" width="100%"/>

**⭐ Star this repo if it helped you!**

</div>
