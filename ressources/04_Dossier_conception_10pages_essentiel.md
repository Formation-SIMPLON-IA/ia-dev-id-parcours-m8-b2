# Dossier de conception en 10 pages — Mini-cours

> Brief associé : M8-B2
> Durée de lecture : ~20 min
> Pré-requis : convergence binôme + 5 arbitrages (½ page chacun)

## Pourquoi cette techno ?

Le dossier de conception est le **livrable technique** qui synthétise les
arbitrages et la conception pour un **architecte** (pas un décideur métier comme le
cadrage). Il doit être assez complet pour qu'un autre puisse **reprendre le
projet**, et assez structuré pour rester lisible en 10 pages. Il **réutilise**
l'acquis du parcours (déploiement M5, monitoring M6, audit M7).

## Concepts clés

- **Public = architecte** : on peut être technique, mais structuré et justifié.
- **Un seul livrable de conception** : pile, pipeline, évaluation, déploiement,
  monitoring, pseudo-code et conformité s'écrivent **directement** dans le
  dossier (sections 3-9) — pas de fichiers intermédiaires à recopier. Questions
  jury en annexe.
- **Références aux modules** : « CI/CD comme en M5 », « monitoring drift comme en
  M6 » — capitalisation explicite.
- **Sobriété visible** : une section « ce qu'on n'a PAS mis » (vector DB, Registry,
  agents) avec la justification.
- **Cohérence** : chaque choix d'archi découle d'un arbitrage (traçabilité).
- **10 pages = un plafond, pas une cible** : synthétiser, ne pas tout détailler —
  le pseudo-code couvre le critique, pas tout le code. Un dossier de 6 pages
  cohérent vaut mieux que 10 pages remplies pour remplir.

## Exemple minimal qui tourne

```markdown
## 3. Pile technique
- Python 3.11, scikit-learn (classification), FastAPI (service), Docker + CI/CD (M5).
## Ce qu'on n'a PAS mis (sobriété)
- Pas de vector DB (RAG non), pas de MLflow Registry (1 modèle simple).
```

## Exercice guidé

À partir de tes arbitrages :
1. Rédige la section **pile technique** (familles + versions, références modules).
2. Ajoute une section **« ce qu'on n'a PAS mis »** + justification.
3. Vérifie que chaque brique d'archi découle d'un arbitrage.

## Pièges fréquents

| Piège | Conséquence |
|---|---|
| Dossier de 25 pages | Illisible, on noie l'essentiel |
| Tout détailler (full code) | C'est de la conception, pas un POC |
| Pas de référence aux modules | On réinvente, on ne capitalise pas |
| Sobriété invisible | Critère manqué |
| Archi incohérente avec arbitrages | Perte de traçabilité |

| Symptôme | Cause probable |
|---|---|
| L'architecte ne peut pas reprendre | dossier trop vague ou incohérent |
| Briques inexpliquées | pas de lien arbitrage → archi |
| Dossier trop long | manque de synthèse |

## Pour aller plus loin

- Cf. déploiement M5, monitoring M6, audit M7 — à référencer.
- MLOps principles : https://ml-ops.org/content/mlops-principles

## Vérification (checklist apprenant)

- [ ] 10 pages **au maximum** (pas une cible), structuré.
- [ ] Lisible par un architecte (technique mais clair).
- [ ] Références aux modules antérieurs (M5/M6/M7).
- [ ] Section « ce qu'on n'a PAS mis » (sobriété).
- [ ] Chaque brique d'archi découle d'un arbitrage.

> 💡 **Récap — Dossier de conception** : public = **architecte** ; **10 pages au maximum** (plafond, pas cible) ; **référencer les modules** (CI/CD M5, monitoring M6) ; section « ce qu'on n'a PAS mis » (sobriété) ; chaque brique d'archi découle d'un arbitrage (traçabilité). Assez complet pour qu'un autre reprenne.

### À retenir

- Le livrable se juge sur sa **clarté pour le destinataire**, pas sur sa longueur.
- **Chiffrer** plutôt qu'affirmer : un nombre vaut mieux qu'un adjectif.
- **Sobriété** : recommander le plus simple qui résout le besoin, et **dire ce qu'on écarte**.
- Distinguer ce qu'on **sait** de ce qui reste **à clarifier** (questions ouvertes).
- Tracer ses **choix** et leur **raison** — c'est ce qui se défend en restitution.
