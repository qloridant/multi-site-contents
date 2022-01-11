---
type: project

options:
  title-key: name
  images-key: images
  images-ratio: 7by4
  columns-size: half

  card-modal: true
  card-modal-config:
    column-left: false
    column-right: 
      tabs:
        - infos
        - gallery 
      images-gallery: true

  miniature-keys: 
    - technos
    - clients
  texts-keys: 
    - description 
    - period
    - type
    - approach
    - resources
  tags-keys: 
    - key: clients
      color: primary
    - key: technos
      color: light
  filters: 
    activate: true
    items: 
      - name: technos
      - name: clients

items: 
  - file: ./texts/references/data-patch.md
  - file: ./texts/references/barometre-action-publique.md
  - file: ./texts/references/africartes.md
  - file: ./texts/references/aides-entreprises.md
  - file: ./texts/references/open-mobility-indicators.md
  - file: ./texts/references/parcours-entree-dans-emploi.md
  - file: ./texts/references/play-with-transitions.md
  - file: ./texts/references/digital-transport-for-africa.md
  - file: ./texts/references/observatoire-open-data-des-territoires.md
  - file: ./texts/references/apiviz.md
  - file: ./texts/references/solidata.md
  - file: ./texts/references/open-scraper.md
  - file: ./texts/references/validata.md
  - file: ./texts/references/dbnomics.md
  - file: ./texts/references/open-fisca.md
  - file: ./texts/references/synapse.md
  - file: ./texts/references/hydroviz.md
  - file: ./texts/references/libviz.md


dict:
  clients:
    fr: clients
    en: clients
  period:
    fr: période
    en: period
  type:
    fr: type
    en: type
  description:
    fr: description
    en: description
  approach:
    fr: approche
    en: approach
  resources:
    fr: ressources
    en: resources
  technos:
    fr: technologies
    en: technos
  refs:
    fr: références
    en: refs
  code:
    fr: code source
    en: code
---
