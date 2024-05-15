---
title: Evaluating a reservoir parametrisation in the vector-based global routing model
  mizuRoute (v2.0.1) for Earth System Model coupling
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
date: '2022-06-01'
publishDate: '2024-05-15T11:38:48.502749Z'
publication_types:
- article-journal
publication: '*Geoscientific Model Development*'
doi: 10.5194/gmd-2022-16
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
links:
- name: URL
  url: https://doi.org/10.5194/gmd-2022-16
---