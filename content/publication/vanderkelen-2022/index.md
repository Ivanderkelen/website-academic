---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Evaluating a reservoir parametrisation in the vector-based global routing model
  mizuRoute (v2.0.1) for Earth System Model coupling
subtitle: ''
summary: ''
authors:
- Inne Vanderkelen
- Shervan Gharari
- Naoki Mizukami
- Martyn P. Clark
- David M. Lawrence
- Sean Swenson
- Yadu Pokhrel
- Naota Hanasaki
- Ann Van Griensven
- Wim Thiery
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-05-28T15:41:59+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-05-28T13:41:49.430741Z'
publication_types:
- '2'
abstract: Human-controlled reservoirs have a large influence on the global water cycle.
  While global hydrological models use generic parametrisations to model human dam
  operations, the representation of reservoir regulation is often still lacking in
  Earth System Models. Here we implement and evaluate a widely used reservoir parametrisation
  in the global river routing model mizuRoute, which operates on a vector-based river
  network resolving individual lakes and reservoirs, and which is currently being
  coupled to an Earth System Model. We develop an approach to determine the downstream
  area over which to aggregate irrigation water demand per reservoir. The implementation
  of managed reservoirs is evaluated by comparing to simulations ignoring inland waters,
  and simulations with reservoirs represented as natural lakes, using (i) local simulations
  for 26 individual reservoirs driven by observed inflows, and (ii) global-scale simulations
  driven by runoff from the Community Land Model. The local simulations show a clear
  added value of the reservoir parametrisation, especially for simulating storage
  for large reservoirs with a multi-year storage capacity. In the global-scale application,
  the implementation of reservoirs shows an improvement in outflow and storage compared
  to the no-reservoir simulation, but compared to the natural lake parametrisation,
  an overall similar performance is found. This lack of impact could be attributed
  to biases in simulated river discharge, mainly originating from biases in simulated
  runoff from the Community Land Model. Finally, the comparison of modelled monthly
  streamflow indices against observations highlights that the inclusion of dam operations
  improves the streamflow simulation compared to ignoring lakes and reservoirs. This
  study overall underlines the need to further develop and test water management parametrisations,
  as well as to improve runoff simulations for advancing the representation of anthropogenic
  interference with the terrestrial water cycle in Earth System Models.
publication: '*Geoscientific Model Development*'
doi: 10.5194/gmd-2022-16
links:
- name: URL
  url: https://doi.org/10.5194/gmd-2022-16
---
