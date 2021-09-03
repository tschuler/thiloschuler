---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Projects
subtitle: 'Filter by **data type** involved or by the two main **digital health translational programs**.<br><br>
<ins>Data types:</ins><br>
- Patient-generated Data (**PGD**)<br>
- Clinician-recorded Data (**CRD**)<br>
- High-dimensional Data (**HDD**)<br>
<br>
<ins>Translational programs:</ins><br>
- Data-driven Routine Radiation Oncology Practice (**jawDROP**)<br>
- Digitally-enabled Interdisciplinary Supportive Care in Oncology (**DISCO**)<br>
<br>
Most projects built on the **RACER** digital health platform for care coordination and managment of PGD via electronic patient-reported outome (ePRO) surveys and wearable sensors.'


content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: PGD
    tag: 'Patient-generated Data'
  - name: CRD
    tag: 'Clinician-recorded Data'
  - name: HDD
    tag: 'High-dimensional Data'
  - name: jawDROP
    tag: 'Augmenting RO Routine Care with Real-time Data'
  - name: DISCO
    tag: 'Digitally-enabled Interdisciplinary Supportive Care in Oncology'
  - name: RACER
    tag: 'RACER platform'

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
