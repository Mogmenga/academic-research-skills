# Checklist Doctorat - Démarrage Thèse Agricole Régionale

## Phase 0 : Préparation (Semaines 1-2) - TU ES ICI

- [ ] Lire plan-these.md et valider structure 3 essais avec directeur/trice
- [ ] Installer Zotero + Better BibTeX, créer collections Essai1/2/3
- [ ] Créer compte RePEc, OpenAlex, Semantic Scholar
- [ ] Ouvrir fichier Excel matrice littérature
- [ ] Lister 10 papiers séminaux à lire en priorité (voir revue-litterature-strategie.md)
- [ ] Contacter DGESS/INSD pour demande données EPA/EHCVM (ne pas attendre)
- [ ] Installer Stata/R + packages spatiaux (faire tutoriel Anselin 1988 chapitre 1)
- [ ] Définir avec directeur : région d'étude = 13 régions ou 45 provinces ? (recommandé : provinces pour variation)

## Phase 1 : Revue littérature Essai 1 (Semaines 3-6)

- [ ] Lancer `/ars-lit-review "regional convergence agricultural productivity"` avec ce toolkit
- [ ] Lire 20 papiers cœur convergence régionale
- [ ] Remplir matrice littérature Essai 1 (au moins 25 lignes)
- [ ] Rédiger 8-10 pages revue Essai 1 (version draft)
- [ ] Identifier 3 gaps précis pour Essai 1
- [ ] Formuler hypothèses H1, H2, H3 Essai 1
- [ ] Présenter revue à directeur (séminaire doctorant)

## Phase 2 : Données et faits stylisés Essai 1 (Semaines 7-10)

- [ ] Obtenir données EPA (ou utiliser FAOSTAT/CHIRPS en attendant)
- [ ] Nettoyer données : construire panel productivité par région/province
- [ ] Statistiques descriptives : moyenne, écart-type, CV par année
- [ ] Cartes : productivité 2000, 2010, 2020 (QGIS/R)
- [ ] Graphiques : évolution disparités (sigma-convergence plot)
- [ ] Rédiger section faits stylisés (5 pages)

## Phase 3 : Estimations Essai 1 (Semaines 11-16)

- [ ] Estimation beta-convergence absolue (OLS simple)
- [ ] Beta-convergence conditionnelle (+ contrôles)
- [ ] Sigma-convergence
- [ ] Kernel density + Markov chains (optionnel mais valorisé)
- [ ] Tests robustesse
- [ ] Rédiger résultats + discussion (10 pages)
- [ ] Premier draft complet Essai 1 (25-30 pages)
- [ ] Lancer `"Review this paper"` avec ce toolkit pour auto-évaluation
- [ ] Envoyer à directeur

## Phase 4 : Parallèle - Revue Essai 2 (Semaines 12-18)

- [ ] Revue déterminants + économétrie spatiale
- [ ] Lire LeSage & Pace chapitres 1-4
- [ ] Construire matrice de contiguïté W (shapefile BF)
- [ ] Collecter variables X (pluvio CHIRPS, routes, etc.)

## Règles d'or anti-échec doctorat

1. **Écris dès le début** : pas "je lis d'abord 6 mois". Écris 200 mots/jour même mauvais.
2. **Un essai = un article** : pense publication dès le début, pas juste chapitre thèse
3. **Données tôt** : 80% des retards doctorat = attente données. Lance demandes maintenant.
4. **Versionnage** : Git ou Dropbox avec historique. Ce repo utilise git.
5. **Anti-hallucination** : ce toolkit vérifie chaque citation sur 4 bases. Ne jamais inventer référence.
6. **Rendez-vous régulier directeur** : toutes les 3 semaines minimum avec livrable concret (pas "j'ai lu").

## Modèle d'email demande données DGESS

> Objet : Demande de données EPA pour thèse doctorat économie agricole régionale
>
> Madame, Monsieur le Directeur,
> Je suis doctorant(e) en économie à [Université], sous la direction de [Nom], sur le thème "Essais sur les dynamiques de disparités régionales de développement agricoles au Burkina Faso".
> Dans le cadre de mon premier essai sur la convergence régionale de la productivité, je sollicite l'accès aux données de l'Enquête Permanente Agricole (EPA) désagrégées au niveau provincial/régional pour la période 2000-2023 (superficies, productions, rendements céréaliers).
> Ces données seront utilisées uniquement à des fins académiques, avec anonymisation et citation de la source. Je m'engage à partager les résultats préliminaires avec la DGESS.
> Vous trouverez ci-joint attestation d'inscription et lettre de mon directeur.
> Dans l'attente, cordialement,
> [Nom, Tel, Email]

## Prochaines actions concrètes (cette semaine)

1. Choisis : veux-tu que je lance une revue systématique sur Essai 1 maintenant ?
2. Dis-moi : as-tu déjà accès aux données EPA ou dois-je t'aider à construire un dataset proxy avec FAOSTAT + CHIRPS ?
3. On planifie ensemble ton premier chapitre avec `/ars-plan` ?

Tu peux me dire : "Lance la revue littérature pour Essai 1" ou "Guide-moi pour affiner ma question de recherche Essai 2"
