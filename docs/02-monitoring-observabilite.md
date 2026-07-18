# 2. Monitoring et observabilité

| Fonction | Rôle |
|---|---|
| **Metrics** | Mesurent CPU, mémoire, latence, requêtes et autres indicateurs quantitatifs. |
| **Logs** | Centralisent et analysent les journaux applicatifs et systèmes. |
| **Distributed Tracing** | Suit une requête à travers plusieurs services. |
| **PurePath** | Vue détaillée d’une transaction distribuée dans Dynatrace. |
| **Problems** | Regroupent et corrèlent plusieurs événements liés à un incident. |
| **Events** | Représentent des anomalies ou changements détectés. |
| **Dashboards** | Fournissent des vues personnalisées. |
| **Data Explorer** | Permet l’exploration des métriques et séries temporelles. |
| **Waterfall** | Décompose chronologiquement le chargement ou l’exécution d’une requête. |
| **Custom Funnel** | Analyse les étapes d’un parcours utilisateur, les conversions et abandons. |
| **Apdex** | Mesure la satisfaction utilisateur selon les temps de réponse. |
| **Conversion Rate** | Nombre d’interactions réussies divisé par le nombre total de sessions ou d’opportunités. |
| **Main-thread blocking** | Mesure les tâches JavaScript longues qui bloquent le thread principal, souvent au-delà de 50 ms. |
| **LCP** | Largest Contentful Paint : mesure la performance de chargement perçue. |
| **DOM complete** | Temps jusqu’à l’état `complete` du document. |
| **Trace** | Parcours complet d’une requête distribuée. |
| **Span** | Une opération ou étape individuelle au sein d’une trace. |
| **MTTD** | Mean Time To Detect : temps moyen de détection. |
| **MTTR** | Mean Time To Repair ou Recover : temps moyen de rétablissement. |
| **W3C Trace Context** | Standardise la propagation du contexte de trace entre services et outils. |

## Flapping

Le **flapping** correspond à une alerte qui s’ouvre et se ferme de manière répétée à cause de fluctuations temporaires, de seuils trop sensibles ou d’une absence de fenêtre de stabilisation.

Conséquences :

- bruit opérationnel ;
- fausses alertes répétitives ;
- fatigue des équipes ;
- perte de confiance dans le système d’alerting.

Mesures recommandées :

- augmenter la fenêtre d’évaluation ;
- ajouter une durée minimale avant ouverture ;
- utiliser une hystérésis ;
- préférer les seuils adaptatifs lorsque cela est pertinent ;
- éviter les seuils trop proches de la valeur normale.
