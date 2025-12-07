# Systèmes automatisés - Barrage à clapet
**Niveau : 3ᵉ - Technologie**

---

## 📚 Révision du cours

### 1. Les systèmes automatisés

Un système automatisé fonctionne sans intervention humaine continue. Il utilise :

- ✅ **Des capteurs** pour mesurer (température, niveau, pression...)
- ✅ **Un automate** pour décider (traiter les informations)
- ✅ **Des actionneurs** pour agir (moteur, pompe, vérin...)
- ✅ **Un écran** pour informer l'utilisateur

### 2. Les deux chaînes à connaître

#### 🔵 Chaîne d'information
```
Capteur → Automate → Affichage
(Acquérir) → (Traiter) → (Communiquer)
```

**Exemple pour le barrage :**
- **Acquérir** : capteur de niveau d'eau
- **Traiter** : automate de gestion
- **Communiquer** : écran de visualisation

#### 🔴 Chaîne d'énergie
```
Électricité → Relais → Hydraulique → Mouvement
(Alimenter) → (Distribuer) → (Convertir/Transmettre) → (Action)
```

**Exemple pour le barrage :**
- **Énergie d'entrée** : énergie électrique
- **Alimenter** : réseau électrique 230V
- **Distribuer** : relais électrique de distribution
- **Convertir et transmettre** : ensemble hydraulique (moteur/pompe)
- **Énergie de sortie** : énergie mécanique → mouvement du clapet

⚠️ **Attention** : L'eau n'est PAS une énergie !

### 3. Fonctionnement du barrage à clapet

Le barrage fonctionne selon 3 modes automatiques :

| Niveau d'eau | Position du clapet | Voyant |
|--------------|-------------------|---------|
| Normal | Position 2 | 🟢 Vert |
| Haut | Position 3 | 🔴 Rouge |
| Bas | Position 1 | 🟠 Orange |

---

## ✅ Correction des exercices

### 📌 Question 3 – Tableau des fonctions et des éléments associés

| Fonctions | Éléments du barrage à clapet |
|-----------|------------------------------|
| Retenir l'eau en amont | Clapet (3) |
| Détecter le niveau d'eau amont | Capteur de niveau d'eau amont (2) |
| Gérer la position du clapet | Ensemble hydraulique – moteur/pompe (1) |
| Alimenter le barrage en électricité | Réseau électrique 230 V (5) |
| Distribuer l'électricité | Relais électrique de distribution (6) |
| Afficher des informations | Écran de visualisation (7) |

---

### 📌 Question 4 – Chaînes d'information et d'énergie

#### Chaîne d'information
- **Acquérir** : capteur de niveau d'eau
- **Traiter** : automate de gestion
- **Communiquer** : écran de visualisation

#### Chaîne d'énergie
- **Énergie d'entrée** : énergie électrique
- **Alimenter** : réseau électrique
- **Distribuer** : relais électrique de distribution
- **Convertir et transmettre** : ensemble hydraulique
- **Énergie de sortie** : énergie mécanique → mouvement du clapet

---

### 📌 Question 5 – Compléter le logigramme

#### Logigramme du système automatisé

```
Début
  ↓
Niveau normal ?
  ↓ OUI                    ↓ NON
Mettre clapet position 2   Niveau haut ?
Mettre voyant vert           ↓ OUI              ↓ NON
  ↓                        Mettre clapet         Mettre clapet
Retour                     position 3            position 1
                           Mettre voyant rouge   Mettre voyant orange
                             ↓                     ↓
                           Retour                Retour
```

#### ⭐ Erreurs fréquentes à éviter :
- ❌ Oublier le voyant orange pour niveau bas
- ❌ Mal placer "position du clapet 1"
- ❌ Inverser les étapes dans le programme

---

### 📌 Programme par blocs - Correspondances

| Numéro | Signification |
|--------|---------------|
| 1 | Niveau normal |
| 2 | Niveau haut |
| 3 | Mettre voyant vert |
| 4 | Mettre voyant rouge |
| 5 | Mettre clapet position 2 |
| 6 | Mettre clapet position 3 |
| 7 | Mettre clapet position 1 + voyant orange |

---

## 🎓 Points clés à retenir

### Les 3 niveaux d'eau
- **Niveau normal** → clapet position 2 → 🟢 voyant vert
- **Niveau haut** → clapet position 3 → 🔴 voyant rouge
- **Niveau bas** → clapet position 1 → 🟠 voyant orange

### Différence capteur / actionneur
- **Capteur** : mesure une grandeur physique → acquiert l'information
- **Actionneur** : transforme l'énergie pour produire une action mécanique

### Séquences à connaître par cœur

**Chaîne d'information :**
```
Acquérir → Traiter → Communiquer
```

**Chaîne d'énergie :**
```
Alimenter → Distribuer → Convertir/Transmettre → Agir
```

---

## 📝 QCM d'entraînement (20 questions)

### 🔹 PARTIE 1 – Questions faciles (5)

**1. Quel élément permet de mesurer le niveau d'eau ?**
- A. Le clapet
- B. Le capteur 
- C. Le relais électrique
- D. L'automate


- B. Le capteur ✅

**2. Le clapet est un élément…**
- A. d'acquisition
- B. d'affichage
- C. d'action 
- D. d'alimentation

- C. d'action ✅

**3. Quelle énergie alimente le système ?**
- A. Thermique
- B. Électrique 
- C. Solaire
- D. Chimique

- B. Électrique ✅

**4. L'écran de visualisation sert à…**
- A. Décider
- B. Agir
- C. Afficher des informations 
- D. Convertir l'énergie

- C. Afficher des informations ✅


**5. Si le niveau d'eau est normal, le voyant doit être…**
- A. Rouge
- B. Orange
- C. Bleu
- D. Vert 

- D. Vert ✅


---

### 🔹 PARTIE 2 – Questions moyennes (5)

**6. Dans la chaîne d'information, l'automate réalise la fonction :**
- A. Acquérir
- B. Traiter 
- C. Convertir
- D. Afficher

- B. Traiter ✅


**7. Dans la chaîne d'énergie, quel élément transforme l'énergie électrique en mouvement ?**
- A. L'écran
- B. Le capteur
- C. L'ensemble hydraulique 
- D. Le relais de distribution

- C. L'ensemble hydraulique ✅


**8. Quel élément distribue l'électricité vers les actionneurs ?**
- A. Le relais électrique 
- B. L'écran
- C. Le capteur
- D. Le clapet

- A. Le relais électrique ✅

**9. Pour un niveau d'eau haut, le clapet va en position…**
- A. 1
- B. 2
- C. 3 
- D. 0

- C. 3 ✅

**10. Le voyant rouge correspond à un niveau…**
- A. Normal
- B. Haut 
- C. Bas
- D. Très bas

- B. Haut ✅

---

### 🔹 PARTIE 3 – Questions difficiles (10)

**11. Quelle est la bonne séquence de la chaîne d'information ?**
- A. Traiter → Acquérir → Communiquer
- B. Communiquer → Traiter → Acquérir
- C. Acquérir → Traiter → Communiquer 
- D. Acquérir → Communiquer → Traiter

- C. Acquérir → Traiter → Communiquer ✅


**12. Quelle est la bonne séquence de la chaîne d'énergie ?**
- A. Distribuer → Alimenter → Convertir → Agir
- B. Alimenter → Distribuer → Convertir/Transmettre → Agir 
- C. Convertir → Alimenter → Distribuer → Agir
- D. Alimenter → Convertir → Distribuer → Agir

- B. Alimenter → Distribuer → Convertir/Transmettre → Agir ✅


**13. Le système hydraulique appartient à la fonction :**
- A. Distribuer l'énergie
- B. Convertir / transmettre l'énergie 
- C. Acquérir l'information
- D. Afficher les données

- B. Convertir / transmettre l'énergie ✅


**14. Si le niveau d'eau est bas, le voyant doit être :**
- A. Vert
- B. Rouge
- C. Orange 
- D. Bleu

- C. Orange ✅


**15. Si le niveau d'eau est bas, le clapet va en position :**
- A. 1 
- B. 2
- C. 3
- D. 4

- A. 1 ✅

**16. Dans un système automatisé, un capteur transforme :**
- A. Une énergie en information 
- B. Une information en énergie
- C. Une action en décision
- D. L'électricité en mouvement

- A. Une énergie en information ✅

**17. Quand l'automate reçoit un niveau haut, il envoie :**
- A. Un ordre d'ouvrir plus le clapet 
- B. Un ordre de fermer complètement
- C. Un ordre d'allumer le voyant vert
- D. Un ordre d'éteindre le système

- A. Un ordre d'ouvrir plus le clapet ✅

**18. Quel est le rôle du relais électrique de distribution ?**
- A. Convertir l'énergie électrique en mouvement
- B. Recevoir les informations du capteur
- C. Acheminer l'électricité vers l'ensemble hydraulique 
- D. Mesurer le niveau d'eau

- C. Acheminer l'électricité vers l'ensemble hydraulique ✅


**19. Dans le logigramme, après "niveau normal ?", si la réponse est NON, on vérifie :**
- A. Le niveau bas
- B. Le niveau haut 
- C. La position du clapet
- D. Le voyant

- B. Le niveau haut ✅

**20. Quel serait un danger si le système hydraulique tombe en panne et que l'eau monte ?**
- A. Le voyant vert reste allumé
- B. Le clapet reste en position 1 et l'eau déborde 
- C. Le système affiche des données incorrectes
- D. L'écran s'éteint seulement

- B. Le clapet reste en position 1 et l'eau déborde ✅

---

## 📊 Correction complète du QCM

### ✔️ Questions faciles (1-5)
1. **B** - Le capteur
2. **C** - d'action
3. **B** - Électrique
4. **C** - Afficher des informations
5. **D** - Vert

### ✔️ Questions moyennes (6-10)
6. **B** - Traiter
7. **C** - L'ensemble hydraulique
8. **A** - Le relais électrique
9. **C** - Position 3
10. **B** - Haut

### ✔️ Questions difficiles (11-20)
11. **C** - Acquérir → Traiter → Communiquer
12. **B** - Alimenter → Distribuer → Convertir/Transmettre → Agir
13. **B** - Convertir / transmettre l'énergie
14. **C** - Orange
15. **A** - Position 1
16. **A** - Une énergie en information
17. **A** - Un ordre d'ouvrir plus le clapet
18. **C** - Acheminer l'électricité vers l'ensemble hydraulique
19. **B** - Le niveau haut
20. **B** - Le clapet reste en position 1 et l'eau déborde

---

## 💡 Conseils pour réussir

1. **Apprendre les deux chaînes par cœur** (information et énergie)
2. **Connaître les 3 positions du clapet** et leurs voyants associés
3. **Savoir faire un logigramme** en respectant les conditions
4. **Différencier capteur et actionneur**
5. **Comprendre que l'eau n'est pas une énergie** (erreur fréquente !)

---

## 📌 Schéma récapitulatif

```
SYSTÈME AUTOMATISÉ DU BARRAGE
═══════════════════════════════

┌─────────────────────────────────────────┐
│      CHAÎNE D'INFORMATION               │
├─────────────────────────────────────────┤
│ Capteur → Automate → Écran              │
│ (niveau)  (décide)   (affiche)          │
└─────────────────────────────────────────┘

┌─────────────────────────────────────────┐
│      CHAÎNE D'ÉNERGIE                   │
├─────────────────────────────────────────┤
│ 230V → Relais → Hydraulique → Clapet    │
│ (alimente) (distribue) (convertit) (agit)│
└─────────────────────────────────────────┘

RÉSULTAT :
🟢 Normal → Position 2
🔴 Haut → Position 3
🟠 Bas → Position 1
```

---

**Bon courage pour tes révisions ! 💪📖**
