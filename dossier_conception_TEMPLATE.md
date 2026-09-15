# Dossier de conception — <votre cas> (À COMPLÉTER)

**Client :** <nom, rôle> · **Binôme :** <prénoms> · **Cas <A/B/C/D>**

> **Livrable principal — 10 pages au maximum, pas une cible** : un dossier court
> et cohérent vaut mieux qu'un dossier rempli. Lisible par un architecte technique.
> Renommez en `dossier_conception.md`. La conception s'écrit **ici, une seule
> fois** : pas de fichiers intermédiaires à recopier. Le détail des 5
> arbitrages vit dans `arbitrages/` (½ page chacun), le schéma dans
> `schema_archi_finale.md`.

---

## 1. Synthèse (½ page)

<!-- Besoin, solution retenue, 2-3 chiffres clés, ce qu'on a écarté. -->

## 2. Les 5 arbitrages (1 tableau)

| Arbitrage | Choix — ou « non applicable » | Raison clé (1 ligne, chiffrée si possible) |
| --- | --- | --- |
| ML vs DL |  |  |
| SLM vs LLM |  |  |
| RAG oui/non |  |  |
| Agents oui/non |  |  |
| Zero-shot suffit ? |  |  |

## 3. Pile technique et sobriété (1-1,5 page)

| Brique | Famille | Candidat(s) | Pourquoi celui-là |
| --- | --- | --- | --- |
|  |  |  |  |

**Ce qu'on n'a PAS mis (obligatoire)** : <!-- brique écartée + raison -->

**Coûts (ordres de grandeur, sur VOTRE volumétrie)** — `ressources/fiche_chiffrage.md`

## 4. Pipeline de données (1 page)

<!-- Flux de la source à l'exploitation. Puis au minimum :
     - modèle de stockage par type de donnée (relationnel / document / fichier / vectoriel) et pourquoi ;
     - rétention : on garde quoi, combien de temps, on purge quoi (minimisation) ;
     - chaud vs froid.
     Appuis : grille de décision stockage + fiche cycle de vie (dépôt de ressources de la promo). -->

## 5. Évaluation (½-1 page)

<!-- Comment on saura que ça marche AVANT la mise en service :
     baseline simple à battre, découpage des données (temporel si le temps compte),
     métriques alignées sur le KPI métier du cadrage. -->

## 6. Déploiement (½-1 page)

<!-- Où et comment ça tourne, chaîne de livraison (héritage M5), rollback. -->

## 7. Monitoring (½-1 page)

| Question | Métrique | Seuil | Alerte vers |
| --- | --- | --- | --- |
| En vie ? |  |  |  |
| Rapide ? |  |  |  |
| Prédit bien ? |  |  |  |

<!-- Dérive (héritage M6). Ce qu'on ne monitore PAS, et pourquoi. -->

## 8. Pseudo-code du composant critique (½-1 page)

**Quel composant, et pourquoi lui** : <!-- … -->

```text
fonction <nom>(<entrées>):
    # 10-20 lignes lisibles par un non-développeur du binôme :
    # cas nominal, cas limite (donnée manquante, confiance basse…),
    # ce qui est journalisé.
```

## 9. Conformité et sécurité (1 page)

<!-- Qualification AI Act et base légale RGPD reprises du cadrage (raisonnement,
     pas étiquette). Chaque menace de sécurité retenue en B1 → sa réponse
     d'architecture + le risque résiduel. -->

## 10. Schéma final

<!-- Renvoi vers schema_archi_finale.md — chaque brique découle d'un arbitrage. -->

---

## Annexe — Questions jury prévues (5 à 10, hors pagination)

1. _question probable_ → _réponse préparée (2-3 lignes)_
2. _…_
