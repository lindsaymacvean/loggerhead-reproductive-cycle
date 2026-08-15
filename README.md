# Loggerhead Sea Turtle — Reproductive Cycle (interactive proof of concept)

An interactive, single-file visualisation of the loggerhead sea turtle
reproductive cycle, built as a proof of concept for conservation discussion.

**Live demo:** https://lindsaymacvean.github.io/loggerhead-reproductive-cycle/

## What it shows

Starting from **1,000 eggs laid**, a radial "cycle" diagram follows the
survival ring clockwise through five stages —
**Eggs Laid → Hatchlings → Maturing → Mating Pool → Nesting Females** — and
back to the start. The ring thins at each stage as turtles are lost to the
coral "spokes" (predators, poaching, light pollution, boat strikes, pollution
& disease, aging, fertility issues, beach erosion, obstruction/disturbance).

- **Left diagram** — a low-conservation *baseline*.
- **Right diagram** — an interactive *conservation* scenario. The sliders
  reduce each threat **relative to the baseline** (0% = identical to baseline,
  100% = that loss eliminated), so the two are directly comparable.
- The centre shows the headline figure: **successful nesters per 1,000 eggs**.

Everything is mass-conserving: the width of every flow equals the number of
turtles.

## Technical notes

- A single self-contained `index.html` — pure HTML + CSS + vanilla JS.
- The radial diagram is hand-drawn SVG, so there are **no external
  dependencies** and nothing to build or install.
- To adjust the biology, edit the loss rates in the `baseline` object inside
  `index.html`; both diagrams derive from it.

## Running locally

Just open `index.html` in any modern browser.

> The figures are illustrative defaults for a proof of concept, not
> peer-reviewed population data.
