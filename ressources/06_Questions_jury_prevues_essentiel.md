# Anticiper les questions du jury — Mini-cours

> Brief associé : M8-B2
> Durée de lecture : ~15 min
> Pré-requis : conception + slides

## Pourquoi cette techno ?

En soutenance (mardi M9, puis en certif), les **5 minutes de Q&A** font souvent la
différence. Un binôme qui a **anticipé** les questions probables et préparé ses
réponses paraît maître de son sujet ; un binôme pris au dépourvu doute. Préparer
5-10 questions réalistes est un entraînement direct à la **soutenance certif** (où
le jury creuse pendant 30 min).

## Concepts clés

- **Questions réalistes** : pas « qu'est-ce qu'un LLM ? » mais « pourquoi pas un
  fine-tuning du SLM au lieu du zero-shot ? ». Le jury creuse les **choix**.
- **Les questions visent vos arbitrages** : chaque « non » (pas de LLM, pas de RAG)
  appelle un « pourquoi ? » → préparez la réponse.
- **Réponse = la condition de changement d'avis** : « on changerait si… » montre que
  le choix est réfléchi, pas dogmatique.
- **Anticiper la sobriété** : « c'est pas un peu simple ? » est la question reine —
  votre réponse défend la sobriété (coût, explicabilité, conformité).
- **5-10 suffisent** : préparation, pas paranoïa. Couvrir les arbitrages + la
  conformité + le coût.
- **Réponses courtes** : 2-3 phrases, chiffrées si possible.

## Exemple minimal qui tourne

```markdown
1. Pourquoi pas un LLM ? → Sur-dimensionné pour 5 classes avec dataset labellisé ;
   coût ~10×, opacité, PII à protéger. ML = plus précis ici.
2. Et si le modèle se trompe ? → Erreur récupérable + seuil de revue humaine + monitoring.
```

## Exercice guidé

À partir de tes arbitrages :
1. Pour chaque « non » (LLM, RAG, agents), anticipe le « pourquoi ? ».
2. Prépare 5-10 questions + réponses (2-3 phrases, chiffrées).
3. Avec ton binôme : qui répond à quelle question ?

## Pièges fréquents

| Piège | Conséquence |
|---|---|
| Questions triviales | N'entraîne pas le vrai Q&A |
| 30 questions | Paranoïa, dispersion |
| Réponses longues | On perd le jury |
| Pas de chiffres | Réponses peu convaincantes |
| Ne pas répartir | Hésitation en duo |

| Symptôme | Cause probable |
|---|---|
| Pris au dépourvu en Q&A | questions non anticipées |
| Réponse dogmatique | pas de condition de changement d'avis |
| Le jury insiste sur la sobriété | défense non préparée |

## Pour aller plus loin

- Cf. `questions_jury_prevues.md` du correctif (6 Q+R).
- M9 — soutenance certif (30 min Q&A) : ceci est l'entraînement.

## Vérification (checklist apprenant)

- [ ] 5-10 questions **réalistes** (pas triviales).
- [ ] Chaque « non » d'arbitrage a sa réponse préparée.
- [ ] Réponses courtes (2-3 phrases), chiffrées si possible.
- [ ] La question « c'est pas trop simple ? » est anticipée.
- [ ] Répartition des réponses en duo.

> 💡 **Récap — Questions jury** : anticiper 5-10 questions **réalistes** (pas « qu'est-ce qu'un LLM ? ») ; chaque « non » d'arbitrage appelle un « pourquoi ? » → la réponse = la condition de changement d'avis ; anticiper « c'est pas trop simple ? » (défense de la sobriété). Réponses courtes, chiffrées.

### À retenir

- Le livrable se juge sur sa **clarté pour le destinataire**, pas sur sa longueur.
- **Chiffrer** plutôt qu'affirmer : un nombre vaut mieux qu'un adjectif.
- **Sobriété** : recommander le plus simple qui résout le besoin, et **dire ce qu'on écarte**.
- Distinguer ce qu'on **sait** de ce qui reste **à clarifier** (questions ouvertes).
- Tracer ses **choix** et leur **raison** — c'est ce qui se défend en restitution.
