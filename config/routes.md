---
routes: 

  - name: home 
    url: /
    sections: 
      - name: logo
        component: logoAnimated
        files:
          fr: ./texts/landing/landing-head-fr.md
      - name: head
        component: textComponent
        files:
          fr: ./texts/landing/landing-text-fr.md

  - name: team 
    url: /team
    sections: 
      - name: head
        component: dataCards
        files:
          fr: ./texts/team/team-data.md
  
  - name: who-are-we
    url: /who-are-we
    sections: 
      - name: head
        component: textComponent
        files:
          fr: ./texts/who-are-we/who-head-fr.md
  
  - name: references
    url: /references
    sections: 
      - name: ref-data
        component: gridComponentData
        files:
          fr: ./texts/references/references-data.md
  
  - name: services
    url: /services
    sections: 
      - name: head
        component: textComponent
        files:
          fr: ./texts/who-are-we/landing-head-fr.md
  
  - name: we-like
    url: /we
    sections: 
      - name: head
        component: textComponent
        files:
          fr: ./texts/we-like/landing-head-fr.md
  
  - name: blog
    url: /blog
    sections: 
      - name: head
        component: textComponent
        files:
          fr: ./texts/we-like/landing-head-fr.md
  
  - name: podcasts
    url: /podcasts
    sections: 
      - name: head
        component: dataCards
        files:
          fr: ./texts/we-like/podcast-fr.md
  
  - name: legal
    url: /legal
    sections: 
      - name: data
        component: textDataComponent
        files:
          fr: ./texts/legal-mentions/legal.md
      - name: head
        component: textComponent
        files:
          fr: ./texts/legal-mentions/legal-fr.md
--- 
