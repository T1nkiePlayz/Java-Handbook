# Java Handbook

**A visual, deep-dive handbook for learning Java and Kotlin from absolute zero.**

🔗 **Live site: [java.handbook.ashtontink.com](https://java.handbook.ashtontink.com/)**

*Java & Kotlin from Zero* is a single-page, self-contained guide that takes you from installing the JDK all the way through coroutines, Flow and Kotlin Multiplatform — with equal weight on what Java does well and where Kotlin is simply better.

## What's inside

32 chapters, 138 annotated code examples, 42 comparison/reference tables, 157 callouts and a 20-question self-quiz — all in one file, with no build step for the published site.

| # | Part I — Java (18 chapters) | Anchor |
|---|------------------------------|--------|
| 1 | What is Java? | [`#intro`](https://java.handbook.ashtontink.com/#intro) |
| 2 | Setup &amp; first program | [`#setup`](https://java.handbook.ashtontink.com/#setup) |
| 3 | Variables &amp; types | [`#variables`](https://java.handbook.ashtontink.com/#variables) |
| 4 | Control flow &amp; methods | [`#control`](https://java.handbook.ashtontink.com/#control) |
| 5 | Classes &amp; objects | [`#oop`](https://java.handbook.ashtontink.com/#oop) |
| 6 | Inheritance &amp; interfaces | [`#inheritance`](https://java.handbook.ashtontink.com/#inheritance) |
| 7 | Records, enums &amp; sealed | [`#datamodels`](https://java.handbook.ashtontink.com/#datamodels) |
| 8 | Generics &amp; variance | [`#generics`](https://java.handbook.ashtontink.com/#generics) |
| 9 | Collections &amp; streams | [`#collections`](https://java.handbook.ashtontink.com/#collections) |
| 10 | Strings, text &amp; I/O | [`#strings`](https://java.handbook.ashtontink.com/#strings) |
| 11 | Error handling | [`#errors`](https://java.handbook.ashtontink.com/#errors) |
| 12 | Lambdas &amp; Optionals | [`#functional`](https://java.handbook.ashtontink.com/#functional) |
| 13 | Annotations &amp; reflection | [`#reflection`](https://java.handbook.ashtontink.com/#reflection) |
| 14 | Threads &amp; memory model | [`#concurrency`](https://java.handbook.ashtontink.com/#concurrency) |
| 15 | Executors &amp; virtual threads | [`#async`](https://java.handbook.ashtontink.com/#async) |
| 16 | Inside the JVM | [`#jvm`](https://java.handbook.ashtontink.com/#jvm) |
| 17 | Builds, tests &amp; modules | [`#tooling`](https://java.handbook.ashtontink.com/#tooling) |
| 18 | Performance vs. others | [`#performance`](https://java.handbook.ashtontink.com/#performance) |

| # | Part II — Kotlin (10 chapters) | Anchor |
|---|--------------------------------|--------|
| 19 | What is Kotlin? | [`#kotlin-intro`](https://java.handbook.ashtontink.com/#kotlin-intro) |
| 20 | Basics &amp; functions | [`#kotlin-basics`](https://java.handbook.ashtontink.com/#kotlin-basics) |
| 21 | Null safety | [`#nulls`](https://java.handbook.ashtontink.com/#nulls) |
| 22 | Classes &amp; data classes | [`#kotlin-oop`](https://java.handbook.ashtontink.com/#kotlin-oop) |
| 23 | Collections &amp; sequences | [`#kotlin-collections`](https://java.handbook.ashtontink.com/#kotlin-collections) |
| 24 | Extensions &amp; scopes | [`#kotlin-fp`](https://java.handbook.ashtontink.com/#kotlin-fp) |
| 25 | Coroutines | [`#coroutines`](https://java.handbook.ashtontink.com/#coroutines) |
| 26 | Flow &amp; streams | [`#flow`](https://java.handbook.ashtontink.com/#flow) |
| 27 | Java ↔ Kotlin interop | [`#interop`](https://java.handbook.ashtontink.com/#interop) |
| 28 | Multiplatform &amp; tooling | [`#multiplatform`](https://java.handbook.ashtontink.com/#multiplatform) |

| # | Part III — Mastery (4 chapters) | Anchor |
|---|---------------------------------|--------|
| 29 | Compiler errors decoded | [`#errors-decoded`](https://java.handbook.ashtontink.com/#errors-decoded) |
| 30 | Projects &amp; study plan | [`#roadmap`](https://java.handbook.ashtontink.com/#roadmap) |
| 31 | Cheat sheets &amp; glossary | [`#cheatsheet`](https://java.handbook.ashtontink.com/#cheatsheet) |
| 32 | Test yourself | [`#quiz`](https://java.handbook.ashtontink.com/#quiz) |

## Features

- **Dark / light theme** — click the toggle or press <kbd>T</kbd>; your choice persists across visits (View Transitions API for a smooth cross-fade).
- **Sticky table of contents** — scroll-spy highlighting via `IntersectionObserver`, with a collapsible drawer on mobile.
- **Reading progress bar** — tracks how far through the handbook you are.
- **Copy-to-clipboard** on every code sample, with syntax highlighting for `java`, `kotlin`, `shell`, `gradle` and `xml`.
- **Callouts** — tips, warnings, myths and notes, each visually distinct.
- **Charts, timelines and stat strips** — comparisons and history at a glance.
- **Self-quiz** — 20 questions with expandable answers to check your understanding.
- **Glossary A–Z** — the vocabulary of both languages in one place.
- **Responsive, dependency-free** — plain HTML, CSS and JavaScript with zero external assets or frameworks.

## Running locally

No build step for the published page. Either open the file directly:

```bash
open docs/index.html        # macOS
xdg-open docs/index.html    # Linux
```

or serve it over HTTP:

```bash
cd docs
python3 -m http.server 8000
# → http://localhost:8000
```

The source fragments used to assemble it live alongside the build script in a private authoring directory; `docs/index.html` is the single artefact GitHub Pages serves.

## Deployment

The site is published with **GitHub Pages** from the `main` branch, `/docs` folder, served at [java.handbook.ashtontink.com](https://java.handbook.ashtontink.com/) via the custom domain declared in [`docs/CNAME`](docs/CNAME).

> [!NOTE]
> The root-level [`CNAME`](CNAME) file duplicates the same domain and is only needed if you ever switch the Pages source to the repository root. If you change the domain, update **both** files.

## Repository layout

```
.
├── CNAME            # custom domain (root, for a root-based Pages source)
├── README.md
└── docs/
    ├── CNAME        # custom domain used by the live Pages site
    └── index.html   # the entire handbook — HTML, CSS and JS in one file
```

## Contributing

Issues and pull requests are welcome — whether it's a typo, a clearer explanation for a tricky section, or a new example.

## License

No license has been declared for this repository yet. All rights reserved by default — add a `LICENSE` file if you plan to open it up.
