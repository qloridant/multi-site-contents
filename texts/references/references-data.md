---
type: project

options:
  title-key: name
  cover-key: logo
  cover-ratio: 6by4
  columns-size: one-quarter
  has-gallery: true
  card-modal: true
  miniature-keys: 
    - description
    - technos
    - clients
  modal-keys: 
    - clients
    - period
    - type
    - description
    - approach
    - resources
    - technos
    - refs
    - code
  tags-keys: 
    - key: clients
      color: primary
  filters: 
    activate: true
    items: 
      - name: technos
      - name: clients

items: 
  - file: ./texts/references/data-patch.md
  - file: ./texts/references/data-patch.md
  - file: ./texts/references/data-patch.md
  - file: ./texts/references/data-patch.md
  - file: ./texts/references/data-patch.md

dict:
  clients:
    fr: clients
    en: clients
  period:
    fr: period
    en: period
  type:
    fr: type
    en: type
  description:
    fr: description
    en: description
  approach:
    fr: approach
    en: approach
  resources:
    fr: resources
    en: resources
  technos:
    fr: technos
    en: technos
  refs:
    fr: refs
    en: refs
  code:
    fr: code
    en: code
---
