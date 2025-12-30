---
marp: true
theme: default
_class: lead
paginate: true
backgroundColor: #0f172a
style: |
  section {
    font-size: 22px;
    color: #f8fafc;
    line-height: 1.5;
    padding: 2.5em;
  }
  h1, h2, h3 {
    color: #38bdf8;
    font-weight: 700;
    margin-bottom: 0.6em;
  }
  h1 { font-size: 2.8em; }
  h2 { font-size: 2.2em; }
  h3 { font-size: 1.6em; color: #fbbf24; }
  p, li {
    font-size: 1.15em;
    margin-bottom: 0.6em;
  }
  ul, ol {
    margin-left: 1.4em;
    margin-bottom: 1.2em;
  }
  img {
    max-width: 85%;
    display: block;
    margin: 1em auto;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  }
  .header-logos {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 0em;
  }
---

# Refonte Inscription SoliCode
### Sprint 1 — Interface publique

**Réalisé par :**   EL ACHIRI MOHAMED AYMANE 
**Encadré par :** M. ESSARRAJ Fouad

---

# Contexte & objectif Sprint 1

Livrer une interface publique statique et responsive qui reflète la maquette :
- Présentation du centre (hero, valeurs)
- Catalogue des formations (Web & Mobile)
- Navigation responsive (menu mobile)
- Contact & carte intégrée
- UX accessible et animations légères

---
# Méthodologies
 Méthodologie ( SCRUM )
![w:800 SCRUM](imgs-presenatation/SCRUM.JPG)

---


# Méthodologies

 Méthodologie ( design Thinking )
![w:800 design Thinking](imgs-presenatation/designThinking.jpg)

---
# Fonctionnalités
- Navigation responsive (desktop + mobile)
- Hero avec CTA d'inscription
- Section statistiques (KPI)
- Fiches formations (liste / détail)
- Formulaire contact simple
- Menu mobile avec icône utilisateur
- Thème clair/sombre persistant
- Smooth scroll + back-to-top
- Icônes Lucide + animations Motion One

---
<!-- # use case  -->
## use case
![Use case](imgs-presenatation/uc.png)

---

# Lab
-LENIS


---


# maquette 

   ![Maquette](imgs-presenatation/maquette.png) 

---

# Scripts & Interactions techniques

Implémenté dans index.html :
- Tailwind config (couleurs soliBlue / soliYellow, fonts)
- Lucide.createIcons()
- Lenis smooth scroll (global, scroll-to anchors)
- Motion One (inView animations, hero load, scroll progress)
- Theme toggle (localStorage)
- Mobile menu open/close logic
- Back-to-top integrated with Lenis

---







# Des retours ?


