# Mots-clés, Bases de Données et Sources - Burkina Faso

## Mots-clés par langue

### Français (pour thèses.fr, Persée, Cairn)
- disparités régionales agriculture
- convergence régionale productivité agricole
- inégalités spatiales développement agricole
- économétrie spatiale agriculture
- productivité agricole Burkina Faso régions
- politiques agricoles inégalités régionales
- résilience climatique agriculture

### Anglais (pour EconLit, RePEc, Scopus - 90% de ta bibliographie sera en anglais)
**Core :**
- regional disparities agricultural development
- agricultural productivity convergence Africa
- spatial inequality agriculture
- spatial econometrics agricultural productivity
- regional convergence Sub-Saharan Africa

**Essai 1 :**
- beta convergence sigma convergence agriculture
- Theil index Gini agricultural productivity
- distribution dynamics agricultural productivity Quah
- club convergence agriculture

**Essai 2 :**
- determinants regional agricultural productivity
- market access agricultural productivity Africa
- infrastructure agricultural productivity spatial
- spatial Durbin model agriculture
- spillover effects agriculture

**Essai 3 :**
- input subsidy regional inequality Africa
- agricultural policy targeting regional disparity
- climate variability agricultural productivity Burkina Faso
- resilience climate shocks regional divergence

## Bases de données à consulter (accès)

### Bibliographiques (articles)
1. **RePEc / IDEAS** : https://ideas.repec.org - GRATUIT, indispensable économiste. Cherche "regional convergence agriculture Africa"
2. **EconLit** : via bibliothèque universitaire (Université Joseph Ki-Zerbo ou Université virtuelle)
3. **OpenAlex** : https://openalex.org - gratuit, API utilisée par ce toolkit
4. **Semantic Scholar** : https://semanticscholar.org - gratuit
5. **Google Scholar** : complément, mais filtre
6. **Scopus / Web of Science** : si accès via université

### Données pour tes estimations

**Burkina Faso - sources nationales (priorité) :**
- **DGESS / Ministère Agriculture** : Enquête Permanente Agricole (EPA) 1996-présent, données production, superficies, rendements par province/région. CONTACTE-LES tôt, accès peut être long.
- **INSD** : Enquête Burkinabè sur Conditions de Vie des Ménages (EHCVM 2018, 2021), RGPH, comptes régionaux
- **RGA (Recensement Général de l'Agriculture)** : 2006-2010, 2017 ?
- **SONAGESS** : prix céréales par marché
- **DGRE** : données pluviométrie stations

**Internationales - gratuites et prêtes :**
- **FAOSTAT** : production agricole par pays, mais pas régional
- **LSMS-ISA World Bank** : pas BF mais modèles méthodologiques
- **CHIRPS (Climate Hazards Group)** : pluviométrie 0.05° résolution, 1981-présent, idéal pour toi. https://www.chc.ucsb.edu/data/chirps
- **World Bank - World Development Indicators** : contrôles macro
- **IFPRI - ASTI** : dépenses R&D agricole
- **Afrobarometer** : perceptions, institutions
- **ACLED** : insécurité (variable contrôle importante pour BF récent)

**Données spatiales :**
- **OpenStreetMap / Humanitarian Data Exchange** : routes, marchés
- **GADM** : shapefiles régions/provinces BF pour cartes et matrice W
- **Distance to markets** : calcule avec QGIS ou R sf

## Logiciels recommandés

**Économétrie :**
- **Stata** (standard éco, beaucoup de packages spatiaux : spreg, xsmle, spmap)
- **R** : packages `spatialreg`, `spdep`, `splm`, `tseries`, `ggplot2` pour cartes
- **Python** : `PySAL`, `geopandas`, `linearmodels` (alternative)

**Cartographie :**
- QGIS (gratuit) pour cartes choroplèthes productivité
- R tmap ou ggplot2

**Gestion biblio :**
- Zotero + Better BibTeX + Zotfile (OBLIGATOIRE pour thèse)
- Crée 3 collections : Essai1, Essai2, Essai3

**Rédaction :**
- LaTeX (recommandé pour thèse éco avec équations) - ce toolkit génère template apa7
- Ou Word avec styles + Zotero plugin

## Contacts utiles Ouagadougou

- Laboratoire d'Économie Publique et de l'Environnement - UJKZ
- CAPES (Centre d'Analyse des Politiques Économiques et Sociales)
- INERA (Institut de l'Environnement et de Recherches Agricoles) - pour données agronomiques
- IFPRI bureau Afrique de l'Ouest (Dakar mais travaux BF)
- Banque Mondiale BF - rapports sectoriels

## Astuce pour accès données DGESS

Lettre officielle de ton directeur de thèse + attestation inscription doctorat + protocole de recherche anonymisé. Prévois 2-4 semaines. Propose de partager résultats préliminaires en échange.
