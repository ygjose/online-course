---
widget: portfolio
headless: true
weight: 30
title: Listado de los cursos
subtitle:
content:
  filters:
    folders:
      - course
    kinds:
      - section
    exclude_tags:
      - preface

  filter_default: 0

  filter_button:
    - name: Cursos Actuales
      tag: current
    - name: Cursos Anteriores
      tag: previous
    - name: Todos los Cursos
      tag: '*'
design:
  columns: '1'
  view: masonry
  flip_alt_rows: false
---
