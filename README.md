# AI → Machine Learning

A free, self-contained course that takes a computer-science graduate from the
**definition of AI** all the way through **classical Machine Learning** — and
deliberately stops before Deep Learning.

**Read it here → https://addahadi.github.io/ai-to-ml/**

Its guiding principle is **understand the *why* before the *how***: every idea
is motivated with engineering intuition first, and each algorithm is built
**from scratch in NumPy** before any library is introduced.

---

## What makes it different

- **No prerequisites beyond programming.** It's written for a software engineer,
  using concrete engineering framings rather than abstract math-first proofs.
- **From scratch, then the library.** You implement the mechanics in raw NumPy,
  so Scikit-learn later feels like a shortcut you understand — not a black box.
- **No build system. No JavaScript. No dependencies.** Every page is
  hand-authored static HTML linking one shared stylesheet. It works **offline** —
  just open any `.html` file in a browser.

## Status

The course is being written and published **in progress**. **9 of a planned 29
lessons** (across 8 modules) are live today; the [roadmap](index.html) shows the
full plan, with each upcoming lesson marked `Planned`. New lessons ship as
they're finished.

## Structure

| Path | What it is |
|------|-----------|
| `index.html` | The roadmap / table of contents — the full 8-module, 29-lesson outline. |
| `modules/lesson-NN.html` | Individual lessons. `lesson-01.html` is the reference implementation. |
| `assets/style.css` | The entire design system, shared by every page. |

## Running locally

Just open `index.html` in a browser. For live reload while editing, any static
file server works:

```
python -m http.server 8000
```

Then visit http://localhost:8000/.

## Contributing

Errata and small fixes are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Dual-licensed (see [LICENSE](LICENSE)):

- **Course content** (prose, lessons, figures, page HTML/CSS) —
  [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Reuse and adapt
  freely, including commercially, with attribution to **Missoum Hadi Adda**.
- **Code** (the Python / NumPy samples) — [MIT](LICENSE).

## Author

Written by **[Missoum Hadi Adda](https://www.linkedin.com/in/adda-missoum-a534a7319/)**.
Drafted collaboratively with [Claude Code](https://claude.com/claude-code).
