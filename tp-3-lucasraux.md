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

#### 11. Comment obtenir l’uid et le gid de alice ?

![GitHub Logo](/assets/ex1.11.png)

#### 12. Quelle commande permet de retrouver l’utilisateur dont l’uid est 1003 ?

![GitHub Logo](/assets/ex1.12.png)

#### 13. Quel est l’id du groupe dev ?

![GitHub Logo](/assets/ex1.13.png)

#### 14. Quel groupe a pour gid 1002 ? ( Rien n’empêche d’avoir un groupe dont le nom serait 1002...)

![GitHub Logo](/assets/ex1.14.png)

#### 15. Retirez l’utilisateur charlie du groupe infra. Que se passe-t-il ? Expliquez.

![GitHub Logo](/assets/ex1.15.png)

#### 16. Modifiez le compte de dave de sorte que :

— il expire au 1er juin 2021

![GitHub Logo](/assets/ex1.16.1.png)

— il faut changer de mot de passe avant 90 jours
— il faut attendre 5 jours pour modifier un mot de passe
— l’utilisateur est averti 14 jours avant l’expiration de son mot de passe
— le compte sera bloqué 30 jours après expiration du mot de passe

#### 17. Quel est l’interpréteur de commandes (Shell) de l’utilisateur root ?

![GitHub Logo](/assets/ex1.17.png)

#### 18. Si vous regardez la liste des comptes présents sur la machine, vous verrez qu’il en existe un nommé nobody. A quoi correspond-il ?

![GitHub Logo](/assets/ex1.18.png)

#### 19. Par défaut, combien de temps la commande sudo conserve-t-elle votre mot de passe en mémoire ?


##### Quelle commande permet de forcer sudo à oublier votre mot de passe ?

![GitHub Logo](/assets/ex1.19.png)
