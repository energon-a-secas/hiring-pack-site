<div align="center">

# Hiring Pack

Turn a Vibe Check scorecard into a hiring summary, resume bullets, follow-up questions, and a reading list.

[![Live][badge-site]][url-site]
[![HTML5][badge-html]][url-html]
[![CSS3][badge-css]][url-css]
[![JavaScript][badge-js]][url-js]
[![Claude Code][badge-claude]][url-claude]
[![License][badge-license]](LICENSE)

[badge-site]:    https://img.shields.io/badge/live_site-0063e5?style=for-the-badge&logo=googlechrome&logoColor=white
[badge-html]:    https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[badge-css]:     https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
[badge-js]:      https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[badge-claude]:  https://img.shields.io/badge/Claude_Code-CC785C?style=for-the-badge&logo=anthropic&logoColor=white
[badge-license]: https://img.shields.io/badge/license-MIT-404040?style=for-the-badge

[url-site]:   https://hiringpack.neorgon.com/
[url-html]:   #
[url-css]:    #
[url-js]:     #
[url-claude]: https://claude.ai/code

</div>

---

## Overview

Hiring Pack takes the six behavioral scores and notes from a [Vibe Check](https://interviews.neorgon.com/) interview and turns them into a decision-ready package: a hiring summary, resume-worthy bullets, targeted follow-up questions, and a suggested reading list. Everything runs in the browser — no signup, no data leaves the page.

It's the writing step of the **Hiring Toolkit**, a connected flow across Vibe Check, Resume Forge, Character Sheet, and Playbook.

**Live:** hiringpack.neorgon.com

---

## Features

- **Score-to-summary** — six 1–5 sliders map to a written hiring recommendation
- **Resume bullets** — generates achievement-framed bullets from the interview notes
- **Follow-up questions** — surfaces the gaps worth probing in the next round
- **Reading list** — suggests prep material tied to the candidate's weak spots
- **Copy & download** — export the full pack as plain text in one click

---

## Running locally

```bash
make serve
```

Or manually:

```bash
python3 -m http.server 8843
```

---

## Architecture

```
hiring-pack-site/
├── index.html          # HTML shell + form + output
├── css/
│   └── style.css       # All styles
├── js/
│   └── app.js          # Slider wiring, pack generation, copy/download
├── og-preview.jpg      # 1200×630 social preview
├── robots.txt
├── sitemap.xml
├── CNAME
├── Makefile
├── LICENSE
└── README.md
```

---

<div align="center">
<sub>Part of <a href="https://neorgon.com/">Neorgon</a></sub>
</div>
