---
datapackage:
  title: Dataset Template
  description: A template for a dataset to publish on DataHub. Uses the Data Package metadata.
  licenses:
  - path: http://opendatacommons.org/licenses/pddl/
    title: Open Data Commons Public Domain Dedication and License v1.0
  resources:
  - path: Data-systems-mapping.csv
    title: C02 PPM per decade
    name: c02-per-decade
    format: csv
    schema:
      fields:
      - name: year
        type: date
      - name: blah
        type: number
      - name: data-systems
        type: text
---

Here's some text.

You can add as much text as you like.

The data files will be automatically displayed here.

We can add a chart:

<LineChart
  data="./Data-systems-mapping.csv"
  title="Data systems"
  xAxis="year"
  yAxis="blah"
/>
