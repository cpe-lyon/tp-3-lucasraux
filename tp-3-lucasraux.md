## TP 3 - Utilisateurs, groupes et permissions

### Exercice 1. Gestion des utilisateurs et des groupes

#### 1. Utilisez la commande groupadd pour créer deux groupes dev et infra

![GitHub Logo](/assets/ex1.1.png)

#### 2. Créez ensuite 4 utilisateurs alice, bob, charlie, dave avec la commande useradd, en demandant la création de leur dossier personnel et avec bash pour shell

![GitHub Logo](/assets/ex1.2.a.png)

![GitHub Logo](/assets/ex1.2.b.png)

![GitHub Logo](/assets/ex1.2.c.png)

![GitHub Logo](/assets/ex1.2.d.png)


#### 3. Ajoutez les utilisateurs dans les groupes créés :
- alice, bob, dave dans dev

![GitHub Logo](/assets/ex1.3.1.png)

- bob, charlie, dave dans infra

![GitHub Logo](/assets/ex1.3.2.png)

#### 4. Donnez deux moyens d’afficher les membres de infra

![GitHub Logo](/assets/ex1.4.png)

#### 5. Faites de dev le groupe propriétaire des répertoires /home/alice et /home/bob et de infra le groupe propriétaire de /home/charlie et /home/dave

![GitHub Logo](/assets/ex1.5.1.png)

![GitHub Logo](/assets/ex1.5.2.png)

#### 6. Remplacez le groupe primaire des utilisateurs :

- dev pour alice et bob || infra pour charlie et dave

![GitHub Logo](/assets/ex1.6.png)

#### 7. Créez deux répertoires /home/dev et /home/infra pour le contenu commun aux membres de chaque groupe, et mettez en place les permissions leur permettant d’écrire dans ces dossiers.

![GitHub Logo](/assets/ex1.7.png)

#### 8. Comment faire pour que, dans ces dossiers, seul le propriétaire d’un fichier ait le droit de renommer ou supprimer ce fichier ?

##### ??????????

#### 9. Pouvez-vous ouvrir une session en tant que alice ? Pourquoi ?

![GitHub Logo](/assets/ex1.9.png)

#### 10. Activez le compte de l’utilisateur alice et vérifiez que vous pouvez désormais vous connecter avec son compte.

![GitHub Logo](/assets/ex1.10.png)

