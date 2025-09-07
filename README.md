# 🧮 Calcul Mental - L'Aventure Mathématique Interactive

> **Une application web ludique et pédagogique pour maîtriser le calcul mental du CE1 au CM2** 🎯

[![Licence](https://img.shields.io/badge/Licence-Libre-brightgreen.svg)](LICENSE)
[![Niveau](https://img.shields.io/badge/Niveau-CE1%20à%20CM2-blue.svg)](#niveaux-disponibles)
[![Technologie](https://img.shields.io/badge/Tech-HTML%2FCSS%2FJS-orange.svg)](#technologies)

---

## 🚀 **Démarrer l'aventure**

### 🎮 **[► JOUER MAINTENANT ◄](./calcul-mental.html)**

*Cliquez sur le lien ci-dessus pour commencer votre entraînement au calcul mental !*

---

## ✨ **Qu'est-ce que Calcul Mental ?**

**Calcul Mental** est une application web interactive conçue pour aider les élèves de l'école primaire à développer leurs compétences en mathématiques de manière **amusante** et **progressive**. 

### 🎯 **Pourquoi cette application ?**

- 📚 **Pédagogiquement structurée** : Suit le programme officiel français
- 🎮 **Ludique et motivante** : Sons, animations et récompenses
- 📊 **Progression personnalisée** : Système d'étapes par niveau de difficulté
- 🏆 **Évaluation encourageante** : Feedback positif et constructif
- 💻 **Accessible partout** : Fonctionne sur ordinateur, tablette et smartphone

---

## 🎓 **Niveaux disponibles**

### 📚 **CE1 (6-7 ans)**
| Difficulté | Étapes | Compétences |
|------------|--------|-------------|
| 🌱 **Facile** | 5 étapes | Addition 1-5 → Addition 1-10 → Soustraction 1-5 → Soustraction 1-10 → Révisions |
| 🌿 **Moyen** | 5 étapes | Addition jusqu'à 20 → Soustraction jusqu'à 20 → Doubles → Calculs rapides → Révisions |
| 🌳 **Difficile** | 5 étapes | Addition avec retenue → Soustraction avec emprunt → Multiplications → Calculs mixtes → Maîtrise |

### 📖 **CE2 (7-8 ans)**
| Difficulté | Étapes | Compétences |
|------------|--------|-------------|
| 🌱 **Facile** | 5 étapes | Addition jusqu'à 100 → Soustraction jusqu'à 100 → Tables 2,5,10 → Révisions → Rapidité |
| 🌿 **Moyen** | 5 étapes | Addition avec retenue → Soustraction avec emprunt → Tables jusqu'à 5 → Division → Révisions |
| 🌳 **Difficile** | 5 étapes | Calculs jusqu'à 1000 → Toutes les tables → Division avec reste → Problèmes → Défis |

### 📗 **CM1 (8-9 ans)** & 📘 **CM2 (9-10 ans)**
*Niveaux avancés avec fractions, décimaux, géométrie et résolution de problèmes complexes*

---

## 🎮 **Comment ça marche ?**

### 1️⃣ **Choix du niveau**
```
📚 CE1    📖 CE2    📗 CM1    📘 CM2
```

### 2️⃣ **Sélection dans la matrice**
```
        │ 🌱 Facile │ 🌿 Moyen │ 🌳 Difficile │
Étape 1 │ Addition  │ Add. 20  │ Add. retenue │
Étape 2 │ Add. 1-10 │ Soust.20 │ Soust. empr. │
Étape 3 │ Soust.1-5 │ Doubles  │ Multiplica.  │
Étape 4 │ Soust.1-10│ Rapides  │ Calc. mixtes │
Étape 5 │ Révisions │ Révisions│ Maîtrise     │
```

### 3️⃣ **Entraînement interactif**
- ✏️ **Saisie des réponses** au clavier ou tactile
- 🔊 **Sons de feedback** (correct/incorrect)
- 🎆 **Animations** pour les bonnes réponses
- 📊 **Barre de progression** en temps réel

### 4️⃣ **Évaluation motivante**
```
🏆 Excellent ! (90-100%) - "Tu es un champion !"
🌟 Très bien ! (80-89%)  - "Superbe travail !"
👍 Bien joué ! (70-79%)  - "Bon résultat !"
💪 Pas mal !   (60-69%)  - "Tu progresses !"
🎯 Continue !  (<60%)    - "Apprends des erreurs !"
```

---

## 🛠 **Technologies**

- **HTML5** : Structure moderne et sémantique
- **CSS3** : Design responsive et animations fluides
- **JavaScript ES6+** : Logique interactive et Web Audio API
- **JSON** : Données d'exercices structurées
- **Progressive Web App** : Fonctionne hors ligne

---

## 🎨 **Fonctionnalités**

### ✨ **Interface utilisateur**
- 🎨 **Design moderne** avec dégradés et animations
- 📱 **Responsive** : S'adapte à tous les écrans
- 🎵 **Audio interactif** : Sons de réussite et d'erreur
- 🎆 **Animations de particules** pour célébrer les succès

### 📊 **Pédagogie**
- 📈 **Progression structurée** par étapes
- 🔄 **Exercices mélangés** pour éviter la mémorisation
- 📋 **Évaluation détaillée** avec pourcentages
- 💬 **Messages motivants** adaptés au niveau

### 🎯 **Navigation**
- ⌨️ **Contrôles clavier** : Entrée, flèches, Échap
- 🖱️ **Interface tactile** optimisée
- 🔙 **Navigation linéaire** avec début et fin définis
- 🏠 **Retour facile** à la sélection

---

## 🚀 **Installation et utilisation**

### 💻 **Utilisation locale**
```bash
# Cloner le projet
git clone [url-du-repo]

# Naviguer dans le dossier
cd ecole-treilles

# Lancer un serveur local
python3 -m http.server 8000
# ou
npx serve .

# Ouvrir dans le navigateur
http://localhost:8000/calcul-mental.html
```

### 🌐 **Déploiement web**
- Compatible **GitHub Pages**
- Compatible **Netlify**, **Vercel**
- Aucune dépendance serveur requise
- Fonctionne avec n'importe quel hébergeur statique

---

## 📚 **Structure du projet**

```
ecole-treilles/
├── calcul-mental.html      # Application principale
├── styles.css              # Styles et animations
├── mathe/                  # Données d'exercices
│   ├── ce1-facile.json
│   ├── ce1-moyen.json
│   ├── ce1-difficile.json
│   ├── ce2-facile.json
│   └── ...
└── README.md               # Cette documentation
```

---

## 🎓 **Pour les enseignants**

### 📋 **Utilisation en classe**
- **Projection** : Idéal pour les exercices collectifs
- **Individuel** : Chaque élève à son rythme
- **Évaluation** : Suivi des progrès avec statistiques
- **Différenciation** : Niveaux adaptés à chaque élève

### 🎯 **Objectifs pédagogiques**
- Automatisation du calcul mental
- Renforcement de la confiance en mathématiques
- Apprentissage ludique et motivant
- Respect du rythme individuel

---

## 👨‍👩‍👧‍👦 **Pour les parents**

### 🏠 **Utilisation à la maison**
- **Révisions** : Complément idéal aux devoirs
- **Vacances** : Maintien des acquis pendant les congés
- **Autonomie** : L'enfant peut s'entraîner seul
- **Motivation** : Système de récompenses intégré

### 📈 **Suivi des progrès**
- Résultats immédiats après chaque session
- Messages encourageants adaptés au niveau
- Progression visible étape par étape

---

## 📄 **Licence et utilisation**

### 🆓 **Libre et gratuit**

**Cette application est entièrement libre et gratuite !** 

✅ **Vous pouvez :**
- Utiliser l'application dans votre école
- La partager avec d'autres enseignants
- L'adapter à vos besoins pédagogiques
- La déployer sur votre propre site web
- L'utiliser à des fins commerciales

❌ **Aucune restriction :**
- Pas de licence à payer
- Pas de compte à créer
- Pas de publicité
- Pas de collecte de données

### 🤝 **Contribution et soutien**

**💝 Vous aimez cette application ? Montrez votre soutien !**

- ⭐ **Donnez une étoile** au projet sur GitHub (bouton "Star" en haut à droite)
- 🔄 **Partagez** avec vos collègues enseignants
- 💬 **Laissez un commentaire** positif dans les [Discussions](../../discussions)
- 📝 **Témoignage** : Créez une [issue](../../issues/new) avec le label "témoignage"

**🛠️ Les contributions techniques sont aussi les bienvenues :**
- 🐛 Signaler des bugs
- 💡 Proposer de nouvelles fonctionnalités  
- 📚 Ajouter des niveaux d'exercices
- 🎨 Améliorer l'interface
- 🌍 Traduire en d'autres langues

---

## 🎉 **Commencer maintenant**

### 🎮 **[► LANCER L'APPLICATION ◄](./calcul-mental.html)**

*Prêt pour l'aventure mathématique ? Un clic suffit !* 🚀

---

## 📞 **Support et contact**

**🚨 IMPORTANT : Tout support uniquement via GitHub Issues !**

**🔧 Support technique :**
- 🐛 **Bugs** : [Signaler un problème](../../issues/new)
- 💡 **Suggestions** : [Proposer une amélioration](../../issues/new)
- ❓ **Questions** : [Poser une question](../../issues/new)
- 📚 **Documentation** : [Améliorer la documentation](../../issues/new)

**💝 Feedback positif :**
- ⭐ **Étoile GitHub** : Cliquez sur "Star" en haut de cette page
- 💬 **Témoignages** : [Partagez votre expérience](../../issues/new) (titre: "Témoignage: ...")
- 🗣️ **Discussions** : [Rejoignez les discussions](../../discussions)

**Aucun autre canal de support n'est disponible.**

### 📝 **Comment bien signaler un problème :**
- **Titre clair** : Décrivez le problème en une phrase
- **Étapes pour reproduire** : Comment le problème survient-il ?
- **Comportement attendu** : Que devrait-il se passer ?
- **Environnement** : Navigateur, OS, version
- **Captures d'écran** : Si applicable
---

*Fait avec ❤️ pour l'éducation française*

**Bonne aventure mathématique !** 🧮✨
