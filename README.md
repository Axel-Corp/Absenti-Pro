# **AbsensiPro - Gestion des Congés et Absences**

AbsensiPro est un logiciel moderne et simple pour gérer les congés et absences des employés dans une entreprise. Développé en Python, il propose une interface intuitive pour enregistrer les employés, suivre leur solde de congés et soumettre des demandes d'absence.

## **Fonctionnalités**
- **Ajout d'employés** : Ajoutez les informations des employés avec leur poste et leur solde de congés.  
- **Suivi des congés** : Consultez une liste complète des employés et surveillez leur solde de congés.  
- **Demande de congés** : Créez des demandes d'absence en sélectionnant un employé et les dates souhaitées.  
- **Base de données intégrée** : Toutes les informations sont stockées dans une base SQLite.

---

## **Prérequis**
- Python 3.x installé sur votre machine.
- Bibliothèques incluses avec Python :  
  - `sqlite3` (gestion des données)  
  - `tkinter` (interface graphique)

---

## **Installation**
1. Clonez ce dépôt ou téléchargez les fichiers nécessaires :  
   ```bash
   git clone https://github.com/votre-utilisateur/absensipro.git
   cd absensipro

## **Utilisation**

1. **Ajout d'employés** :  
   - Cliquez sur **"Ajouter un employé"** et remplissez les informations requises : nom, poste et solde de congés.
2. **Visualisation des employés** :  
   - Une liste affiche les employés enregistrés avec leur solde actuel de congés.
3. **Création de demandes** :  
   - Sélectionnez un employé, renseignez les dates de début et de fin, et soumettez la demande d'absence.
4. **Gestion des données** :  
   - Les données sont automatiquement sauvegardées dans un fichier SQLite nommé `absensipro.db`.

---

## **Améliorations futures**

- Interface pour valider ou rejeter les demandes de congés.  
- Rapport exportable au format PDF ou Excel.  
- Intégration d'une gestion par calendrier interactif.  
- Notifications automatiques pour les gestionnaires (par email ou SMS).

---

## **Capture d'écran**

_(Ajoutez ici une capture d'écran si disponible)_  
<img src="screenshot.png" alt="Capture d'écran d'AbsensiPro" width="600">

---

## **Licence**

Ce projet est sous licence MIT. Vous pouvez l'utiliser, le modifier et le redistribuer librement.

---

## **Crédits**

Développé par Axel Corp.
