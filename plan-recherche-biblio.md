# Plan de Recherche Bibliographique Systématique

## Vue d'ensemble
**Objectif**: Constituer une base de connaissances exhaustive et actualisée pour fonder scientifiquement le modèle de transition systémique.  
**Cible**: 500+ sources de haute qualité, équilibrées entre disciplines et perspectives  
**Durée**: 2 semaines intensives + veille continue  

---

## 1. REQUÊTES STRUCTURÉES POUR BASES ACADÉMIQUES

### Requête 1: Transitions systémiques et points de bascule
**Bases**: Web of Science, Scopus, Google Scholar
```
("systemic transition" OR "sustainability transition" OR "social-ecological transformation") 
AND ("tipping point" OR "critical threshold" OR "regime shift" OR "cascade*") 
AND ("empirical" OR "case study" OR "evidence")
TIMESPAN: 2020-2025
```
**Résultats attendus**: 200-500 articles
**Filtres prioritaires**: Citations >10, Revues Q1, Meta-analyses

### Requête 2: Modèles économiques alternatifs post-croissance
**Bases**: EconLit, RePEc, SSRN
```
("degrowth" OR "post-growth" OR "steady-state economy" OR "doughnut economics" 
OR "circular economy" OR "wellbeing economy" OR "ecological economics")
AND ("model*" OR "framework" OR "indicator*" OR "metric*")
AND NOT ("green growth" OR "sustainable growth")
TIMESPAN: 2018-2025
```
**Résultats attendus**: 150-300 articles
**Focus**: Modèles quantifiés avec validation empirique

### Requête 3: Gouvernance polycentrique et communs
**Bases**: JSTOR, Political Science Database, Sage
```
("polycentric governance" OR "commons management" OR "collective action" 
OR "institutional diversity" OR "adaptive governance")
AND ("climate" OR "resource*" OR "global" OR "transnational")
AND (Ostrom OR "design principles" OR "social-ecological systems")
TIMESPAN: 2015-2025
```
**Résultats attendus**: 100-200 articles  
**Priorité**: Études multi-échelles et cross-culturelles

### Requête 4: Justice et équité dans les transitions
**Bases**: Social Sciences Citation Index, Sociological Abstracts
```
("just transition" OR "energy justice" OR "climate justice" OR "environmental equity")
AND ("distributional" OR "procedural" OR "recognition" OR "capability")
AND ("Global South" OR "developing" OR "vulnerable" OR "indigenous")
TIMESPAN: 2019-2025
```
**Résultats attendus**: 150-250 articles
**Critère**: Inclusion voix marginalisées

### Requête 5: Technologies de rupture et impacts systémiques
**Bases**: IEEE Xplore, ACM Digital Library, arXiv
```
("artificial intelligence" OR "blockchain" OR "renewable energy" OR "geoengineering"
OR "synthetic biology" OR "quantum computing")
AND ("systemic impact" OR "societal implication*" OR "disruption" OR "transformation")
AND ("risk assessment" OR "scenario" OR "governance" OR "ethic*")
TIMESPAN: 2020-2025
```
**Résultats attendus**: 200-400 articles
**Filtre**: Exclure pure technique, garder socio-technique

---

## 2. SOURCES DE DONNÉES OUVERTES PRIORITAIRES

### Données Climatiques et Environnementales
1. **Climate.gov / NOAA**
   - URL: https://www.climate.gov/climate-data
   - Données: Température, GES, événements extrêmes
   - Fréquence: Temps réel + séries historiques
   - Format: CSV, NetCDF, API REST

2. **Global Carbon Project**
   - URL: https://www.globalcarbonproject.org/
   - Données: Budgets carbone, émissions par pays/secteur
   - Mise à jour: Annuelle
   - Atout: Méthodologie transparente IPCC-compatible

3. **Planetary Boundaries (Stockholm Resilience)**
   - URL: https://www.stockholmresilience.org/planetary-boundaries
   - Données: 9 limites planétaires, état actuel
   - Visualisation: Dashboard interactif
   - Usage: Baseline pour modèles soutenabilité

### Données Socio-économiques
4. **World Inequality Database (WID)**
   - URL: https://wid.world/
   - Données: Inégalités revenus/richesse, 170+ pays
   - Profondeur: 1980-2024, percentiles détaillés
   - API: Disponible pour automatisation

5. **Our World in Data**
   - URL: https://ourworldindata.org/
   - Données: 3000+ indicateurs développement
   - Atouts: Visualisations, code ouvert, citations
   - Biais: Attention au framing "progrès"

6. **UN Stats SDG Database**
   - URL: https://unstats.un.org/sdgs/dataportal
   - Données: 231 indicateurs ODD, tous pays
   - Granularité: National → sous-national (partiel)
   - Limite: Données manquantes pays fragiles

### Données Énergétiques et Ressources
7. **IEA Data & Statistics**
   - URL: https://www.iea.org/data-and-statistics
   - Données: Mix énergétique, efficacité, projections
   - Paywall: Données détaillées payantes (contourner via bibliothèque)
   - Alternative: BP Statistical Review (gratuit mais source fossile)

8. **Global Energy Monitor**
   - URL: https://globalenergymonitor.org/
   - Données: Trackers charbon/gaz/renouvelables, projets pipeline
   - Atout: Géolocalisation infrastructures
   - Usage: Analyser verrouillage carbone

### Données Gouvernance et Conflits
9. **V-Dem (Varieties of Democracy)**
   - URL: https://www.v-dem.net/data/
   - Données: 450+ indicateurs démocratie, 1789-2024
   - Méthodologie: 3500+ experts, inter-codeur fiabilité
   - Usage: Corréler (dé)mocratisation et soutenabilité

10. **ACLED (Armed Conflict Location)**
    - URL: https://acleddata.com/
    - Données: Conflits, protestations, violences géolocalisées
    - Temps réel: Mise à jour hebdomadaire
    - Pertinence: Anticiper zones instabilité climatique

---

## 3. CRITÈRES D'INCLUSION/EXCLUSION

### Critères d'INCLUSION
✅ **Temporalité**: Priorité 2020-2025, accepter 2015+ si fondamental  
✅ **Qualité**: Peer-reviewed OU grey literature d'institutions reconnues  
✅ **Pertinence**: Lien direct/indirect avec transition systémique  
✅ **Diversité**: Minimum 30% auteurs Sud Global / 40% femmes  
✅ **Empirique**: Données/cas concrets privilégiés sur théorie pure  
✅ **Interdisciplinaire**: Bonus si traverse 2+ disciplines  
✅ **Open Access**: Privilégier quand disponible  

### Critères d'EXCLUSION
❌ **Obsolescence**: Données pré-2015 sauf séries historiques  
❌ **Greenwashing**: Sources corporate non-vérifiées  
❌ **Pseudoscience**: Auteurs/revues prédateurs (liste Beall)  
❌ **Mono-solution**: Technologies miracles sans analyse système  
❌ **Biais extrême**: Sources ouvertement climatosceptiques/cornucopiennes  
❌ **Redondance**: Doublons ou reformulations mineures  
❌ **Paywall total**: Si aucun accès via Sci-Hub/bibliothèque  

---

## 4. STRATÉGIE DE RECHERCHE COMPLÉMENTAIRE

### Littérature Grise de Haute Valeur
- **GIEC/IPCC**: AR6 complet + rapports spéciaux
- **IPBES**: Global Assessment + rapports régionaux
- **UNEP**: Gap Reports (émissions, adaptation, finance)
- **Club de Rome**: Earth4All, Limits to Growth updates
- **Fondations**: Rockefeller (résilience), MacArthur (circular economy)
- **Think tanks**: IISD, WRI, Stockholm Environment Institute

### Boule de Neige Inversée
1. Identifier 10 articles séminaux (Rockström, Steffen, Raworth, etc.)
2. Qui les cite? → Forward citation via Google Scholar
3. Explorer articles critiques/contradictoires
4. Cartographier réseaux de citations → clusters thématiques

### Veille Active
- **Alertes Google Scholar**: 20 mots-clés stratégiques
- **Twitter/X Lists**: 50 chercheurs-clés transitions
- **Preprints**: bioRxiv, arXiv, SSRN pour signaux faibles
- **Newsletters**: Carbon Brief, Anthropocene Magazine
- **Podcasts académiques**: Outrage + Optimism, How to Save a Planet

### Sources Non-Conventionnelles
- **Savoirs autochtones**: IPBES ILK, UNESCO LINKS
- **Données citoyennes**: iNaturalist, OpenStreetMap
- **Forums praticiens**: Transition Towns, Permaculture networks
- **Archives historiques**: Effondrement Mayas, Angkor, Rapa Nui

---

## 5. GESTION ET TRAITEMENT

### Architecture de Base de Données
```
/bibliographie/
├── 01_raw/           # PDFs originaux
├── 02_processed/     # Annotations, résumés
├── 03_synthesis/     # Méta-analyses thématiques
├── 04_citations/     # BibTeX + Zotero
└── 05_datavis/       # Graphiques, cartes
```

### Workflow de Traitement
1. **Import**: Mendeley/Zotero avec tags automatiques
2. **Screening**: Titre/abstract → 30 sec décision
3. **Évaluation**: Lecture diagonale → score pertinence (1-5)
4. **Extraction**: Données clés dans matrice standardisée
5. **Synthèse**: Résumé 200 mots + 5 bullet points
6. **Cross-référencement**: Liens avec autres sources

### Outils d'Analyse
- **Bibliométrie**: VOSviewer pour cartographie thématique
- **Text mining**: Python/NLTK pour extraction concepts
- **Méta-analyse**: R/metafor pour synthèse quantitative
- **Visualisation**: Tableau/D3.js pour dashboards

---

## 6. GESTION DES BIAIS ET QUALITÉ

### Matrice de Diversité des Sources
| Critère | Cible | Actuel | Gap |
|---------|-------|--------|-----|
| Géographie: Sud Global | 30% | 0% | -30% |
| Genre: Femmes/Non-binaire | 40% | 0% | -40% |
| Discipline: Sciences sociales | 35% | 0% | -35% |
| Discipline: Sciences naturelles | 35% | 0% | -35% |
| Discipline: Ingénierie/Tech | 30% | 0% | -30% |
| Type: Empirique vs Théorique | 70/30 | 0/0 | - |
| Perspective: Critique vs Mainstream | 30/70 | 0/0 | - |

### Protocole de Fact-Checking
1. **Triangulation**: Minimum 3 sources indépendantes pour fait critique
2. **Trace origine**: Remonter à source primaire, éviter téléphone arabe
3. **Vérifier calculs**: Refaire calculs clés independently
4. **Dates**: Vigilance sur obsolescence rapide données
5. **Conflits intérêts**: Checker financement auteurs/institutions

### Red Team / Devil's Advocate
- Constituer groupe 3-5 experts pour challenger hypothèses
- Organiser "pre-mortem": imaginer échec et causes
- Rechercher activement "Black Swans" négligés
- Tester robustesse avec scénarios extrêmes

---

## 7. PLANNING ET MILESTONES

### Semaine 1: Collecte Intensive
- J1-2: Lancer 5 requêtes, export 1000+ références
- J3-4: Screening titres/abstracts → 300 retenus
- J5-7: Lecture rapide, scoring, catégorisation

### Semaine 2: Analyse et Synthèse  
- J8-9: Extraction données dans matrices
- J10-11: Identification patterns et gaps
- J12-14: Rédaction synthèses thématiques

### Maintenance Continue
- Quotidien: 30 min veille + ajout 2-3 sources
- Hebdo: Update matrices et indicateurs
- Mensuel: Rapport synthèse nouvelles trouvailles
- Trimestriel: Révision complète et élagage

---

## 8. BUDGET ET RESSOURCES

### Accès Payant Nécessaire (si pas institutionnel)
- Sci-Hub: Backup pour articles verrouillés [éthique douteuse mais urgence]
- DeepDyve: $50/mois pour accès lecture
- Unpaywall: Extension pour trouver versions ouvertes
- ResearchGate: Contacter auteurs directement

### Temps Estimé
- Collecte initiale: 40h
- Analyse/synthèse: 60h  
- Maintenance: 5h/semaine ongoing
- **Total Phase 1**: 100h concentrées

### Compétences à Mobiliser
- Recherche avancée: Opérateurs booléens, troncature
- Lecture rapide: 500 mots/minute avec compréhension
- Synthèse: Extraction signal dans bruit
- Visualisation: Transformer données en insights actionnables

---

## MÉTRIQUES DE SUCCÈS

- [ ] 500+ sources pertinentes collectées
- [ ] 100+ sources analysées en profondeur  
- [ ] Couverture 10 disciplines minimum
- [ ] 30%+ sources non-occidentales
- [ ] 5 méta-analyses produites
- [ ] 20 experts contactés pour clarifications
- [ ] 3 découvertes contre-intuitives
- [ ] 10 solutions prometteuses identifiées
- [ ] Niveau confiance conclusions: >70%

---

**→ Prochaine action**: Lancer immédiatement Requête 1 et configurer Zotero avec structure dossiers prédéfinie. Objectif J+1: 100 premières sources triées.