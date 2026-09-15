# M8-B2 — Concevoir l'architecture cible (arbitrages explicites, binôme par cas)

> **Repo template.** Binôme = les 2 qui ont tiré le **même cas** en M8-B1. « Use
> this template » → `M8-B2-conception-<cas>-<binome>`. **Pas de code** (pseudo-code OK).
> Restitution **en ouverture de M9** (15 min, format certif).

---

## 🧭 Votre brief en un coup d'œil

| Support | Rôle |
|---|---|
| **Simplonline** | Le contrat : contexte, livrables, critères |
| **Ce README** | Le pilotage : quoi produire, dans quel ordre |
| [`ressources/`](./ressources/) | 6 mini-cours + [`fiche_chiffrage.md`](./ressources/fiche_chiffrage.md) |
| **Discord `fil-M8-B2`** | Questions communes |

### L'async binôme (jeudi + vendredi matin, 5 h)

| Étape | À produire | Fichier |
|---|---|---|
| 1 | Converger depuis vos 2 cadrages | `decisions_binome_TEMPLATE.md` |
| 2 | **5 fiches d'arbitrage** (½ page max ; ≥ 1 raison **chiffrée** ; « non applicable » justifié accepté) | `arbitrages/0{1..5}_*.md` |
| 3 | **Dossier de conception** (10 p **maximum**, pas une cible) — livrable principal (pile, pipeline, évaluation, déploiement, monitoring, pseudo-code, **sécurité** ; questions jury en annexe) | `dossier_conception_TEMPLATE.md` |
| 4 | Schéma final (support de la restitution orale — pas de slides) | `schema_archi_finale_TEMPLATE.md` |

### ✅ Checklist livrables (avant vendredi 17h)

- [ ] 5 arbitrages **tranchés ou non applicables** (justifiés en 1 ligne) — pas de
      GenAI forcée par la grille ; ≥ 1 raison **chiffrée sur votre volumétrie**
- [ ] Archi **cohérente** avec les arbitrages (RAG non ⇒ pas de vector DB)
- [ ] **Sobriété visible** : la section « ce qu'on n'a PAS mis », justifiée
- [ ] **Sécurité** : les menaces du cadrage B1 ont une réponse d'architecture
- [ ] 5-10 questions jury **réalistes** en annexe du dossier ; restitution orale sur le schéma final, sans slides
- [ ] Convergence tracée (négociation, pas union) ; **journal de bord** tenu

## ⭐ Extension (non notée, si socle bouclé) — la contradictoire croisée

Échangez votre dossier avec le binôme d'un **autre cas** : chaque binôme
attaque par écrit **3 points** du dossier de l'autre (un chiffre non
recalculé, une incohérence archi/arbitrage, une menace sans réponse), puis
chacun répond — accepte ou défend. 20 minutes chrono par sens. Le jury de
M9 fera exactement ça : autant l'avoir déjà vécu par écrit.

## 📚 Ressources

Voir [`./ressources/`](./ressources/) — 6 mini-cours + `fiche_chiffrage.md` + `liens_officiels.md`.
