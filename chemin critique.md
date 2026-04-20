# Exercice chemin critique
**1. Diagramme de dépendances**
<img width="1012" height="732" alt="image" src="https://github.com/user-attachments/assets/d71714d1-16c5-470f-ad61-bce1be0a75bf" />

**2. Tous les chemins possibles (de A à J)**

| # | Chemin | Durée |
|---|--------|-------|
| 1 | A → C → D → E → G → I → J | 3+4+3+8+4+5+2 = **29j** ⭐ |
| 2 | A → B → F → G → I → J | 3+5+6+4+5+2 = **25j** |
| 3 | A → B → H → I → J | 3+5+2+5+2 = **17j** |

---

**3. Chemin critique**

Le chemin critique est **A → C → D → E → G → I → J** avec une durée de **29 jours**. C'est la durée minimale incompressible du projet.

---

**4. Marges des lots**

| Lot | Chemin le plus long le traversant | Durée | Marge |
|-----|----------------------------------|-------|-------|
| **B** | A→B→F→G→I→J = 25j | 25j | 29 – 25 = **4j** |
| **F** | A→B→F→G→I→J = 25j | 25j | 29 – 25 = **4j** |
| **H** | A→B→H→I→J = 17j | 17j | 29 – 17 = **12j** |
| A, C, D, E, G, I, J | Chemin critique | 29j | **0j** (aucune marge) |

En clair : les lots B, F et H peuvent prendre du retard sans décaler la date de fin du projet — dans la limite de leur marge respective. Tout retard sur A, C, D, E, G, I ou J retarde directement la livraison.

