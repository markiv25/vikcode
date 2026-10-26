<div align="center">
  <img src="assets/banner.svg" alt="Loadline — system design, under interview conditions" width="100%">
  <p><strong>A hands-on system design interview practice space.</strong></p>
  <p>Clarify requirements · estimate scale · draw the system · test the tradeoffs</p>
</div>

## App previews

### Interview workbench

Follow a timed interview flow, make notes, build an architecture, and see how the design responds to load.

<img src="assets/screenshots/interview-workbench.svg" alt="Loadline interview workbench showing interview stages, a system architecture canvas, candidate notes, and live system signals" width="100%">

### Problem library

Browse 23 system design prompts by difficulty and track practice progress in your browser.

<img src="assets/screenshots/problem-library.svg" alt="Loadline problem library with search, difficulty filters, system design prompts, and practice progress" width="100%">

## Run locally

Open `index.html` in a modern browser. There is no build step or dependency install. Google Fonts are optional; system font fallbacks are included.

## Practice flow

Each prompt guides you through clarifying requirements, estimating scale, drawing an architecture, testing load and failure scenarios, and debriefing tradeoffs. The 45-minute timer, stage progress, notes, designs, and submissions are saved in the browser using local storage.

The canvas models traffic, latency, capacity, and estimated monthly cost. It is an interview aid; API design, data modeling, consistency, and durability still need to be explained by the candidate.

## Visual assets

The repository includes its banner and app preview artwork in [`assets/`](assets/). These are local SVG files and need no external image host.
