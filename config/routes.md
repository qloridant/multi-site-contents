---
routes: 

  # LANDING
  - name: home 
    url: /
    sections: 
      - name: logo
        component: LogoAnimated
        options: [ no-translation ]
        files:
          fr: ./texts/landing/landing-head-fr.md
          en: ./texts/landing/landing-head-fr.md
      - name: head
        component: TextComponent
        files:
          fr: ./texts/landing/landing-text-fr.md
          en: ./texts/landing/landing-text-en.md
  
  # WHO ARE WE
  - name: who-are-we
    url: /who-are-we
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/who-are-we/who-head-fr.md

  - name: manifesto
    url: /manifesto
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/who-are-we/manifesto-fr.md

  - name: team 
    url: /team
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/team/team-head-fr.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/team/team-data.md

  - name: references
    url: /references
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/references/references-head-fr.md
      - name: ref-data
        component: DataGrid
        files:
          fr: ./texts/references/references-data.md

  - name: jobs 
    url: /jobs
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/jobs/jobs-head-fr.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/jobs/jobs-data.md

  # OFFER
  - name: offer
    url: /offer
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/offer/offer-head-fr.md

  - name: dev
    url: /dev
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/offer/offer-dev-fr.md

  - name: data
    url: /data
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/offer/offer-data-fr.md

  - name: design
    url: /design
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/offer/offer-design-fr.md

  - name: audit
    url: /audit
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/offer/offer-audit-fr.md


  # WE LIKE
  - name: we-like
    url: /we-like
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/we-like/we-like-head-fr.md
  
  - name: network
    url: /network
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/we-like/network-head-fr.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/we-like/network-data.md

  - name: podcasts
    url: /podcasts
    sections:
      - name: head
        component: TextComponent
        files:
          fr: ./texts/podcasts/podcasts-head-fr.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/podcasts/podcasts-data.md
  
  - name: blog
    url: /blog
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/blog/blog-data.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/blog/blog-data.md

  # CONTACT
  - name: contact
    url: /contact
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/contact/contact-head-fr.md

  - name: infos
    url: /infos
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/contact/infos-head-fr.md

  - name: contribute
    url: /contribute
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/contact/contribute-head-fr.md

  - name: legal
    url: /legal
    sections: 
      - name: data
        component: TextDataComponent
        files:
          fr: ./texts/contact/legal-data.md
--- 
