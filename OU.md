## 1.  Accès
  
2 moyens pour y accéder au Utilisateurs et ordinateurs Active Directory  : 

- Barre du titre de la console > Outil > [Utilisateurs et ordinateurs Active Directory](https://github.com/Fairskip/Organizational_Unit/blob/main/Users%20%26%20Hosts%20AD%201.png) 
- Clic droit sur le serveur > [Utilisateurs et ordinateurs Active Directory](https://github.com/Fairskip/Organizational_Unit/blob/main/Users%20%26%20Hosts%20AD%202.png) 

<br>
  
## 2. Utilisateurs et ordinateurs Active Directory 

#### 1 - Création d'une Unité d'Organisation  

- Cliquer sur l'icone Nouvel Unité d'Organisation situé sur la barre des taches
- Donner un nom
- Ok

![OU](https://github.com/Fairskip/Organizational_Unit/blob/main/OU%20wilders_students.png)

<br>

### 2 - Création d'un Groupe  

- Cliquer sur l'icone Nouveau groupe situé sur la barre des taches
- Donner un nom
- Ok

![group](https://github.com/Fairskip/Organizational_Unit/blob/main/Group%20Students.png)

<br>

### 3 - Création d'un User  

- Cliquer sur l'[icone Nouveau groupe situé sur la barre des taches](https://github.com/Fairskip/Organizational_Unit/blob/main/User%201.png)  
- Remplir le [formulaire](https://github.com/Fairskip/Organizational_Unit/blob/main/User%202_mdp_%40zerty1234.png)  . Suivant.
- Donner un [mot de passe long et compliqué](https://github.com/Fairskip/Organizational_Unit/blob/main/User%203.png)    . Choisir les options désirés. Suivant.
- Terminer

![user](https://github.com/Fairskip/Organizational_Unit/blob/main/User%204.png)  

<br>

### 4 - Ajouter un user au groupe Students  

- Double clic sur le groupe
- Général > membres => Ajouter
- Entrez les noms des objets à selectionner => entrer la première lettre de l'user, cliquer sur verifier les noms. Le nom de l'user s'affichera de lui-même.
- Ok

![user into group](https://github.com/Fairskip/Organizational_Unit/blob/main/OU_ajouter%20un%20user%20%C3%A0%20un%20groupe.png)

<br>

# 5 - Tester l'accès d'un user récemment créé sur un PC Host pour une première utilisation.  

Si le PC a bien rejoint le domaine Wilder :   

![test1](https://github.com/Fairskip/Organizational_Unit/blob/main/User%20Test%201.png)

* Cliquer sur Autre utilisateur.
* Entrer l'ID du login donné par l'administrateur (aka moi). Ne pas oublier de mettre le nom du domaine avant l'ID suivit d'un anti-slash.
* Entrer le mot de passe donné par l'administrateur

  ![test2](https://github.com/Fairskip/Organizational_Unit/blob/main/User%20test%202.png)

  * L'ID est valide. Toutefois avant la première connexion, il faut changer le mot de passe.
 
![test3](https://github.com/Fairskip/Organizational_Unit/blob/main/User%20test%203.png)

  * Mettre l'ancien mot de passe compliqué, inscrire le nouveau mot de passe tout aussi compliqué et le confirmer en y réécrivant le dite nouveau mot de passe.
  * Valider.

![test4](https://github.com/Fairskip/Organizational_Unit/blob/main/User%20test%204.png)  

* Il est possible maintenant de se logger avec son nouveau mot de passe.
