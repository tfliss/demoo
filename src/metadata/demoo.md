---
layout: ontology_detail
id: demoo
title: Demo Ontology
jobs:
  - id: https://travis-ci.org/tfliss/demoo
    type: travis-ci
build:
  checkout: git clone https://github.com/tfliss/demoo.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: Demo Ontology is an ontology...
domain: stuff
homepage: https://github.com/tfliss/demoo
products:
  - id: demoo.owl
    name: "Demo Ontology main release in OWL format"
  - id: demoo.obo
    name: "Demo Ontology additional release in OBO format"
  - id: demoo.json
    name: "Demo Ontology additional release in OBOJSon format"
  - id: demoo/demoo-base.owl
    name: "Demo Ontology main release in OWL format"
  - id: demoo/demoo-base.obo
    name: "Demo Ontology additional release in OBO format"
  - id: demoo/demoo-base.json
    name: "Demo Ontology additional release in OBOJSon format"
dependencies:
- id: po
- id: ro
- id: pato

tracker: https://github.com/tfliss/demoo/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.

