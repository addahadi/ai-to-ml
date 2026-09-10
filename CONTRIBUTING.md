# Contributing

Thanks for reading the course closely enough to want to improve it.

## What's welcome

- **Errata** — typos, broken links, a wrong number in an equation, a rendering
  glitch, a factual slip. Open an [issue](https://github.com/addahadi/ai-to-ml/issues)
  or send a small pull request. Fixes like these are gratefully accepted.
- **Clarity nits** — a sentence that misleads, an example that doesn't land.
  An issue describing *what confused you* is genuinely useful, even without a
  proposed fix.

## What to open an issue for first (rather than a PR)

- **New lessons or substantial rewrites.** The lessons are authored by
  **Missoum Hadi Adda** to keep one consistent voice and pedagogical arc across
  the whole course, so lesson content isn't accepted as drive-by PRs. Ideas,
  outlines, and "here's what I'd want covered" are very welcome as issues.

## House rules for a fix PR

The course has a deliberately minimal architecture — please keep it that way:

- **No build system, no package manager, no JavaScript, no dependencies.**
  Every page is static HTML linking the one shared stylesheet.
- **No inline or per-page styles.** Reuse the existing component classes in
  `assets/style.css`; if a genuinely new style is needed, add it there as a CSS
  variable in *both* the light and dark blocks — never hard-code a hex value in
  markup.
- **Follow `lesson-01.html`.** It's the reference implementation for structure,
  callouts, and voice.
- **Keep things in sync.** A lesson's `<title>`/hero, its entry in `index.html`,
  and the prev/next `.lessonnav` links must all agree.

## Previewing your change

```
python -m http.server 8000
```

Then open http://localhost:8000/ and check the page in both light and dark mode
(your OS theme toggles it).
