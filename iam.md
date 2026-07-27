| Groupe IAM | Groupe métier | Périmètre / MZ | Scopes | Boundary | Niveau | Statut |
|---|---|---|---|---|---|---|
| `GRP-SRE-VoyagesSejours` | SRE | MZ-VOYAGES-SEJOURS | RW: logs, metrics, traces, dashboards, alerting, settings / X-R: users, security | `BND-VoyagesSejours-All` | Environment | À valider |
| `GRP-Developer-VoyagesSejours` | Developer | MZ-VOYAGES-SEJOURS (non-prod) | RW: logs, metrics, traces (non-prod) / R: dashboards / X: alerting, settings, security | `BND-VoyagesSejours-NonProd` | Environment | À faire |
| `GRP-SRE-AchatsFinance` | SRE | MZ-ACHATS-FINANCE | RW: logs, metrics, traces, dashboards, alerting, settings / X-R: users, security | `BND-AchatsFinance-All` | Environment | À faire |
| `GRP-Developer-AchatsFinance` | Developer | MZ-ACHATS-FINANCE (non-prod) | RW: logs, metrics, traces (non-prod) / R: dashboards / X: alerting, settings, security | `BND-AchatsFinance-NonProd` | Environment | À faire |
| `GRP-SRE-SI` | SRE | MZ-SI | RW: logs, metrics, traces, dashboards, alerting, settings / X-R: users, security | `BND-SI-All` | Environment | À faire |
| `GRP-Developer-SI` | Developer | MZ-SI (non-prod) | RW: logs, metrics, traces (non-prod) / R: dashboards / X: alerting, settings, security | `BND-SI-NonProd` | Environment | À faire |
| `GRP-SRE-Culture` | SRE | MZ-OFFRE-CULTURE | RW: logs, metrics, traces, dashboards, alerting, settings / X-R: users, security | `BND-Culture-All` | Environment | À faire |
| `GRP-Developer-Culture` | Developer | MZ-OFFRE-CULTURE (non-prod) | RW: logs, metrics, traces (non-prod) / R: dashboards / X: alerting, settings, security | `BND-Culture-NonProd` | Environment | À faire |
| `GRP-SRE-Communication` | SRE | MZ-COMMUNICATION | RW: logs, metrics, traces, dashboards, alerting, settings / X-R: users, security | `BND-Communication-All` | Environment | À faire |
| `GRP-Developer-Communication` | Developer | MZ-COMMUNICATION (non-prod) | RW: logs, metrics, traces (non-prod) / R: dashboards / X: alerting, settings, security | `BND-Communication-NonProd` | Environment | À faire |
| `GRP-SRE-Assurance` | SRE | MZ-OFFRE-ASSURANCE | RW: logs, metrics, traces, dashboards, alerting, settings / X-R: users, security | `BND-Assurance-All` | Environment | À faire |
| `GRP-Developer-Assurance` | Developer | MZ-OFFRE-ASSURANCE (non-prod) | RW: logs, metrics, traces (non-prod) / R: dashboards / X: alerting, settings, security | `BND-Assurance-NonProd` | Environment | À faire |
| `GRP-SRE-PromotionConseil` | SRE | MZ-PROMOTION-CONSEIL | RW: logs, metrics, traces, dashboards, alerting, settings / X-R: users, security | `BND-PromotionConseil-All` | Environment | À faire |
| `GRP-Developer-PromotionConseil` | Developer | MZ-PROMOTION-CONSEIL (non-prod) | RW: logs, metrics, traces (non-prod) / R: dashboards / X: alerting, settings, security | `BND-PromotionConseil-NonProd` | Environment | À faire |
| `GRP-SRE-Restauration` | SRE | MZ-OFFRE-RESTAURATION | RW: logs, metrics, traces, dashboards, alerting, settings / X-R: users, security | `BND-Restauration-All` | Environment | À faire |
| `GRP-Developer-Restauration` | Developer | MZ-OFFRE-RESTAURATION (non-prod) | RW: logs, metrics, traces (non-prod) / R: dashboards / X: alerting, settings, security | `BND-Restauration-NonProd` | Environment | À faire |
| `GRP-SRE-SiETFlux` | SRE | MZ-SIET-FLUX | RW: logs, metrics, traces, dashboards, alerting, settings / X-R: users, security | `BND-SiETFlux-All` | Environment | À faire |
| `GRP-Developer-SiETFlux` | Developer | MZ-SIET-FLUX (non-prod) | RW: logs, metrics, traces (non-prod) / R: dashboards / X: alerting, settings, security | `BND-SiETFlux-NonProd` | Environment | À faire |
| `GRP-SRE-Sante` | SRE | MZ-OFFRE-SANTE | RW: logs, metrics, traces, dashboards, alerting, settings / X-R: users, security | `BND-Sante-All` | Environment | À faire |
| `GRP-Developer-Sante` | Developer | MZ-OFFRE-SANTE (non-prod) | RW: logs, metrics, traces (non-prod) / R: dashboards / X: alerting, settings, security | `BND-Sante-NonProd` | Environment | À faire |
| `GRP-MCO-Global` | MCO | Tous périmètres | R: logs, metrics, traces, dashboards / RW ciblé: alerting / X: settings, security avancés | `BND-Global-Portfolio` | Environment | À faire |
| `GRP-Manager-Global` | Manager | Tous périmètres | R: dashboards, alerting / X: reste | `BND-Global-Portfolio` | Environment | À faire |
| `GRP-Auditor-Global` | Auditor | Tous périmètres | R: logs, metrics, traces, dashboards / R: security, API tokens / X: écriture partout | `BND-Global-Portfolio` | Account | À faire |
