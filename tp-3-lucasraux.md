## TP 3 - Utilisateurs, groupes et permissions

### Exercice 1. Gestion des utilisateurs et des groupes

#### 1. Utilisez la commande groupadd pour créer deux groupes dev et infra

#### 2. Créez ensuite 4 utilisateurs alice, bob, charlie, dave avec la commande useradd, en demandant la création de leur dossier personnel et avec bash pour shell

#### 3. Ajoutez les utilisateurs dans les groupes créés :
- alice, bob, dave dans dev
- bob, charlie, dave dans infra

#### 4. Donnez deux moyens d’afficher les membres de infra

#### 5. Faites de dev le groupe propriétaire des répertoires /home/alice et /home/bob et de infra le groupe propriétaire de /home/charlie et /home/dave

#### 6. Remplacez le groupe primaire des utilisateurs :
- dev pour alice et bob
- infra pour charlie et dave
- 
#### 7. Créez deux répertoires /home/dev et /home/infra pour le contenu commun aux membres de chaque groupe, et mettez en place les permissions leur permettant d’écrire dans ces dossiers.

#### 8. Comment faire pour que, dans ces dossiers, seul le propriétaire d’un fichier ait le droit de renommer ou supprimer ce fichier ?

#### 9. Pouvez-vous ouvrir une session en tant que alice ? Pourquoi ?

#### 10. Activez le compte de l’utilisateur alice et vérifiez que vous pouvez désormais vous connecter avec son compte.

