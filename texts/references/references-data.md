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
      default-text: description
      infos-texts: 
        - period
        - type
        - approach
        - resources
      tabs:
        - infos
        - gallery 
        - links 
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
  links-keys: 
    - refs 
    - code

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
    fr: Clients
    en: Clients
  period:
    fr: Période
    en: Period
  type:
    fr: Type de projet
    en: Project type
  description:
    fr: Description
    en: Description
  approach:
    fr: Approche et contraintes
    en: Approach
  resources:
    fr: Ressources
    en: Resources
  technos:
    fr: Technologies
    en: Technos
  refs:
    fr: Références
    en: References
  code:
    fr: Code source
    en: Code
---
