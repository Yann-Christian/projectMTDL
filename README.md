# javahealth
Ennoce :

Le Ministère de la Santé, en collaboration avec les hôpitaux, les cabinets et les cliniques publiques ou privées, a décidé que la Roumaine a besoin d’un nouveau système de e-health, plus innovant et flexible. Ils ont demandé à votre compagnie de développer un système logiciel pour gérer les processus métier associés. Les demandes d’un tel système sont les suivantes :
•	La plateforme a plusieurs types d’utilisateurs : personnel médical (médecins, assistants, infirmières), patients, pharmaciens, fournisseurs (médicaments, appareils médicaux, équipements), administrateurs.
•	Pour avoir accès à l’application, chaque utilisateur doit premièrement s’enregistrer en ligne, cela signifie créer un compte en fournissant ses informations personnelles (incluant un code unique – par exemple un code unique pour chaque membre du personnel médical / le CNP pour les patients), adresse d’email, mot-de-passe.
•	Chaque patient peut faire une programmation pour une consultation, en choisissant le domaine médical correspondant (contrôle ophtalmologique, ORL, contrôle de routine etc.), le jour et l’heure de la visite. Le système va lui afficher les cabinets / hôpitaux et les médecins disponibles.
•	Chaque médecin peut ajouter des consultations dans le système, incluant les informations du patient, la date de la visite, les maladies, le traitement offert. Les médecins et les assistants peuvent aussi libérer des recettes contenant les médicaments indiqués au patient.
•	Le pharmacien va recevoir la recette (en format image) et donne les médicaments indiqués (ou des substituants) au patient.
•	Les fournisseurs maintiennent des catalogues mises à jour avec les informations des leurs produits (description, photos, prix), qui peuvent être accédés soit par le personnel médical, soit par les deux, personnel médical et patients.  
•	Chaque administrateur a le droit d’effacer des utilisateurs inactifs ou des produits médicaux qui n’ont pas toutes les informations essentielles mises à jour.

Le système :
-    Une application Java desktop implémentée utilisant Java FX, incluant les fonctionnalités identifiées dans la description et incluses dans les diagrammes. Elle doit permettre aussi de visualiser les photos des recettes et des équipements (upload des images).  
- Utiliser aussi 1 test unitaire pour vérifier des fonctionnalités de votre application ! 

La création d’une base de données avec les informations des utilisateurs, des consultations, des droits d'accès différents (création, actualisation, effacement).


Fonctionnement :

Java-health est une application qui nécessite une inscription pour afin de pourvoir acceder aux différentes interfaces.

Pour s’inscrire l’utilisateur aura besoin d’introduire son nom, son prénom, son adresse mail, son mot de passe, son code unique qui représente en gros son CNP, et son type d’utilisateur(Médecin, Patient,…). 

Il n’est pas possible de s’inscrire en tant que administrateur car les administrateurs sont directement introduits dans la bases de données.

L’interface de l’application présente plusieurs fenêtre qui s’affiche selon le types de utilisateur.
Avec c’est application, il est possible au patient de faire une pour un patient de programmer une consultation tout en choisissant la date, le domaine médicale, l’hôpital et le médecin. 

Le médecin á la possibilité de voir toutes les programmations des patients qui l’ont choisit.

L’administateur est le gérant de tous ce qui ce passe dans l’application. Il a accès a tous les interfaces et peut faire des mises a jour.


