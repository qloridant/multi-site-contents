---
routes: 

  - name: home 
    component: markdown
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
    component: markdown
    url: /team
    contentFolder: ./texts/landing
    sections: 
      - name: head
        component: dataCards
        files:
          fr: team-data.md
  
  - name: who-are-we
    component: markdown
    url: /who-are-we
    contentFolder: ./texts/who-are-we
    sections: 
      - name: head
        component: textComponent
        files:
          fr: who-head-fr.md
  
  - name: references
    component: grid
    url: /references
    contentFolder: ./texts/who-are-we
    sections: 
      - name: head
        component: textComponent
        files:
          fr: landing-head-fr.md
  
  - name: services
    component: markdown
    url: /services
    contentFolder: ./texts/who-are-we
    sections: 
      - name: head
        component: textComponent
        files:
          fr: landing-head-fr.md
  
  - name: we-like
    component: markdown
    url: /we
    contentFolder: ./texts/we-like
    sections: 
      - name: head
        component: textComponent
        files:
          fr: landing-head-fr.md
  
  - name: blog
    component: markdown
    url: /blog
    contentFolder: ./texts/we-like
    sections: 
      - name: head
        component: textComponent
        files:
          fr: landing-head-fr.md
  
  - name: podcasts
    component: list
    url: /podcasts
    contentFolder: ./texts/we-like
    sections: 
      - name: head
        component: dataCards
        files:
          fr: podcast-fr.md
  
  - name: legal
    component: markdown
    url: /legal
    contentFolder: ./texts/legal-mentions
    sections: 
      - name: head
        component: textComponent
        files:
          fr: legal-fr.md
--- 
