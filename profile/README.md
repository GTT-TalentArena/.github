<!--
  Perfil de la organización. Las imágenes se generan desde la web
  (GTT-TalentArena/gtt-talentarena.github.io → npm run previews) para que la marca sea una sola.
-->

<a href="https://gtt-talentarena.github.io">
  <img alt="GTT — Més que dades (more than data). Football analytics team at More than a Hack 2027, Talent Arena, Barcelona." src="https://raw.githubusercontent.com/GTT-TalentArena/.github/main/profile/assets/banner.png" width="100%">
</a>

<p align="center">
  <a href="https://gtt-talentarena.github.io"><b>Website</b></a> ·
  <a href="https://gtt-talentarena.github.io/log/"><b>Log</b></a> ·
  <a href="https://github.com/GTT-TalentArena/more-than-a-hack-2027"><b>Challenge fork</b></a> ·
  <a href="https://landing.mobileworldcapital.com/more-than-a-hack-2027"><b>More than a Hack 2027</b></a>
</p>

We are **GTT**, a team of five combining data analysis, algorithm development, evaluation and engineering to explore
football through data. We are competing in **More than a Hack 2027** at Talent Arena, Barcelona — turning raw tracking
data into possession, frame by frame: _reproducible, measured, explained._

<br>

<sub><code>01 — THE CHALLENGE</code></sub>

## Who has _the ball?_

For every frame of a full LaLiga match, say which team has the ball. One CSV, one row per frame, scored against a
private frame-by-frame ground truth — no jury, just a number. The tracking is automatic and uncorrected: gaps, identity
switches, and a ball nobody can see for long stretches. That is the game.

<a href="https://github.com/GTT-TalentArena/more-than-a-hack-2027">
  <img alt="Animated, simulated tracking: 22 players and the ball on a pitch, with the possession label switching between home, away and dead ball." src="https://raw.githubusercontent.com/GTT-TalentArena/.github/main/profile/assets/pitch.svg" width="100%">
</a>

| **199,319** | **H · A · D · X** | **41%** | **0.2433** |
| :-- | :-- | :-- | :-- |
| frames to label | home, away, dead ball, no answer | scored frames with the ball unseen | baseline spellF1 to beat |

<sub>Simulated players, not match data. The dashed line is the official baseline's idea — the player nearest the
ball; the dashed ring is the ball the tracking lost.</sub>

<br>

<sub><code>02 — THE SQUAD</code></sub>

## The _squad._

<a href="https://gtt-talentarena.github.io/#squad">
  <img alt="The squad: Jimy, Edu, Alejandro, Nico and Pablo." src="https://raw.githubusercontent.com/GTT-TalentArena/.github/main/profile/assets/squad.png" width="100%">
</a>

| # | Player | Role | Links |
| :-- | :-- | :-- | :-- |
| 01 | **Jimy** | _Pending_ | [GitHub](https://github.com/jimy-k4) · [Portfolio](https://jimy-portfolio.vercel.app/en) · [LinkedIn](https://www.linkedin.com/in/juan-llinares-mauri) |
| 02 | **Edu** | _Pending_ | [GitHub](https://github.com/hxst1) · [Portfolio](https://edu-ruiz-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/edu-ruiz-cantos) |
| 03 | **Alejandro Molines** | _Pending_ | [GitHub](https://github.com/AlejandroMolines) · [LinkedIn](https://www.linkedin.com/in/alejandro-molines-00524822b/) |
| 04 | **Nico** | _Pending_ | [GitHub](https://github.com/n1co2611) · [Portfolio](https://nicolashidalgo.es/) · [LinkedIn](https://www.linkedin.com/in/nicolashidalgosalinas/) |
| 05 | **Pablo** | _Pending_ | Coming soon |

<sub>Roles are still being decided.</sub>

<br>

<sub><code>03 — APPROACH</code></sub>

## How we _play._

> Our goal is not just to build a solution, but to understand why it works, how it can fail, and how to improve it.

- **Reproducible** _by default._ — Every number we report regenerates from the repository with one command.
- **Measure** _before we believe._ — spellF1 and macroF1 on the public window, plus our own validation.
- **Know why** _it fails._ — Tracking gaps, identity switches, an invisible ball: we study the failure modes.
- **Built** _together._ — Small pull requests, written decisions, shared notebooks. Five people, one codebase.

`Data analysis` `Algorithm development` `Evaluation & validation` `Engineering`

Every study, experiment and iteration — including the ones that fail — goes into **[the log](https://gtt-talentarena.github.io/log/)**.

<br>

<sub><code>04 — FIXTURES</code></sub>

## The _fixtures._

| Date | Fixture | Who |
| :-- | :-- | :-- |
| **20 Oct 2026** | **Kick-off** — match data released, the Initial Challenge opens online | All teams |
| **17 Nov 2026** | **Phase 1 deadline** — possession CSV, public repository and technical write-up | All teams |
| **26 Nov 2026 → 14 Jan 2027** | **Innovation Challenge** — open analytical and tactical questions | Top 20 |
| **02 Mar 2027** | **Final Pitch** — on stage at Talent Arena, Barcelona | Top 5 |

<br>

<sub><code>05 — FOLLOW</code></sub>

## Follow the _build._

<a href="https://gtt-talentarena.github.io">
  <img alt="Preview of the GTT website." src="https://raw.githubusercontent.com/GTT-TalentArena/.github/main/profile/assets/site.png" width="100%">
</a>

<table>
  <tr>
    <td width="50%">
      <a href="https://github.com/GTT-TalentArena/more-than-a-hack-2027"><img alt="more-than-a-hack-2027 — our fork of the Phase 1 challenge" src="https://raw.githubusercontent.com/GTT-TalentArena/.github/main/brand/social-challenge.png" width="100%"></a>
      <br><b><a href="https://github.com/GTT-TalentArena/more-than-a-hack-2027">more-than-a-hack-2027</a></b><br>
      <sub>Our fork of the challenge — where the possession model lives.</sub>
    </td>
    <td width="50%">
      <a href="https://github.com/GTT-TalentArena/gtt-talentarena.github.io"><img alt="gtt-talentarena.github.io — the GTT website" src="https://raw.githubusercontent.com/GTT-TalentArena/.github/main/brand/social-web.png" width="100%"></a>
      <br><b><a href="https://github.com/GTT-TalentArena/gtt-talentarena.github.io">gtt-talentarena.github.io</a></b><br>
      <sub>The website, the log and the generator of every image on this page.</sub>
    </td>
  </tr>
</table>

---

<p align="center">
  <i>Més que dades.</i> · <b>GTT — TalentArena</b> · Barcelona, 2026<br>
  <sub>Independent team. Not affiliated with FC Barcelona, Metrica Sports or Mobile World Capital Barcelona.</sub>
</p>
