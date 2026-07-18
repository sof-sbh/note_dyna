# 8. Questions et pièges fréquents

## Questions ultra fréquentes

| Question | Réponse |
|---|---|
| Qui collecte les données ? | **OneAgent** |
| Qui aide à identifier la cause racine ? | **Davis AI** |
| Qui crée et corrèle les Problems ? | **Dynatrace Intelligence / Davis AI** |
| Qui cartographie les dépendances ? | **Smartscape** |
| Qui sert de proxy ou gateway ? | **ActiveGate** |
| Qui déploie Dynatrace dans Kubernetes ? | **Dynatrace Operator** |

## Différences importantes

| Concept | Différence |
|---|---|
| **Event vs Problem** | Un Problem peut regrouper plusieurs Events corrélés. |
| **Smartscape vs Dashboard** | Smartscape montre la topologie dynamique ; un dashboard présente des indicateurs choisis. |
| **OneAgent vs ActiveGate** | OneAgent collecte ; ActiveGate route et prend en charge certaines intégrations. |
| **Synthetic vs RUM** | Synthetic simule ; RUM observe les vrais utilisateurs. |
| **SLI vs SLO** | SLI = mesure ; SLO = objectif. |

## Pièges fréquents

| Piège | Bonne réponse |
|---|---|
| Davis AI collecte les métriques | ❌ Faux |
| ActiveGate remplace OneAgent | ❌ Faux |
| Smartscape est un dashboard | ❌ Faux |
| Problem = un seul Event | ❌ Faux |
| Synthetic = vrais utilisateurs | ❌ Faux |
