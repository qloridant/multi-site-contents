---
background-color: white
logo-left: ./images/logos/logo MULTI - 003-bis.png
fixed-top: true

buttons-left: 

buttons-right: 

  - name: who-are-we 
    link: /who-are-we
    component: dropdownLink
    label: 
      fr: Qui sommes-nous
      en: Who are we
    submenu: 
      - name: manifesto
        link: /manifesto
        component: simpleLink
        label: 
          fr: Manifeste
          en: Manifesto
      - name: team
        link: /team
        component: simpleLink
        label: 
          fr: Equipe
          en: Team
      - name: references
        link: /references
        component: simpleLink
        label: 
          fr: Références
          en: References
      - name: jobs
        link: /jobs
        component: simpleLink
        label: 
          fr: On recrute
          en: We recruit

  - name: offer 
    link: /offer
    component: dropdownLink
    label: 
      fr: Offre de services
      en: Services
    submenu: 
      - name: dev
        link: /dev
        component: simpleLink
        label: 
          fr: Développement
          en: Development
      - name: data
        link: /data
        component: simpleLink
        label: 
          fr: Data & algos
          en: Data & algos
      - name: design
        link: /design
        component: simpleLink
        label: 
          fr: Design
          en: Design
      - name: audit
        link: /audit
        component: simpleLink
        label: 
          fr: Conseil
          en: Audit

  - name: we-like 
    link: /we-like
    component: dropdownLink
    label: 
      fr: On aime
      en: We like
    submenu: 
      - name: network
        link: /network
        component: simpleLink
        label: 
          fr: Notre réseau
          en: Our network
      - name: podcast
        link: /podcasts
        component: simpleLink
        label: 
          fr: Podcasts
          en: Podcasts

  - name: contact 
    link: /contact
    component: dropdownLink
    label: 
      fr: Contact
      en: Contact
    submenu: 
      - name: infos
        link: /infos
        component: simpleLink
        label: 
          fr: Infos
          en: Infos
      - name: contribute
        link: /contribute
        component: simpleLink
        label: 
          fr: Contribuer
          en: Contribute
      - name: legal
        link: /legal
        component: simpleLink
        label: 
          fr: Mentions légales
          en: Legal

  - name: switch-locale
    component: switchLocaleDropdown
    appearance: rounded
    

--- 

# Navbar config file
