<!--
  maintenance, yearly: bump the 2023-now / uptime 8y fields in both
  assets/banner-*.svg files (edit the SVGs directly; layout source is
  banner-lab/concepts-2026/trace-full.svg, palette maps in
  banner-lab/NOTES.md). Bump ?v= on any SVG change; after pushing, wait a
  few minutes before loading the page or bump ?v= again (raw CDN lag).
  The banner's commit hash is the real git blob hash of the claim line:
  printf 'i build the ml & ai stack end to end\n' | git hash-object --stdin
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg?v=48">
  <img alt="A terminal session, three commands of the jcb CLI. jcb runs, newest first, each with a duration bar: Gametime (2023 to now, running, ML platform plus agentic harnesses), Rivian (2022 to 2023, autonomy data platform), Mercedes-Benz R&D (2019 to 2022, sensor fusion plus fleet telemetry), aiPod at Idealab (2018, ML plus simulation at a startup studio). jcb whoami: name, Jacob Beaudin; role, senior machine learning engineer II; education, MS Analytics and BS Industrial Engineering, USC. jcb status: at work, machine learning model training and serving, software development lifecycle automation, and building agents for data and automation; own time, a notebook server in Rust. Ending in commit 800617a: i build the ml and AI stack end to end. Agent: jacob.beaudin." src="assets/banner-light.svg?v=48" width="100%">
</picture>
