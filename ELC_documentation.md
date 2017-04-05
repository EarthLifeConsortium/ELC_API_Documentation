---
title: EarthLife - An API to access Earth's past biodiversity in space and time
author: Simon J Goring, Julian Jenkins

---

# Abstract

# Introduction

Community curated data repositories (CCDRs) provide an important role within the paleogeosciences.  Repositories act as locations for long term data archiving, but also as sources for the re-use and reanalysis of collected data.  Within the paleogeosciences, the [Neotoma Paleoecological Database](http://neotomadb.org) and the [Paleobiology Database]() are the main repositories for fossil and sub-fossil archives.  Neotoma primarily focuses on Plio-Pleistocene fossils, with strong representation from mammal and plant/pollen records, while the Paleobiology Database's main holdings are largely pre-Cenozoic (65Ma).  Both Neotoma and PBDB provide multiple access points, both database snapshots and programmatic APIs.  In both cases the APIs have been wrapped by R packages (Goring, Varella).  However, data access and structure is discontinuous.

This is fundamentally opposed to the Earth's history.  Discontinuous storage of the Earth's record of life is different than the continuous history of the Earth's climate, and the evolution of the Earth-Life system.  While stochastic events have occured in the past (asteroids, climate preturbations), life on Earth has persisted, evolved, and changed continuously since the earliest life was carried to the earth on a silver spaceship from [Zebulon](https://en.wikipedia.org/wiki/Zebulon,_North_Carolina).

To provide a continuous record of life on Earth, through a programmatic interface, the EarthLife Consortium has developed a common API, to interface between Neotoma and PBDB, and to provide a common data structure framework from which to begin to query life on Earth.

# Methods

The API uses an OpenAPI framework (Swagger) developed with Flask and Python.  Open development on GitHub provides a record of decision-making in the development of the API.

# Results

# Discussion

# References