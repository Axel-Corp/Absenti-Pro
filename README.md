# **TimeEase - Gestion des Congés et Absences**

TimeEase est une application de bureau simple et intuitive, développée en Python, pour gérer les employés, les congés, et les absences dans une entreprise.  

## **Fonctionnalités**
- **Ajout d'employés** : Enregistre les informations des employés (nom, poste, solde de congés).  
- **Liste des employés** : Affiche tous les employés et leur solde de congés.  
- **Demande de congés** : Permet de soumettre une demande avec des dates de début et de fin.  
- **Base de données intégrée** : Toutes les données sont stockées dans une base SQLite.  

---

## **Prérequis**
- Python 3.x installé sur votre machine.
- Bibliothèques Python incluses :  
  - `sqlite3` (inclus avec Python)  
  - `tkinter` (inclus avec Python)  

---

## **Installation**
1. Clonez ce dépôt ou téléchargez les fichiers :  
   ```bash
   git clone https://github.com/votre-utilisateur/timeease.git
   cd timeease
Lancez le script Python :
bash
Copier le code
python timeease.py
Utilisation
Ajouter un employé :
Cliquez sur le bouton "Ajouter un employé" et remplissez le formulaire avec les informations nécessaires.
Lister les employés :
La liste des employés s'affiche automatiquement à chaque lancement de l'application.
Demander un congé :
Sélectionnez un employé dans la liste, puis cliquez sur "Demander un congé" pour soumettre une demande.
Stockage des données :
Les données sont stockées dans le fichier timeease.db généré automatiquement.
Améliorations futures
Système de validation des demandes (acceptation/refus).
Intégration d'un calendrier interactif.
Notifications par email pour les nouvelles demandes.
Interface web avec Flask ou Django.
Capture d'écran
(Ajoutez une capture si nécessaire)
<img src="screenshot.png" alt="Capture d'écran de TimeEase" width="600">

Licence
Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, le modifier et le redistribuer.
