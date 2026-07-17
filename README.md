<!-- the banner is two hand-written SVGs (light/dark). no widgets, nothing phones home. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img src="assets/banner-light.svg" width="100%" alt="shmor3 — systems engineer">
</picture>

Most of what I build comes down to coordination: many small programs behaving
like one reliable system. Right now that's an agent runtime in Rust, with its
own small language, a scheduler, and a plugin layer that speaks MCP and ACP so
tools and models can attach without bespoke glue.

The parts I care about are the ones you only notice when they're missing —
isolation, clean scheduling, failure you can reason about.

<sub>Cambridge, MA · <a href="https://rstanford.com">rstanford.com</a></sub>
