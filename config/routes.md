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
          fr: ./data/team/team-data.md

  - name: references
    url: /references
    sections: 
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
          fr: ./data/jobs/jobs-data.md

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
          fr: ./texts/offer/dev-head-fr.md

  - name: data
    url: /data
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/offer/data-head-fr.md

  - name: design
    url: /design
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/offer/design-head-fr.md

  - name: audit
    url: /audit
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/offer/audit-head-fr.md


  # WE LIKE
  - name: we-like
    url: /we-like
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/we-like/landing-head-fr.md
  
  - name: network
    url: /network
    sections: 
      - name: head
        component: DataGrid
        files:
          fr: ./texts/we-like/blog-head-fr.md

  - name: podcasts
    url: /podcasts
    sections: 
      - name: head
        component: DataGrid
        files:
          fr: ./texts/we-like/podcast-fr.md
  
  - name: blog
    url: /blog
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/we-like/blog-head-fr.md
  
  # CONTACT
  - name: contact
    url: /contact
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/legal-mentions/legal.md

  - name: contribute
    url: /contribute
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/legal-mentions/legal.md

  - name: legal
    url: /legal
    sections: 
      - name: data
        component: textDataComponent
        files:
          fr: ./texts/legal-mentions/legal.md
      - name: head
        component: TextComponent
        files:
          fr: ./texts/legal-mentions/legal-fr.md
--- 
