# 🎴 Omnicard - Jeu de Cartes Stratégique et Modulaire

**Omnicard** est un jeu de cartes stratégique, narratif et hautement personnalisable, mêlant des mécaniques originales à une esthétique soignée. Il s’inspire de nombreux univers issus de la pop culture, des jeux vidéo aux animés, en passant par des créations originales.
---

## 🗂️ Arborescence du projet

```
public-Omnicard
├───Carte
│   └───saison_01
│       ├───bloodborne
│       ├───jojo_bizzare_adventure
│       └───wtf
├───Document
│   ├───Livret
│   └───(raccourcis vers Google Drive, Livrets, Règles)
├───.gitattributes
├───README.md
```

📁 **Carte/** : contient toutes les cartes, triées par saison et catégorie (Bloodborne, Jojo, etc.).
Chaque catégorie contient cinq types de cartes : `Unite`, `Sort`, `Terrain`, `Piege`, `Equipement`.

📁 **Document/** : regroupe les documents de référence pour les joueurs :

* `Livret/` : livrets illustrés complets des cartes
* `Regle.url` : lien vers les règles officielles
* `GoogleDrive.url` : accès centralisé à toutes les ressources publiques

---

## 📚 Livrets et Cartes

Chaque **catégorie** (univers) possède son propre **livret illustré**. Ils sont disponibles dans `Document/Livret/`.

Chaque livret comprend des sections par type de carte :

* 🛡️ **Unité** : personnages avec PV / PA
* ✨ **Sort** : effets à usage unique
* 🧠 **Piège** : effets cachés déclenchés sous condition
* 🌍 **Terrain** : carte active unique influençant le jeu
* ⚔️ **Équipement** : objets s’attachant à une unité

🔍 **Chaque carte affiche :**

* Une illustration
* Son nom, type, coût, statistiques
* Sa ou ses familles / catégories
* Un effet complet (avec mots-clés techniques)
* Son statut : *Légendaire* (1 seule par deck), *Invocation* (non jouable directement)

---

## 📖 Règles du jeu

🔗 Le document de règles est accessible via `Document/Regle.url`. Voici les grandes lignes du gameplay :

* 🧙 Chaque joueur débute avec **2 Mana**, puis en gagne **+1 par tour** (jusqu'à 10 max)
* 💎 La Mana non utilisée devient un **Cristal** (max 5), utilisable comme Mana
* 🃏 Le deck est composé de **40 cartes** réparties selon 5 types
* ❌ Les cartes **ne défendent pas** automatiquement ; pour attaquer un joueur, son terrain doit être vide
* ❤️ Chaque joueur commence avec **40 PV**
* 🔀 Le plateau comporte **2 lignes de 10 emplacements** chacune ; certains effets dépendent de la ligne (avant/arrière)

### 🧩 Composition d’un Deck

Vous pouvez composer votre deck à partir de **jusqu’à 5 catégories** (univers).

* **Catégorie principale (1ère)** : jusqu’à 40 cartes (100%)
* **2e catégorie** : max 20 cartes
* **3e catégorie** : max 10 cartes
* **4e catégorie** : max 4 cartes
* **5e catégorie** : max 1 carte

---

## 🛠️ Génération des Cartes et Livrets

Ce dépôt est également utilisé pour générer automatiquement les livrets illustrés à partir d’un **Google Sheet** via un script Google Apps.

### 🔄 Fonctionnalités du script :

* Génère un Google Doc avec mise en page automatique
* Affiche chaque carte avec image, titre, stats, effet, famille, statut
* Trie les cartes par type (Unité, Sort, etc.) sur des pages distinctes
* Intègre les images hébergées via Google Drive (liens `/uc?export=view&id=`)

📌 Le script est à venir dans une future section du dépôt.

---

## 🧪 Statuts de cartes

* 🟪 **Légendaire** : une seule copie autorisée dans le deck
* 🔮 **Invocation** : carte créée par effet, non jouable directement

---

## 🚧 État du projet

🔧 **En développement actif**. Les mécaniques, cartes, visuels et interfaces sont amenés à évoluer.

✅ Cartes disponibles pour les catégories :

* Jojo’s Bizarre Adventure
* Bloodborne
* WTF

📌 Chaque nouvelle saison ou extension ajoutera de nouvelles cartes, effets et mécaniques.

---

## 🤝 Contribution

Vous pouvez contribuer de plusieurs manières :

* 📝 Proposer des idées de mécaniques ou d’univers
* 🐛 Remonter des bugs ou des incohérences via les issues
* 🧩 Créer vos propres catégories et cartes via le format établi

---

## 🔗 Liens utiles

* 📁 [Accès Google Drive Public](https://drive.google.com/drive/folders/1jzkH1dhuYOw4pObaTGOPLtqTOptEKr9g?usp=drive_link)
* 📜 [Règles Officielles](https://docs.google.com/document/d/1mgtt0cQY0ZIfcbaNRI4depJPEG7k_EK_QcFoiQ_McKQ/edit?usp=drive_link)
* 📚 [Livrets de cartes](https://docs.google.com/document/d/1Cmm5wtN2-XPV-eHg-GNI3fIKXJe9_oDSnHdmrJCceJc/edit?usp=drive_link)

---

## ✉️ Contact

Pour toute question ou retour :

* Email : **[charles.lindecker@outlook.fr](mailto:charles.lindecker@outlook.fr)**
* Auteur : [Charles Lindecker](https://www.linkedin.com/in/charles-lindecker/)

---

> Merci d’avoir consulté ce projet ! Que la partie commence. 🎮
