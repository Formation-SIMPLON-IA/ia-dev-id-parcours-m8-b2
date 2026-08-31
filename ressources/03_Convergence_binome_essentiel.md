# Converger en binôme (2 visions techniques) — Mini-cours

> Brief associé : M8-B2
> Durée de lecture : ~15 min
> Pré-requis : 2 cadrages M8-B1 (le tien + celui du coéquipier)

## Pourquoi cette techno ?

Vous avez tiré le **même cas** en M8-B1, mais cadré **différemment**. En M8-B2, vous
devez produire **une seule** conception. Converger n'est pas fusionner (coller les
2 textes) ni s'aligner par fatigue : c'est **négocier** chaque divergence et
**trancher** avec une raison. C'est une compétence pro réelle (CT9) — défendre,
écouter, décider.

## Concepts clés

- **Convergence ≠ union** : on ne juxtapose pas les 2 cadrages, on choisit.
- **Lister les divergences** : 3-5 points majeurs à trancher en priorité (modèle,
  seuil, stockage…).
- **Pour chaque divergence** : position A / position B / **décision retenue + raison**.
- **Pas de compromis mou** : « on met les deux » est rarement la bonne réponse —
  trancher avec un argument est mieux qu'un entre-deux flou.
- **Tracer** : `decisions_binome.md` documente le processus (pas juste le résultat) —
  c'est la preuve de la négociation.
- **Désaccord sain** : challenger l'autre (« et si on faisait plus simple ? »)
  améliore la conception.

## Exemple minimal qui tourne

```markdown
| Divergence | Position A | Position B | Décision |
|---|---|---|---|
| Seuil de revue | 0.5 | 0.7 | 0.6 (compromis argumenté : charge vs qualité) |
| PII | suppression | pseudonymisation | pseudonymisation (garde le signal) |
```

## Exercice guidé

Avec ton binôme :
1. Listez les 3-5 points où vos cadrages divergent.
2. Pour chacun : argumentez, puis **tranchez** (pas « on verra »).
3. Tracez position A / B / décision dans `decisions_binome.md`.

## Pièges fréquents

| Piège | Conséquence |
|---|---|
| Coller les 2 cadrages | Conception incohérente |
| Compromis mou (« les deux ») | Sur-engineering / indécision |
| S'aligner par fatigue | Choix non argumenté |
| Ne tracer que le résultat | Pas de preuve de négociation |
| Éviter le désaccord | On rate l'amélioration mutuelle |

| Symptôme | Cause probable |
|---|---|
| Dossier contradictoire | union au lieu de convergence |
| Archi qui « met tout » | compromis mou |
| Restitution décousue | pas de décision commune claire |

## Pour aller plus loin

- Cf. M6-B2 (coordination groupe) — collaboration à plus grande échelle.
- Pair programming (Fowler) : https://martinfowler.com/articles/on-pair-programming.html

## Vérification (checklist apprenant)

- [ ] On a listé 3-5 divergences majeures.
- [ ] Chaque divergence est **tranchée** (pas « on verra »).
- [ ] `decisions_binome.md` trace position A / B / décision.
- [ ] Pas de compromis mou (« on met les deux »).
- [ ] La conception finale est **cohérente** (une seule vision).

> 💡 **Récap — Convergence binôme** : convergence ≠ union ≠ compromis mou : on **négocie** et on **tranche** chaque divergence avec une raison ; tracer position A / B / décision dans `decisions_binome.md`. Le désaccord sain (« et si plus simple ? ») améliore la conception.

### À retenir

- Le livrable se juge sur sa **clarté pour le destinataire**, pas sur sa longueur.
- **Chiffrer** plutôt qu'affirmer : un nombre vaut mieux qu'un adjectif.
- **Sobriété** : recommander le plus simple qui résout le besoin, et **dire ce qu'on écarte**.
- Distinguer ce qu'on **sait** de ce qui reste **à clarifier** (questions ouvertes).
- Tracer ses **choix** et leur **raison** — c'est ce qui se défend en restitution.
