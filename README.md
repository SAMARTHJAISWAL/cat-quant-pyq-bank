<img src="favicon.svg" alt="" width="64" align="left">

# CAT Quant PYQ Bank, 2014–2025

[![Live site](https://img.shields.io/badge/open_the_question_bank-samarthjaiswal.github.io-175c78?style=flat-square)](https://samarthjaiswal.github.io/cat-quant-pyq-bank/)

<br clear="left">

**▶ [samarthjaiswal.github.io/cat-quant-pyq-bank](https://samarthjaiswal.github.io/cat-quant-pyq-bank/)**

Every Quantitative Aptitude question from CAT 2014–2025 that could be reliably sourced: **656 questions from 26 papers**, grouped by topic and tagged with year, slot and difficulty. Each one is solved the CAT way: the concept, the formula, the steps, and a shortcut where one exists.

## Features

- **Filter by anything:** area, topic, year, slot, difficulty (Easy / Medium / Hard) and type (MCQ or TITA), or switch from grouping by topic to grouping by paper.
- **Search** across questions, options, subtopics and concepts, for example `remainder`, `circle`, `CI`.
- **Solutions on demand:** each question hides its solution until you open it, and the correct option turns green. "Show all solutions" opens them all for revision.
- **Track progress:** mark questions as done and hide them. Your progress and filters are saved in your own browser, and nothing is sent anywhere.
- **Sources:** every card links to the original question.
- **Works everywhere:** a phone-friendly layout, dark mode that follows your system, keyboard accessible.

## What's inside

| Area | Topic | Questions |
|---|---|---:|
| Arithmetic | Averages, Ratio, % & Mixtures | 109 |
| Arithmetic | Profit, Loss & Interest | 51 |
| Arithmetic | Time, Speed, Distance & Work | 83 |
| Algebra | Linear Equations & Inequalities | 42 |
| Algebra | Quadratic & Polynomial Equations | 49 |
| Algebra | Progressions & Series | 41 |
| Algebra | Functions & Graphs | 34 |
| Algebra | Logarithms, Surds & Indices | 60 |
| Geometry | Geometry & Mensuration | 104 |
| Number System | Number System | 49 |
| Modern Math | P&C and Probability | 26 |
| Modern Math | Set Theory / Venn Diagrams | 8 |

By difficulty: 251 Easy, 279 Medium, 126 Hard. By type: 439 MCQ, 217 TITA.

### Coverage by year

| Year | Papers | Questions |
|---|---|---:|
| 2017–2025 | every slot, complete | 22–34 per slot |
| 2016 | Slot 2 only, from student recall | 8 |
| 2014 | one memory-based paper | 36 |

The IIMs never released the 2014–2016 papers:

- **2014** comes from Career Launcher's memory-based solved paper.
- **2016 Slot 2** comes from questions students recalled right after the exam.
- **CAT 2015** and **2016 Slot 1** are left out on purpose: the sets circulating under those names turned out to be compilations of older CAT questions.

Full per-paper notes are on the site under "Coverage by paper and notes on sources".

## How difficulty is assigned

Where available, difficulty comes from 2IIM's share of test-takers who answered correctly: 40% or more is Easy, 20–39% is Medium, and under 20% is Hard. Otherwise it comes from the source's own label or an assessment, and each card says which.

## Sources and fair use

Questions are restated in their own words, keeping the original numbers and options; the "Original question ↗" link on each card leads to the exact wording. Sources include [2IIM](https://online.2iim.com), [Cracku](https://cracku.in), Career Launcher's memory-based paper and PaGaLGuY student recalls. This is a free study aid and is not affiliated with the IIMs or with any coaching institute.

## Run it locally

It's a single static page with no build step and no dependencies:

```bash
git clone https://github.com/SAMARTHJAISWAL/cat-quant-pyq-bank.git
cd cat-quant-pyq-bank
python3 -m http.server 8000   # then open http://localhost:8000
```

Opening `index.html` directly also works. The question data is embedded in the page as JSON (`<script id="qdata">`), and GitHub Pages serves the `main` branch as is.
