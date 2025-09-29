# 🛒 Application SAÉ IHM – Gestion et optimisation d’un magasin

Projet réalisé dans le cadre du **BUT Informatique (IUT de Calais, 2024-2025)**.  
Cette application en **Python/PyQt6** permet à un gestionnaire de magasin de créer un plan, d’y placer des produits et d’exporter une liste avec leurs emplacements.  

---

## 🚀 Objectif
- Gérer les informations principales du magasin (nom, adresse, auteur, date, etc.)  
- Afficher un plan du magasin et positionner des produits dans les rayons  
- Sauvegarder et recharger une configuration existante  
- Exporter une liste des produits avec leurs coordonnées  

---

## 📦 Prérequis

### Installer Python
- **Windows** : télécharger depuis [python.org](https://www.python.org/downloads/), cocher *Add Python to PATH* lors de l’installation.  

- **Linux (Ubuntu/Debian)** :

```bash
sudo apt update && sudo apt upgrade
sudo apt install python3 python3-pip
```

### Installer PyQt6
- **Windows** :

```bash
python -m pip install --upgrade pip
pip install PyQt6
```

- **Linux (Ubuntu/Debian)** :

```bash
sudo apt install python3-pip python3-venv
pip3 install PyQt6
```

---

## ▶️ Lancement de l’application
1. Télécharger l’archive `Application1`  
2. Décompresser dans un dossier local  
3. Ouvrir un terminal dans ce dossier  
4. Lancer la commande suivante :  

```bash
python main.py
```

---

## 🖥️ Utilisation
1. Importer le plan du magasin :  
   - Menu → **Afficher le plan** → choisir `Images/Plan.jpg`  
   - Le plan s’affiche avec un quadrillage pour placer les produits  

2. Compléter les informations de l’entreprise :  
   - Nom du projet  
   - Auteur  
   - Date de création  
   - Nom et adresse du magasin  

3. Sauvegarder / Charger un projet :  
   - Menu **Fichier → Sauvegarder**  
   - Menu **Fichier → Ouvrir**  

4. Positionner les produits :  
   - Sélectionner une catégorie (ex : *Légumes*)  
   - Cliquer sur la zone du plan correspondante pour les placer  

5. Exporter la liste des produits :  
   - Bouton **Exporter**  
   - Fichier généré dans `liste_produit_entreprise/NomDuMagasin_liste_produits`  

---

## 📷 Captures d’écran
*(ajoute ici des images de ton application pour la rendre plus attractive)*  
```markdown
![Accueil](images/screenshot_accueil.png)
![Plan magasin](images/screenshot_plan.png)
```

---

## 👥 Travail en groupe
Projet réalisé en équipe dans le cadre de la **SAÉ IHM – BUT1** :  
- **Mahana Bernard**  
- **Gabin Bonnier**  
- **Thomas Justin**  
- **Jordan Sow**  

---

## ⚙️ Technologies utilisées
- **Python 3.13.7**  
- **PyQt6** pour l’interface graphique  

---

## 📜 Licence
Ce projet est distribué sous licence MIT – voir le fichier [LICENSE](LICENSE) pour plus d’informations.  

---

## 🚀 Améliorations possibles
- Ajout d’un algorithme de recherche du chemin optimal dans le magasin  
- Interface utilisateur enrichie avec plus de visuels  
- Export vers différents formats (CSV, JSON, Excel)  
