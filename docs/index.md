---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "ReSukiSU"
  text: "A more stable fork of SukiSU"
  tagline: "Make SukiSU Great Again!"
  image:
    src: /logo.svg
    alt: refs
  actions:
    - theme: brand
      text: Get started
      link: /guide/install
    - theme: alt
      text: Github
      link: https://github.com/ReSukiSU/ReSukiSU
    - theme: alt
      text: About ReSukiSU
      link: /guide/introduce

features:
  - title: KernelSU-based ROOT Solution
    details: ReSukiSU is a KernelSU downstream project, derived from the SukiSU Ultra branch.
    icon: <i class="ri-hashtag"></i>
  - title: Non-GKI Kernel Support
    details: ReSukiSU focuses more on compatibility with Non-GKI, ensuring Non-GKI devices won't break.
    icon: <i class="ri-checkbox-circle-fill"></i>
  - title: Scope-Minimized Hook Compatibility
    details: ReSukiSU is compatible with the latest minimal hooks, no need to select hooks.
    icon: <i class="ri-checkbox-fill"></i>
    link: ./guide/manual-hooks.md
  - title: KPM Support
    details: ReSukiSU is a branch based on SukiSU Ultra, theoretically supporting KPM, but note that this feature is not fully developed.
    icon: <i class="ri-puzzle-2-fill"></i>
---

