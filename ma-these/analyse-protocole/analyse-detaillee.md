# Analyse détaillée du Protocole de Thèse - MOGMENGA

**Date d'analyse** : 2026-09-05
**Analyste** : Assistant academic-research-skills
**Document source** : Projet de recherche thèse doctorat - 4 essais

---

## 1. Points forts du protocole actuel (à conserver)

**Très solide :**

1.  **Problématique bien ancrée** : Tu pars du paradoxe agrégé (60% emploi, 25% PIB en SSA mais disparités masquées) vers le cas Burkina (35% PIB, 82% emploi, 2024). C'est le funnel classique et efficace.
2.  **Définition conceptuelle claire** : Tu définis disparité régionale de développement agricole avec 6 dimensions (intensité culturale, diversification, irrigation, productivité, efficacité, poids agriculture) en citant Li et al. 2022. Très bien, c'est opérationnalisable en indice composite.
3.  **Justification terrain Burkina** : Double justification (dépendance + hétérogénéité climatique Sud-Ouest vs Sahel) + chiffres récents percutants (77% Centre-Nord vs 20,7% Hauts-Bassins ne couvrant pas besoins céréaliers, 20 provinces sur 45 en baisse 2023-2024). C'est fort pour le jury.
4.  **Architecture en 4 essais** : Logique et progressive :
    - Essai 1 = Mesure (le quoi)
    - Essai 2 = Comportements (le qui, micro)
    - Essai 3 = Chocs (le contexte exogène)
    - Essai 4 = Interaction (le comment ça se combine)
5.  **Fondements théoriques opposés** : Pour chaque essai tu opposes 2 théories (néoclassique vs NGE, EU vs Prospect Theory, etc.). C'est exactement ce qu'attend un jury d'économie : montrer que tu testes entre deux lectures.
6.  **Données identifiées** : EPA 2016-2025 + ACLED pour chocs sécuritaires. Cohérent.

**Tu as déjà un protocole au-dessus de la moyenne des doctorants de 1ère année.**

---

## 2. Points à renforcer - Diagnostic général

### A. Le cœur du retour du Pr OUEDRAOGO (Essai 2 et 4)

Ton prof a raison et c'est le point le plus important à corriger. Actuellement dans ton protocole :

**Logique actuelle (p.3-4) :**
> "Ces comportements, rationnels à l'échelle du ménage, peuvent produire un effet cumulatif à l'échelle régionale. Dans les régions les plus exposées à l'incertitude, l'adoption serait ralentie, ce qui freinerait le rattrapage... Ces mécanismes comportementaux constituent dès lors une piste explicative plausible de la persistance des disparités"

**Problème** : Tu expliques la persistance des disparités **par** les comportements. C'est l'approche "bottom-up" : ménages -> région.

**Ce que veut le prof (top-down + spécificité BF) :**
> Les disparités structurelles régionales (dotations, enclavement, marchés incomplets) **contraignent** les ménages qui sont à la fois producteurs et consommateurs, ce qui **oriente** leurs comportements, qui à leur tour **reproduisent** les disparités.

**Et surtout** : Tu oublies que le ménage burkinabè n'est pas une firme. Dans ton Essai 2, tu mobilises EU vs Prospect Theory, mais ces deux théories supposent un producteur qui maximise profit. Or le ménage BF maximise **utilité de consommation sous contrainte de production**, avec forte auto-consommation. C'est le modèle du ménage agricole.

**Conséquence** : Il faut **inverser la flèche causale** et **ajouter le modèle ménage agricole** au cœur de l'Essai 2 et 4.

### B. Autres points à renforcer

1.  **Période 2016-2025 trop courte pour Essai 1** : 10 ans, 13 régions = 130 observations pour une chaîne de Markov Quah. C'est faible pour tester convergence. Il faut discuter cette limite et proposer extension (2006-2025 si EPA disponible, ou passage à 45 provinces = 450 obs).
2.  **Indice composite : comment ?** Tu cites ACP et taxonomie mais tu ne dis pas quelles variables exactement parmi tes 6 dimensions. Il faut lister les indicateurs EPA précis.
3.  **Essai 2 méthodologie Bar-Shira 1997** : Ce modèle mesure aversion au risque via allocation cultures, mais il ne capture pas la dimension consommation. Il faut le compléter par Barnum-Squire ou Singh et al.
4.  **Essai 3 et 4 : endogénéité** : Si les comportements sont une réponse aux chocs, alors dans Essai 4 tu ne peux pas traiter comportement comme modérateur exogène. Il faut discuter endogénéité et proposer IV ou modèle structurel.
5.  **Questions de recherche redondantes** : QR1 "Quelle est la dynamique..." = objectif général. Il faut affiner.
6.  **Références futures** : Gebretsadik & Uaiene 2026, INSD 2025 -> vérifie dates, jury va relever.

---

## 3. Analyse essai par essai

### Essai 1 : Dynamique des disparités - BON, mais à préciser

**Forces** : Quah Markov est original pour Burkina, peu utilisé. Bonne opposition néoclassique vs NGE.

**À renforcer :**
- **Construction indice** : Détaille. Exemple :
  - Intensité culturale = superficie cultivée / superficie cultivable (EPA)
  - Diversification = 1 - Herfindahl cultures
  - Irrigation = % superficie irriguée
  - Productivité = rendement céréalier kg/ha
  - Efficacité = valeur prod / coût intrants (si dispo)
  - Poids agriculture = VA agricole / VA totale régionale (INSD comptes régionaux)
  - Ensuite ACP, garder 1er axe si >60% variance, ou moyenne pondérée.

- **Classes pour Markov** : Comment définis-tu les classes c_k ? Quartiles ? Seuil Banque Mondiale ? Il faut le dire. Propose 4 classes : faible, moyen-faible, moyen-élevé, élevé.

- **Période** : Négocie avec DGESS pour avoir EPA depuis 2006 ou 2009. 2016-2025 c'est court et biaisé par crise sécuritaire. Si impossible, passe en provinces (45) pour gagner puissance.

- **Hypothèse H1** : "ne conduit pas à convergence" -> trop binaire. Reformule : "conduit à une persistance / divergence ou à des clubs de convergence" (plus testable avec Markov).

### Essai 2 : Effet des comportements - À REVOIR EN PROFONDEUR (priorité prof)

**Problème actuel :** Tu testes aversion au risque et biais comportementaux (EU vs Prospect Theory) comme déterminants des disparités. C'est intéressant mais :
1.  Ça met comportement comme cause première
2.  Ça ignore dimension consommation
3.  Modèle Bar-Shira mesure aversion via allocation, mais sans lien explicite avec disparité régionale

**Proposition de refonte (validée par prof) :**

**Nouveau titre** : *Dynamiques régionales et logiques paysannes : Comment les contraintes territoriales façonnent les comportements des ménages producteurs-consommateurs*

**Nouveau cadre théorique (remplace/complète EU vs Prospect) :**
Garde EU vs Prospect comme sous-partie, mais ajoute comme cœur :

1.  **Modèle ménage agricole de Singh, Squire & Strauss (1986)** : Le ménage maximise U(c, l) sous contrainte production Q = f(L, K) et contrainte budgétaire p_c c = p_q (Q - c_auto) + revenu off-farm. Si marchés parfaits, séparabilité. Si marchés incomplets (cas BF), non-séparabilité : caractéristiques ménage affectent production.

2.  **Marchés manquants au Burkina** : de Janvry, Fafchamps & Sadoulet (1991) "Peasant household behavior with missing markets". Au Burkina : marché crédit, assurance, travail, foncier incomplets. Conséquence : prix implicites (shadow prices) différents selon région.

3.  **Risque et apprentissage** : Garde Foster & Rosenzweig, Dercon, Duflo mais comme mécanismes d'ajustement face à contraintes régionales, pas comme cause première.

**Nouvelle chaîne causale :**
Contraintes régionales (distance, pluvio, insécurité) -> Marchés incomplets / prix implicites élevés -> Contrainte ménage producteur-consommateur (forte autoconsommation, aversion risque contrainte) -> Comportements observables (faible intensification, diversification défensive) -> Reproduction disparités

**Nouvelle méthodologie :**

Au lieu de Bar-Shira seul, propose 2 étapes :

**Étape A (descriptive, puissante)** : Calcule part autoconsommation par région à partir de EHCVM 2018/2021. Montre : Centre-Nord 70% autoconsommation vs Hauts-Bassins 30%. C'est la preuve de non-séparabilité différenciée.

**Étape B (test séparabilité)** : Modèle de Benjamin (1992) ou Jacoby (1993) :
- Régression : Demande de travail agricole familiale = f(surface, actifs, caractéristiques ménage, variables régionales)
- Si caractéristiques ménage (taille, éducation) significatives -> rejet séparabilité -> marchés incomplets.
- Estime séparément par zone agro-climatique pour montrer hétérogénéité régionale.

**Étape C (comportement)** : Ensuite seulement, modèle allocation cultures sous aversion au risque (Bar-Shira) mais avec variables régionales comme déterminants de alpha et beta.

**Nouvelles QR Essai 2 :**
- QR2.1 : Dans quelle mesure les ménages agricoles burkinabè sont-ils non-séparables et cette non-séparabilité varie-t-elle selon les régions ?
- QR2.2 : Comment les contraintes régionales (enclavement, risque) façonnent-elles l'aversion au risque et les choix d'assolement des ménages producteurs-consommateurs ?
- QR2.3 : En quoi ces comportements contraints contribuent-ils à la persistance des disparités régionales ?

### Essai 3 : Chocs - BON, mais clarifier covariant vs idiosyncrasique

**Forces** : Distinction chocs climatiques et sécuritaires, modèles Adelaja & George pertinent, données ACLED.

**À renforcer :**
- Tu mentionnes 20-70% terres cultivées perdues, -56% engrais (FAO 2022) -> très bien, garde.
- Théorie Myrdal causalité cumulative vs néoclassique -> bien.
- Mais tu dois introduire dès Essai 3 la distinction idiosyncrasique vs covariant que tu utilises en Essai 4. Un choc sécuritaire est covariant (toute la région touchée), un choc climatique peut être idiosyncrasique (une parcelle) ou covariant (sécheresse régionale).
- Méthodo : Q_i = (1-h_i) f(K,L) est simple mais h_i comment mesuré ? Intensité ACLED = nombre événements / 1000 hab ? Ou dummy ? Précise.
- Période 2016-2025 ok pour chocs sécuritaires (début 2016).

### Essai 4 : Modération - LE PLUS COMPLEXE, à bien cadrer

**Forces** : Question originale, modèle Zimmerman & Carter dynamique actifs bien choisi, distinction chocs.

**Problème majeur : Endogénéité**
Si Essai 2 montre que comportements sont déterminés par dynamiques régionales et chocs, alors dans Essai 4 tu ne peux pas mettre comportement comme modérateur exogène. C'est endogène.

**Solution :**
- Explique que tu testes un modèle à équations simultanées ou avec interaction instrumentée.
- Ou reformule : Ce ne sont pas les comportements qui modèrent les chocs, mais la **capacité de résilience** (actifs, diversification) qui est le résultat de comportements passés contraints par dynamiques régionales.
- Modèle Zimmerman & Carter : F(T,M,theta_idio, theta_covar) -> bien, mais explique T = actif productif (terre, bétail), M = actif tampon (stock céréalier). Au Burkina, M est crucial pour ménage producteur-consommateur.

**QR à reformuler :**
Actuelle : "Dans quelle mesure les comportements modulent-ils l'impact des chocs sur la dynamique..."
Nouvelle : "Dans quelle mesure la capacité de résilience des ménages producteurs-consommateurs, façonnée par les dynamiques régionales, atténue-t-elle l'impact des chocs covariants vs idiosyncrasiques sur les disparités ?"

---

## 4. Proposition de reformulation des éléments transversaux

### Problématique générale révisée (intègre retour prof)

Garde début, mais modifie fin p.4-5 :

**Version actuelle (comportement -> disparité) :**
> "Ces comportements, rationnels à l'échelle du ménage, peuvent produire un effet cumulatif à l'échelle régionale... Ces mécanismes comportementaux constituent dès lors une piste explicative plausible de la persistance des disparités"

**Version proposée (dynamique -> comportement -> disparité + spécificité) :**

> "Ces potentiels agricoles régionaux ne se traduisent pas mécaniquement en écarts de production. Cette transmission est médiatisée par la nature même des ménages agricoles burkinabè, à la fois producteurs et consommateurs (Singh et al., 1986). Dans un contexte de marchés incomplets (crédit, assurance, travail), caractéristique des zones rurales burkinabè (de Janvry et al., 1991), les décisions de production ne peuvent être séparées des impératifs de consommation et de sécurisation alimentaire. Dès lors, ce ne sont pas tant les comportements qui dictent la dynamique des disparités, mais l'inverse : ce sont les dynamiques structurelles régionales – hétérogénéité agro-climatique, enclavement, chocs covariants sécuritaires – qui, en façonnant des prix implicites et des contraintes spécifiques à chaque région, orientent les stratégies des ménages producteurs-consommateurs. Dans les régions les plus exposées à l'incertitude et à l'enclavement, le comportement rationnel consiste à privilégier l'autoconsommation, la diversification défensive et la faible intensification, au détriment de l'adoption d'innovations productives pourtant rentables en espérance (Dercon & Christiaensen, 2011; Foster & Rosenzweig, 1995). Ces stratégies d'adaptation, bien que rationnelles à l'échelle du ménage, produisent un effet cumulatif à l'échelle régionale en freinant le rattrapage des régions les plus vulnérables. C'est cette interaction entre contraintes territoriales et logiques paysannes producteur-consommateur qui constitue la piste explicative centrale de la persistance des disparités régionales de développement agricole au Burkina Faso."

### Questions de recherche révisées

**Générale** : Comment les dynamiques structurelles régionales façonnent-elles les comportements des ménages agricoles producteurs-consommateurs et, à travers eux, la persistance des disparités régionales de développement agricole au Burkina Faso ?

**Spécifiques :**
1.  Quelle est la dynamique (convergence/divergence/clubs) des disparités régionales de développement agricole au Burkina Faso mesurée par indice composite ?
2.  Dans quelle mesure les ménages agricoles burkinabè sont-ils caractérisés par la non-séparabilité production-consommation et comment les contraintes régionales façonnent-elles leurs comportements face au risque ?
3.  Quel est l'effet des chocs covariants (sécuritaires, climatiques) vs idiosyncrasiques sur la dynamique des disparités régionales ?
4.  Dans quelle mesure la capacité de résilience des ménages producteurs-consommateurs, elle-même façonnée par les dynamiques régionales, module-t-elle l'impact des chocs sur les disparités ?

### Objectifs et hypothèses révisés

**Objectif général** : Analyser comment les dynamiques structurelles régionales, à travers les contraintes qu'elles imposent aux ménages agricoles producteurs-consommateurs, façonnent la persistance des disparités régionales de développement agricole au Burkina Faso.

**H1 (Essai1)** : La dynamique des disparités ne conduit pas à une convergence unique mais à une persistance avec formation de clubs de convergence (hypothèse plus fine et testable avec Markov).

**H2 (Essai2) - Réécrite** : Les ménages agricoles burkinabè sont caractérisés par une non-séparabilité production-consommation d'autant plus forte que les contraintes régionales (enclavement, risque) sont élevées, ce qui oriente leurs comportements vers des stratégies défensives contribuant à la persistance des disparités.

**H3 (Essai3)** : Les chocs covariants (sécuritaires et climatiques régionaux) accentuent la divergence régionale, tandis que les chocs idiosyncrasiques ont un effet plus limité grâce aux mécanismes de solidarité locale.

**H4 (Essai4)** : La capacité de résilience (actifs tampons, diversification) des ménages producteurs-consommateurs atténue l'impact des chocs idiosyncrasiques mais s'avère insuffisante face aux chocs covariants qui affectent l'ensemble de la communauté.

---

## 5. Bibliographie complémentaire à ajouter (cœur pour prof)

**Pour spécificité producteur-consommateur (à ajouter absolument) :**
- Singh, I., Squire, L., & Strauss, J. (1986). Agricultural Household Models: Extensions, Applications and Policy. Johns Hopkins.
- Barnum, H. & Squire, L. (1979). An econometric application of the theory of the farm household. Journal of Development Economics.
- de Janvry, A., Fafchamps, M., & Sadoulet, E. (1991). Peasant household behavior with missing markets. Journal of Development Economics.
- Benjamin, D. (1992). Household composition, labor markets, and labor demand: testing for separation in agricultural household models. Econometrica.
- Reardon, T. et al. sur part autoconsommation en Afrique

**Pour inversion causalité dynamique -> comportement :**
- Barrett, C. B., & Swallow, B. M. (2006). Fractal poverty traps. World Development.
- Jalan, J., & Ravallion, M. (2002). Geographic poverty traps. Journal of Comparative Economics.
- Krugman (1991) déjà cité, mais insiste sur première nature vs seconde nature

**Pour Burkina spécifique producteur-consommateur :**
- Matlon, P. (1988) - Burkina Faso farm household studies (ICRISAT)
- Reardon, T., Matlon, P., & Delgado, C. (1988). Coping with household-level food insecurity in drought-affected areas of Burkina Faso.

---

## 6. Plan d'action immédiat

**Semaine 1 :**
- [ ] Valider avec Pr OUEDRAOGO la nouvelle formulation problématique inversée + H2 réécrite
- [ ] Ajouter 5 références cœur (Singh, de Janvry, Benjamin) dans biblio
- [ ] Réécrire QR et objectifs selon proposition ci-dessus

**Semaine 2 :**
- [ ] Détailler construction indice composite Essai 1 (liste variables EPA exactes)
- [ ] Lancer demande EPA depuis 2006 (pas seulement 2016) + EHCVM 2018/2021 pour part autoconsommation
- [ ] Commencer calcul part autoconsommation par région (EHCVM)

**Semaine 3 :**
- [ ] Rédiger schéma conceptuel global (je peux t'aider à le dessiner)
- [ ] Rédiger Essai 2 nouvelle version avec test séparabilité

Veux-tu que je te rédige maintenant la version révisée complète de ton protocole (3-4 pages) prête à envoyer au Pr OUEDRAOGO ?
