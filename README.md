# 🛠️ Script Toolbox

Bienvenue sur mon dépôt **`scripts`** !  
Ce dépôt regroupe une collection de **scripts utiles et réutilisables** pour l’administration système, le développement, l’automatisation et plus encore.

Chaque script est isolé dans son propre dossier, avec les fichiers nécessaires (`script.sh`, `README.md`, etc.) pour une utilisation claire et modulaire.

---

## 📁 Structure du dépôt

📘 Chaque script dispose de son propre dossier avec un `README.md` explicatif.

```bash
scripts/
├── backup/
│   ├── backup.sh
│   └── README.md
├── update-containers/
│   ├── update.sh
│   └── README.md
└── README.md
```

> 📂 Chaque dossier = un script autonome  
> 📄 Le fichier `README.md` explique l'utilisation, les paramètres et les dépendances éventuelles

---

## 🚀 Utilisation

1. Clone ce dépôt :
   ```bash
   git clone https://github.com/MrDouille/scripts.git
   cd scripts/nom_du_script
   ```
2. Lis le `README.md` du dossier pour connaître les prérequis
3. Rends le script exécutable si besoin :
   ```bash
   chmod +x script.sh
   ```
4. Exécute-le :
   ```bash
   ./script.sh
   ```

---

## ⚙️ Prérequis

- Un shell Unix-compatible (bash, sh, zsh…)
- Les dépendances spécifiques sont listées dans chaque dossier
- Certaines commandes peuvent nécessiter les droits sudo

---

## ✅ Bonnes pratiques

- Relis toujours le script avant exécution 📄
- Adapte les chemins ou variables à ton environnement
- Tu peux forker ce repo pour y ajouter tes propres scripts

---

## 🙌 Contribuer

Une idée de script utile ?  
Les contributions sont les bienvenues via **pull request** ou **issues** !

---

## 📄 Licence

Ce dépôt est sous licence [MIT](LICENSE).  
Tu peux l’utiliser librement, mais évite d’y stocker des informations sensibles.

---

> ✉️ Pour toute question ou suggestion, tu peux ouvrir une issue ici sur GitHub.
