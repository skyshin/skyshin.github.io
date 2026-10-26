# skyshin.github.io

Bilingual (Korean / English) site for JongHo Shin's AI/ML/agent consulting for Korean companies doing business in the US.

- `index.html` — the whole site. Every visible text has a Korean `<span lang="ko">` and English `<span lang="en">` pair; the toggle (or `?lang=en`) switches them.
- `assets/css/site.css` — styles. Colors are tokens at the top of the file.
- Low-profile mode: `<meta name="robots" content="noindex, nofollow">` keeps the page out of Google/Naver search while links shared in posts, emails and flyers still work. Delete that line to allow indexing.
- Hosting: GitHub Pages from `main`. The same files run unchanged on Cloudflare Pages, Netlify or Vercel (no build step).
