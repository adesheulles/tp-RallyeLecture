# tp-RallyeLecture
Dans ce tp nous devons faire un programme pour lire un fichier csv qui contient le nom et prénom d'élève puis on leur créer un login et
un mot de passe que l'on met dans un nouveaux fichier csv ensuite on crée c'est élève dans la base de donnée et on crée leur classe.

 
 Les outils mis en oeuvre :
 * VisualStudio
 * WindowsForm
 
 Le développement tourne autour de 4 grandes parties.
 * Connection d'un utilisateur.
 * Lecture est stockage des donnée d'un fichier csv.
 * Création d'un fichier csv avec le login et mot de passe de chaque éleve.
 * Envoi des informations dans la base de données.
 
 |développement          |langages |technique de programmation                           |
|-----------------------|:-------:|----------------------------------------------------:|
|Connection d'un utilisateur |c#|programmation objet|
|Lecture est stockage des donnée d'un fichier csv |c#|programmation objet|
|Création d'un fichier csv avec le login et mot de passe de chaque éleve|c#|programmation objet|
|Envoit des informations dans la base de donnée|c#|programmation objet|
 
 # Cas d'utilisation :
 
  ![Capture.png](https://github.com/adesheulles/tp-RallyeLecture-application/blob/master/casUtilisation.PNG)
 
 # Connection d'un utilisateur :
 

 ![Capture.png](https://github.com/adesheulles/tp-RallyeLecture-application/blob/master/connection.PNG)
  
  
 # Formulaire :
 
  ![Capture.png](https://github.com/adesheulles/tp-RallyeLecture-application/blob/master/alimentation.PNG)
 
 # Lecture est stockage des donnée d'un fichier csv :
 Le programme lit un fichier csv ligne par ligne et crée un élève avec un mot de passe qui sera soit aléatoire ou bien construi(première lettre du prénom + nom), choit fait par l'utilisateur.
 
   ![Capture.png](https://github.com/adesheulles/tp-RallyeLecture-application/blob/master/Eleve.PNG)
 
 # Création d'un fichier csv avec le login et mot de passe de chaque élève :
 Crée un fichier csv indiquant le login et le mot de passe de chaque élève.
 
  ![Capture.png](https://github.com/adesheulles/tp-RallyeLecture-application/blob/master/csvEleve.PNG)
  
 # Envoies des informations dans la base de donnée :
 Envoie de requête qui va ajouter les élève dans la table élève et dans aauth-user puis créer une classe dans la table classe.

