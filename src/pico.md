---
title: Pico
description: Structure du framework Pico.
layout: base
tags: primary
---
- pico.classless.scss @import ->
  - **pico** @import ->
    - **variables** -> configuration + responsive
    - **themes/default** -> @import colors + styles + light + dark (variables + config)
    - **layout/**
      - **document**
      - **sectioning**
      - **container**
      - **section**
      - **grid**
      - **scroller**
    - **content/**
      - **typography**
      - **embedded**
      - **button**
      - **form**
      - **form-checkbox-radio**
      - **form-alt-input-types**
      - **table**
      - **code**
      - **miscs**
    - **components/**
      - **accordions**
      - **card**
      - **modal**
      - **nav**
      - **progress**
      - **dropdown**
    - **utilities**
      - **loading**
      - **tooltip**
      - **accessibility**
      - **reduce-motion**

[GitHub](https://github.com/picocss/pico)