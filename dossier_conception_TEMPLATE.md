# Dossier de conception — <votre cas> (À COMPLÉTER)

**Client :** <nom, rôle> · **Binôme :** <prénoms> · **Cas <A/B/C/D>**

> **10 pages max**, lisible par un architecte technique. Ce dossier
> **synthétise** : les sections 3 à 7 reprennent vos fichiers
> `conception/*.md`, la section 2 vos `arbitrages/`. Pas de copier-coller
> intégral — la version longue reste dans les fichiers, ici on tranche.

---

## 1. Synthèse (½ page)

<!-- TODO : la solution en 4-5 lignes — quoi, pour quel gain chiffré, avec
     quelle posture de sobriété. Un lecteur pressé ne lit que ça. -->

## 2. Les 5 arbitrages (résumé — 1 tableau)

| Arbitrage | Choix | Raison clé (1 ligne) |
|---|---|---|
| ML vs DL | | |
| SLM vs LLM | | |
| RAG oui/non | | |
| Agents oui/non | | |
| Zero-shot suffit ? | | |

<!-- Chaque ligne renvoie au fichier arbitrages/ correspondant.
     ≥ 1 raison chiffrée sur les arbitrages 2-5 (cf.
     ressources/fiche_chiffrage.md + cheatsheet sobriété & coûts). -->

## 3. Pile technique

<!-- TODO : cf. conception/pile_technique.md — familles + candidats,
     et le bloc « ce qu'on n'a PAS mis » (critère sobriété). -->

## 4. Pipeline données

<!-- TODO : cf. conception/pipeline_donnees.md -->

## 5. Déploiement

<!-- TODO : cf. conception/deploiement.md -->

## 6. Monitoring

<!-- TODO : cf. conception/monitoring.md -->

## 7. Pseudo-code du composant critique

<!-- TODO : cf. conception/pseudo_code_critique.md — UN composant, celui
     qui porte la décision. -->

## 8. Schéma final

<!-- Renvoi : schema_archi_finale.md (Mermaid, cohérent avec le tableau §2 :
     pas de vector DB si RAG=non, pas d'orchestrateur si agents=non). -->

## 9. Conformité et sécurité

<!-- TODO obligatoire — 2 volets :
     a) Conformité : RGPD (base légale, minimisation), AI Act (quelle
        catégorie de risque, pourquoi, quelles obligations).
     b) Sécurité (menaces B1 → réponses d'ARCHITECTURE) : reprenez les
        menaces identifiées au cadrage et dites quelle brique y répond.
        Si RAG : injection indirecte (corpus empoisonné) — qui alimente le
        corpus, que peut faire la génération ? Si agents : moindre
        privilège + HITL — que peut faire l'agent au pire ? Si ni l'un ni
        l'autre : dites-le et montrez la surface d'attaque restante. -->
