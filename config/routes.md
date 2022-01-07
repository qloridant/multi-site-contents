---
routes: 

  - name: home 
    url: /
    contentFolder: ./texts/landing
    sections: 
      - name: head
        component: logoAnimated
        files:
          fr: landing-head-fr.md
      - name: head
        component: textComponent
        files:
          fr: landing-text-fr.md

  - name: team 
    url: /team
    contentFolder: ./texts/landing
    sections: 
      - name: head
        component: dataCards
        files:
          fr: team-data.md
  
  - name: who-are-we
    url: /who-are-we
    contentFolder: ./texts/who-are-we
    sections: 
      - name: head
        component: textComponent
        files:
          fr: who-head-fr.md
  
  - name: references
    url: /references
    contentFolder: ./texts/references
    sections: 
      - name: ref-data
        component: gridComponentData
        files:
          fr: references-data.md
  
  - name: services
    url: /services
    contentFolder: ./texts/who-are-we
    sections: 
      - name: head
        component: textComponent
        files:
          fr: landing-head-fr.md
  
  - name: we-like
    url: /we
    contentFolder: ./texts/we-like
    sections: 
      - name: head
        component: textComponent
        files:
          fr: landing-head-fr.md
  
  - name: blog
    url: /blog
    contentFolder: ./texts/we-like
    sections: 
      - name: head
        component: textComponent
        files:
          fr: landing-head-fr.md
  
  - name: podcasts
    url: /podcasts
    contentFolder: ./texts/we-like
    sections: 
      - name: head
        component: dataCards
        files:
          fr: podcast-fr.md
  
  - name: legal
    url: /legal
    contentFolder: ./texts/legal-mentions
    sections: 
      - name: head
        component: textComponent
        files:
          fr: legal-fr.md
--- 
