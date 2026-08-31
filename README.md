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
| 2 | **5 arbitrages** (choix + 3 raisons dont ≥ 1 **chiffrée** + condition) | `arbitrages/0{1..5}_*.md` |
| 3 | Conception (pile / pipeline / déploiement / monitoring / pseudo-code) | `conception/*.md` |
| 4 | Schéma final + dossier 10 p (avec section **sécurité**) | `schema_archi_finale_TEMPLATE.md`, `dossier_conception_TEMPLATE.md` |
| 5 | Slides + questions jury | `slides_TEMPLATE.md`, `questions_jury_TEMPLATE.md` |

### ✅ Checklist livrables (avant vendredi 17h)

- [ ] 5 arbitrages **tous tranchés** (3 raisons + condition de changement d'avis),
      ≥ 1 raison **chiffrée sur votre volumétrie** (fiche chiffrage, pas recopiée)
- [ ] Archi **cohérente** avec les arbitrages (RAG non ⇒ pas de vector DB)
- [ ] **Sobriété visible** : la section « ce qu'on n'a PAS mis », justifiée
- [ ] **Sécurité** : les menaces du cadrage B1 ont une réponse d'architecture
- [ ] Slides format certif (≤ 10, lisibles à 3 m) ; 5-10 questions jury **réalistes**
- [ ] Convergence tracée (négociation, pas union) ; **journal de bord** tenu

## ⭐ Extension (non notée, si socle bouclé) — la contradictoire croisée

Échangez votre dossier avec le binôme d'un **autre cas** : chaque binôme
attaque par écrit **3 points** du dossier de l'autre (un chiffre non
recalculé, une incohérence archi/arbitrage, une menace sans réponse), puis
chacun répond — accepte ou défend. 20 minutes chrono par sens. Le jury de
M9 fera exactement ça : autant l'avoir déjà vécu par écrit.

## 📚 Ressources

Voir [`./ressources/`](./ressources/) — 6 mini-cours + `fiche_chiffrage.md` + `liens_officiels.md`.
