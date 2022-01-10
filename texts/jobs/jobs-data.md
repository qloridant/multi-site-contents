---
type: jobs

options:
  title-key: title
  columns-size: half
  has-readmore: true
  card-modal: true
  miniature-keys: 
    - job_status
    - tags
  modal-keys: false
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
