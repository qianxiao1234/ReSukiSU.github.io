---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "ReSukiSU"
  text: "一个更加稳定的SukiSU分支"
  tagline: "让SukiSU再次伟大！"
  image:
    src: /logo.svg
    alt: refs
  actions:
    - theme: brand
      text: 快速上手
      link: ./guide/install
    - theme: alt
      text: Github
      link: https://github.com/ReSukiSU/ReSukiSU
    - theme: alt
      text: 关于项目
      link: ./guide/introduce

features:
  - title: 基于 KernelSU 的 ROOT 方案
    details: ReSukiSU是一个 KernelSU 下游，由 SukiSU Ultra 分支而来
    icon: <i class="ri-hashtag"></i>
  - title: Non-GKI 内核支持
    details: ReSukiSU更专注于对Non-GKI的兼容支持，不会炸飞Non-GKI设备
    icon: <i class="ri-checkbox-circle-fill"></i>
  - title: 最小化钩子兼容
    details: ReSukiSU可以兼容当前最新的最小化钩子，无需选hook
    icon: <i class="ri-checkbox-fill"></i>
    link: ./guide/manual-hooks.md
  - title: KPM 支持
    details: ReSukiSU是基于SukiSU Ultra的分支，理论上也是支持KPM，但注意这功能并不完善。
    icon: <i class="ri-puzzle-2-fill"></i>
---

