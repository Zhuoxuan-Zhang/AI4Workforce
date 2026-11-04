# AI4Workforce Workshop Homepage

Static workshop homepage for the IEEE BigData 2026 workshop:
**AI in Workforce: Human Labor vs. AI Automation (Zero-Sum or Positive-Sum?)**

## File Structure

```txt
/
├── index.html
├── style.css
├── assets/
│   ├── speakers/
│   │   └── placeholder-speaker.svg
│   └── organizers/
│       ├── tianlong_chen.jpg
│       ├── xinwen.png
│       ├── eva_zhao.jpg
│       ├── wenwen.jpeg
│       ├── seancao.jpg
│       ├── lirong.jpg
│       ├── wenyue.png
│       ├── JinhaoDuan.jpeg
│       ├── zt.png
│       ├── mz.jpg
│       ├── Zhuoxuan_Zhang.jpeg
│       └── placeholder-organizer.svg
└── README.md
```

## Local Preview

Open `index.html` directly in a browser, or run a simple static server:

```bash
cd /Users/bytedance/Documents/web
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Update Guide

- Workshop metadata (title, affiliation, date/location): `index.html` hero section.
- Call for papers and review details: `#cfp` section in `index.html`.
- Important dates: `#dates` section in `index.html`.
- Invited speakers: `#speakers` section in `index.html`.
- Core and student organizers (with photos and bios): `#organizers` section in `index.html`.
- Program table: `#program` section in `index.html`.
- Visual style: `style.css`.

## Photo Sources

Organizer photos are copied from:
`/Users/bytedance/Downloads/BigData_2026_Workshop_Proposal___Human_and_AI/figs/`

Current keynote speaker photos are placeholders because no keynote image files were present in the provided proposal folder.

## Deployment

This site is GitHub Pages compatible (plain HTML/CSS, no framework required).
