# 3. Modes de déploiement

## Vue synthétique

| Mode de déploiement | Ce qui est monitoré | Niveau de visibilité | Cas d’usage principal |
|---|---|---|---|
| **Full-Stack Monitoring** | Infrastructure, applications, services, processus, traces, réseau et éventuellement logs | Complète | Observabilité complète de production |
| **Infrastructure Monitoring** | CPU, RAM, disque, réseau, hôtes et processus | Infrastructure principalement | Monitoring infrastructure et optimisation des coûts |
| **Application-Only Monitoring** | Services, transactions, traces et visibilité code | Applicative | Équipes de développement et APM ciblé |
| **Discovery Mode** | Hôtes, processus et technologies détectées | Découverte et inventaire | Audit, cadrage ou migration |
| **Cloud Native Full-Stack** | Kubernetes, pods, conteneurs, namespaces, services, traces et logs selon configuration | Complète et orientée cloud-native | Kubernetes et microservices |

## Comparaison rapide

| Mode | Logs | Traces | Infrastructure | Kubernetes | Code-level |
|---|---:|---:|---:|---:|---:|
| **Full-Stack** | ✅ selon configuration | ✅ | ✅ | ✅ | ✅ |
| **Infrastructure** | ❌ par défaut | ❌ | ✅ | Partiel | ❌ |
| **Application-Only** | Partiel | ✅ | ❌ | Partiel | ✅ |
| **Discovery** | ❌ | ❌ | Partiel | Partiel | ❌ |
| **Cloud Native Full-Stack** | ✅ selon configuration | ✅ | ✅ | ✅✅ | ✅ |

## Point de vigilance

La collecte des logs n’est pas automatiquement garantie par le seul choix du mode Full-Stack. Elle dépend également :

- de l’activation de la surveillance des logs ;
- des règles d’inclusion et d’exclusion ;
- des droits d’accès aux fichiers ;
- de la configuration de l’environnement ;
- des règles de stockage et de routage.
