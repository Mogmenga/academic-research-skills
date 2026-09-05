# Stratégie de Revue de Littérature - Thèse Disparités Régionales Agricoles

Objectif : Répondre à ton besoin prioritaire "Français - Besoin de revue de littérature"

## Méthode recommandée : Revue systématique PRISMA adaptée (pas besoin de faire full Cochrane, mais structure PRISMA aide jury)

### Étape 1 : Définir 3 revues distinctes (une par essai)

Ne fais PAS une seule revue énorme. Fais 3 revues ciblées :

**Revue 1 (Essai 1) - Mesure et dynamique :**
Question PICO : Comment mesurer la convergence/divergence agricole régionale en Afrique subsaharienne ?
Mots-clés : "regional convergence" AND "agricultural productivity" AND Africa, "sigma convergence" "beta convergence" agriculture, "spatial inequality" agriculture, "Theil index" agricultural

**Revue 2 (Essai 2) - Déterminants :**
Question : Quels facteurs expliquent les disparités spatiales agricoles ?
Mots-clés : "determinants" "regional disparities" agriculture, "spatial econometrics" agriculture Africa, "market access" agricultural productivity, "infrastructure" "agricultural productivity" spatial

**Revue 3 (Essai 3) - Politiques et chocs :**
Question : Effets des politiques agricoles et chocs climatiques sur inégalités régionales
Mots-clés : "input subsidy" Africa regional inequality, "agricultural policy" "regional disparity", "climate shock" "agricultural productivity" convergence, "resilience" regional agriculture

### Étape 2 : Bases de données à interroger (par ordre priorité)

**Pour économiste :**
1.  **EconLit / RePEc / IDEAS** - CORE pour toi (https://ideas.repec.org)
2.  **Web of Science / Scopus** - via université
3.  **Google Scholar** - complément, mais attention qualité
4.  **OpenAlex** (openalex.org) - gratuit, utilisé par ce toolkit pour vérif citations
5.  **AGRICOLA / CAB Abstracts** - spécifique agri

**Pour contexte Burkina Faso :**
6.  **AFD, Banque Mondiale, FAO, IFPRI** - rapports gris très utiles
7.  **INSD, DGESS, CAPES** - littérature grise nationale

**Outils de ce repo :**
- `bibliography_agent` va chercher sur Semantic Scholar + OpenAlex + Crossref + arXiv automatiquement
- Il vérifie existence réelle de chaque référence (anti-hallucination)

### Étape 3 : Protocole d'inclusion / exclusion (à noter pour jury)

**Inclusion :**
- 1990-2025 (ou 2000-2025 pour recent)
- Articles peer-reviewed + working papers de qualité (World Bank Policy Research, IFPRI Discussion Papers, CSAE Oxford)
- Régions : Afrique SSA prioritaire, mais aussi comparaisons Inde, Chine, Amérique latine
- Langues : Anglais + Français

**Exclusion :**
- Études purement agronomiques sans dimension économique spatiale
- Études sans données empiriques (purement théoriques sauf seminal)

### Étape 4 : Matrice de littérature (outil essentiel)

Crée un Excel / Zotero avec colonnes :

| Auteur Année | Région Pays | Période | Mesure disparité | Méthode | Déterminants testés | Résultat clé | Gap identifié | Pertinence pour toi |
|--------------|-------------|---------|------------------|---------|---------------------|--------------|---------------|---------------------|

Ce toolkit génère automatiquement une `literature_matrix` en Phase 1.

### Étape 5 : Papiers séminaux à lire en PRIORITÉ (starter pack)

**Convergence régionale (base théorique) :**
- Barro & Sala-i-Martin (1991, 1992) - The classic
- Quah (1993) - Distribution dynamics
- Magrini (2004) - Regional convergence literature review

**Agriculture et disparités en Afrique :**
- Binswanger & Townsend (2000) - Agricultural determinants
- Dorosh & Thurlow (2014) - Agriculture and small towns, Africa
- Vandercasteelen et al. (2018) - Urban proximity and agricultural performance in Africa
- Hirvonen & Headey (2018) - Agricultural productivity and rural nonfarm

**Économétrie spatiale appliquée agri :**
- Anselin (1988) - Spatial Econometrics Methods and Models (livre)
- LeSage & Pace (2009) - Introduction to Spatial Econometrics
- Schmidtner et al. (2012) - Spatial distribution of agricultural productivity

**Burkina Faso / Afrique de l'Ouest spécifique :**
- Wouterse & Taylor (2008) - Burkina Faso migration and agriculture
- Kaminski et al. - travaux sur productivité agricole BF
- Rapports PNSR II, PNIA, Banque Mondiale Burkina Faso Agricultural Sector Review
- Diao et al. (IFPRI) sur transformation agricole Afrique

**Politiques et chocs :**
- Jayne & Rashid (2013) - Input subsidy programs in SSA
- Barrett et al. - climate shocks and poverty traps

### Étape 6 : Organisation rédactionnelle revue (pour chaque essai)

Structure type d'une revue critique (pas descriptive !) :

1.  Introduction de la revue : question, pourquoi importante, comment organisée
2.  Bloc 1 : Fondements théoriques (convergence, NGE)
3.  Bloc 2 : Évidence empirique internationale
4.  Bloc 3 : Évidence Afrique SSA
5.  Bloc 4 : Spécificité Burkina Faso / gap
6.  Cadre conceptuel qui en découle + hypothèses

> **Erreur à éviter** : revue "catalogue" (A dit X, B dit Y). Il faut **critiquer, synthétiser, identifier contradictions et gaps**.

### Étape 7 : Comment utiliser ce repo concrètement MAINTENANT

Dans Claude Code, tu peux lancer :

```
"Do a systematic review on regional convergence of agricultural productivity in Sub-Saharan Africa with PRISMA, focus on Burkina Faso"

ou

"Guide my research on determinants of regional agricultural disparities spatial econometrics"

ou

"Give me a literature review on input subsidy programs effects on regional inequality Africa"
```

Le système va :
1. Te poser des questions socratiques pour affiner
2. Chercher sur 4 bases (S2 + OpenAlex + Crossref + arXiv)
3. Vérifier que chaque référence existe vraiment (lookup_verified)
4. Produire annotated bibliography + synthesis + gap analysis

### Livrable attendu fin Mois 1

- 60-80 références triées et annotées (Zotero)
- 3 matrices de littérature (une par essai)
- 10 pages de revue pour Essai 1 (version draft)
- Liste de 5 gaps clairs qui justifient ta thèse

Besoin que je lance une première revue pour toi sur un des essais ?
