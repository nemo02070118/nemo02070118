<!-- Profile README · Huannian Jin -->

<div align="center">

<a href="https://github.com/nemo02070118">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=5B8DEF&center=true&vCenter=true&width=720&lines=I+don't+hunt+factors.+I+prove+where+the+hunt+is+blind.;Misallocated%2C+not+mispriced%3A+a+law%2C+not+a+heuristic.;Independent+researcher+%C2%B7+systems+builder+%C2%B7+already+in+motion." alt="typing banner" />
</a>

</div>

# Huannian Jin

<div align="center">

![JF](https://img.shields.io/badge/JF-MS%202026--0738%20·%20external%20review-0b1021?style=flat-square&labelColor=0b1021&color=1f3a5f)
![EFA](https://img.shields.io/badge/EFA-submitted-0b1021?style=flat-square&labelColor=0b1021&color=1f3a5f)
[![SSRN](https://img.shields.io/badge/SSRN-working%20paper-0b1021?style=flat-square&labelColor=0b1021&color=1f3a5f)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7607684)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--9124--9152-0b1021?style=flat-square&labelColor=0b1021&color=a6ce39&logo=orcid&logoColor=white)](https://orcid.org/0009-0006-9124-9152)
[![Repro](https://img.shields.io/badge/replication-localstrength--repro-0b1021?style=flat-square&labelColor=0b1021&color=1f3a5f&logo=github&logoColor=white)](https://github.com/nemo02070118/localstrength-repro)

</div>

> **A factor's strength can be real but misallocated** — a mistake about *where* it is tested, not *whether* it works. One pooled reallocation moves out-of-sample Sharpe **0.85 → 1.30** (three-quarters of the way to the 1.45 ceiling); the converse proves no router recovers the rest (floor at **m\* ≈ 1.3 factors**). The replication crisis is a measurement problem, and measurement obeys a law.

On academic leave from Shanghai Lixin University of Accounting and Finance for full-time research · building in public · `huanian.jin@outlook.com`

**▸ Latest:** *The Resolution Limit of Factor Discovery — Why the Replication Crisis Is a Measurement Problem.* Derives the law $q^2(\tau)=\tau/(1+\tau)$ and shows every empirical result, positive and negative, is one reading of a single curve. [paper + full replication →](https://github.com/nemo02070118/localstrength-repro)

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=nemo02070118&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&bg_color=0b1021&title_color=5B8DEF&text_color=c9d1d9&icon_color=5B8DEF" alt="stats" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nemo02070118&layout=compact&hide_border=true&langs_count=8&bg_color=0b1021&title_color=5B8DEF&text_color=c9d1d9" alt="top langs" />

<img height="160" src="https://github-readme-streak-stats.herokuapp.com/?user=nemo02070118&hide_border=true&background=0b1021&stroke=1f3a5f&ring=5B8DEF&fire=5B8DEF&currStreakLabel=5B8DEF&sideLabels=c9d1d9&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9" alt="streak" />

</div>

<div align="center">
  <img alt="quant terminal — resolution limit, equity curve, and a contribution-grid snake" src="https://raw.githubusercontent.com/nemo02070118/nemo02070118/main/assets/quant-hero.svg" width="920" />
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nemo02070118/nemo02070118/output/github-snake-dark.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/nemo02070118/nemo02070118/output/github-snake.svg" />
  </picture>
</div>

---

## Proof of work — start here

| Surface | Open |
|---|---|
| **Live portfolio** | [nemo02070118.github.io/boatfx-repro](https://nemo02070118.github.io/boatfx-repro/) |
| **Resolution-limit paper + repro** | [`localstrength-repro`](https://github.com/nemo02070118/localstrength-repro) |
| **BOAT Terminal + OpenClaw** | [#terminal](https://nemo02070118.github.io/boatfx-repro/#terminal) |
| **Walkthrough video** | [youtu.be/tVHLUQy93rg](https://youtu.be/tVHLUQy93rg) |
| **Repro pack** | [`python repro.py`](https://github.com/nemo02070118/boatfx-repro) |
| **AI factory internals** | [`system_showcase`](https://github.com/nemo02070118/boatfx-repro/tree/main/system_showcase) |

---

## The scientific claim

A universal significance hurdle is a fixed-aperture instrument. Below its resolution it cannot separate a factor that is genuinely absent from one whose strength lives in a venue it never inspects. The law of that limit is

$$q^2(\tau)=\frac{\tau}{1+\tau},\qquad \tau=\frac{m\lambda}{\sigma^2}.$$

Read it from the top and a discarded factor revives: moved as a pool to the venue it fits, Sharpe climbs **0.85 → 1.30**, a six-factor alpha of **3.8%/yr** (*t* = 8.3). Read it from the bottom and every negative result appears as the low-*m* branch — the oracle's extra 0.14 is the winner's curse, tradable rank is one, and fine routing *loses* 0.18. An independent China A-share panel of 5,441 stocks reproduces the gain out of sample at the magnitude the law predicts.

- **The Resolution Limit of Factor Discovery** — working paper (resolution law + converse)
- **Global Weakness, Local Strength** — deployable predecessor → **Journal of Finance** · MS 2026-0738 · passed desk, in external review (editor: Antoinette Schoar); also submitted to **EFA**

---

## BOAT Terminal — the builder desk

About a year of nights shipping a usable multi-agent quant framework, in public.

| Layer | Stack |
|---|---|
| **Rust** | compute / engine core |
| **Python** | strategies + AI |
| **Flutter** | desk UI |
| **OpenClaw** | Captain · Chanlun · Physics (Ising / LPPLS / TDA) · Factor · Risk · Execution → parliament verdict (DeepSeek) |

Lens case: 600519.SH (Moutai) with Chanlun overlays, an Ising temperature signal, and a V12 CSI-300 backtest under Monte Carlo and walk-forward. Personal A-share book (a label kept separate from the paper and its backtests): roughly ¥50k → ~¥1.00M. Still rough, posted for critique.

---

## Engineering mass

Zheshang Securities systems internship — **sole developer** of the task system: **56 modules · ~64k LoC · >95% coverage**. The public repo is the receipt.

## How I use AI

Cursor · Claude Code · Codex · cloud agents draft. **I gate; CI decides what ships.** See [`AGENTS.md`](https://github.com/nemo02070118/boatfx-repro/blob/main/AGENTS.md) and [`DISCIPLINE.md`](https://github.com/nemo02070118/boatfx-repro/blob/main/DISCIPLINE.md).

## Contact

[huanian.jin@outlook.com](mailto:huanian.jin@outlook.com) · [@nemo02070118](https://github.com/nemo02070118)

<div align="center">
<img src="https://komarev.com/ghpvc/?username=nemo02070118&style=flat-square&color=5B8DEF&label=profile+views" alt="views" />
</div>
