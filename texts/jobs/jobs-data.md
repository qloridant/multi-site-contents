---
type: jobs

options:
  title-key: title
  columns-size: half
  has-readmore: true
  readmore-divider: h1
  
  card-modal: true
  card-modal-config:
    column-left: false
    column-right: true

  miniature-keys: 
    - job_status
    - tags
  tags-keys: 
    - key: job_status
      color: primary
    - key: tags
      color: info
  filters: 
    activate: true
    items: 
      - name: job_status
      - name: tags
    
items:
  - file: ./texts/jobs/posts/jobs-post-01-fr.md

dict:
  job_status: 
    fr: statut
    en: status
  tags:
    fr: tags
    en: tags
---
