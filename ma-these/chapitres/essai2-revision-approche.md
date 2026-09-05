# Essai 2 - Révision d'approche suite retour Prof

## Retour du Professeur (à intégrer)
> "Ce n'est pas le comportement qui va dicter la dynamique mais l'inverse, sans oublier la spécificité des ménages agricoles au Burkina Faso qui sont à la fois consommateurs et producteurs"

## Diagnostic : Ce que le Prof critique (probablement)

**Ancienne approche (comportement -> dynamique) :**
Tu partais peut-être de : les choix individuels des ménages (adoption technologie, migration, diversification) expliquent les disparités régionales agrégées.

**Problème :** En économie du développement, c'est une erreur d'agrégation. Ça suppose des marchés parfaits et que les comportements sont exogènes.

**Nouvelle approche demandée (dynamique -> comportement) :**
Ce sont les **dynamiques structurelles régionales** (dotations agro-écologiques, infrastructures, politiques, chocs prix/climat, histoire) qui **contraignent et façonnent** les comportements des ménages. Et ces ménages ne sont pas des firmes classiques.

---

## Fondement théorique à mobiliser : Le modèle du ménage agricole

C'est LA spécificité burkinabè à mettre au cœur de l'Essai 2. Référence fondatrice :

**Singh, Squire & Strauss (1986) - Agricultural Household Models: Extensions, Applications and Policy**

### 1. Le ménage burkinabè n'est PAS une entreprise

- **Double rôle** : Producteur (maximise profit agricole) ET Consommateur (maximise utilité alimentaire, loisir, etc.)
- **Non-séparabilité** : Quand les marchés sont incomplets (travail, crédit, assurance, terre - cas typique Burkina), la décision de production dépend des préférences de consommation, et vice-versa. On ne peut pas séparer.
  - Exemple : Si pas de marché du travail ou crédit, le ménage ne va pas embaucher même si productivité marginale > salaire. Il auto-exploite sa main d'œuvre familiale.
  - Exemple : Il produit du mil pour auto-consommation même si le marché dit que le maïs est plus rentable, parce qu'il y a risque prix + insécurité alimentaire.

### 2. Implications pour les disparités régionales

La dynamique régionale (ex: enclavement, volatilité prix, aléa pluvio) crée des **prix implicites (shadow prices)** différents selon la région, qui dictent le comportement.

**Schéma causal inversé (celui que veut le Prof) :**

```
Dynamiques structurelles régionales
[Pluvio, sols, distance marché, politiques, chocs]
         |
         v
Marchés incomplets / Prix implicites spécifiques à chaque région
         |
         v
Contraintes du ménage producteur-consommateur
[Autoconsommation élevée ~50-70%, aversion risque, contrainte liquidité]
         |
         v
Comportements d'adaptation observables
[Faible intensification, diversification, extensification, migration]
         |
         v
Reproduction / Amplification des disparités régionales (Essai 1)
```

Ce n'est plus : "les paysans du Sahel sont conservateurs donc la région est pauvre"
C'est : "la région du Sahel a des marchés incomplets + risque climatique élevé -> le comportement rationnel du ménage producteur-consommateur est de rester en auto-subsistance -> la disparité se reproduit"

### 3. Cadre théorique enrichi pour Essai 2

Tu peux structurer ta revue littérature autour de 3 blocs :

**Bloc A : Pourquoi l'approche comportement -> dynamique est limitée**
- Critique de l'approche micro sans structure (Fallacy of composition)
- Nouvelle Géographie Économique : la géographie de première nature dicte les comportements (Krugman)

**Bloc B : Modèle ménage agricole producteur-consommateur**
- Chayanov (1925) - organisation de l'exploitation paysanne
- Singh et al. (1986) - modèle de base
- de Janvry, Fafchamps, Sadoulet (1991) - "Peasants are missing markets"
- Applications Burkina : Reardon, Matlon, etc. sur part autoconsommation

**Bloc C : Dynamiques régionales comme déterminants des comportements**
- Risque et incertitude : Rosenzweig & Binswanger (1993) - les ménages pauvres choisissent des cultures moins risquées mais moins rentables
- Enclavement : Fafchamps & Hill (2005) - distance marché et prix à la production
- Trappes à pauvreté spatiales : Jalan & Ravallion (2002), Barrett & Swallow (2006)

## Nouvelle architecture proposée pour Essai 2

**Titre révisé** : *Dynamiques régionales et logiques paysannes : Comment les disparités structurelles façonnent les comportements des ménages agricoles producteurs-consommateurs au Burkina Faso*

**RQ principale révisée** : Comment les dynamiques régionales de disparités (dotations, accès marchés, chocs) façonnent-elles les stratégies de production et de consommation des ménages agricoles, et en quoi cette double casquette explique-t-elle la persistance des écarts ?

**Sous-questions :**
1. Quelle est la part d'autoconsommation vs commercialisation selon les régions ? (Fait stylisé puissant)
2. Comment les contraintes régionales (distance, pluvio, prix) affectent-elles les décisions d'assolement, d'intensification, de diversification ?
3. La non-séparabilité est-elle plus forte dans les régions les plus enclavées / vulnérables ? (Test empirique)

**Méthodologie révisée (plus micro-économique, cohérente avec prof) :**

Au lieu de SDM macro régional seul, combiner :

1.  **Analyse descriptive régionale** : Part autoconsommation par région à partir de EHCVM 2018/2021 ou EPA. Montre la spécificité.
2.  **Modèle de ménage agricole empirique** :
    - Estimation d'une fonction de production + demande de consommation jointe
    - Ou plus simple : modèle de part commercialisée (marketed surplus) en fonction de variables régionales + caractéristiques ménage
    - Equation type : `Part_commercialisée_ih_r = α + β1 Distance_marché_r + β2 Risque_pluvio_r + β3 Actifs_h + γ Région_r + ε`
    - Test de séparabilité : est-ce que caractéristiques ménage (taille, éducation) affectent décisions production ? Si oui -> non-séparabilité -> marchés incomplets.
3.  **Hétérogénéité régionale** : Estimer séparément par zone (Nord Sahel vs Sud-Ouest) pour montrer que le même choc a des effets différents selon contexte régional.

**Données** : EHCVM (a modules agriculture + consommation, parfait pour ça) + EPA + CHIRPS + distances.

## Ce que tu dois montrer au Prof pour valider la nouvelle approche

1.  Schéma causal inversé (ci-dessus)
2.  Référence Singh et al. 1986 + de Janvry et al. 1991
3.  Statistique descriptive : part autoconsommation moyenne Burkina ~ 60% ? à calculer par région
4.  Nouvelle RQ qui part du territoire vers le ménage, pas l'inverse

---

## En attente de ton draft

Colle ici ce que tu as déjà écrit pour Essai 2 (même brouillon), je vais :
1. Le relire à la lumière de ce retour prof
2. Identifier exactement où l'ancienne logique comportement->dynamique apparaît
3. Te proposer des reformulations concrètes paragraphe par paragraphe
