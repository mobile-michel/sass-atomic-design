---
title: Atomic
description: Structure de Atomic Design.
layout: base
tags: primary
---
- 00-elements -> **src/_components/elements/**
  - 00-meta
  - 01-global
  - 02-list
  - 03-image
  - 04-form-elements
  - 05-button
- 01-components -> **src/_components/components/**
  - 00-accordion
  - 01-dropdown
  - 02-card
  - 03-form
  - 04-table
- 02-landmarks -> **src/_components/landmarks/**
  - 00-header
  - 01-main
  - 02-footer
  - 03-navigation
  - 04-sidebar
  - 05-section
  - 06-article
- 03-layouts -> **src/_layouts/**
  - 00-landing-page
  - 01-blog
  - 02-portfolio
  - 03-e-commerce
  - 04-documentation
- 04-content
  - 00-datas -> **src/data/**
  - 02-images -> **src/assets/images/ to /assets/images/**
  - 03-javascript -> **src/assets/js/ to /assets/js/**
  - 01-pages -> **src/pages**
- 05-css-framework -> **_scss/ to /assets/css/**
  - 00-base (colors, variables, reset, typography)
  - 01-components (navigation, article, form, table)
  - 02-landmarks (header, main, footer, sidebar, section)
  - 03-layouts (landing, blog, portfolio, documentation)