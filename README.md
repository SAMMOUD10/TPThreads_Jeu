# TPThreads_Jeu

- Ce TP est pour objectif d'implémenter une petite jeu Client Serveur en utilisant le principe de thread.
ce jeu consiste à définir un nombre entier de manière aléatoire et les clients doit de diviner tout simplement.

# Classe ServerJeu (Serveur Multi Threads):
Voici l'ensemble d'instruction du code utilisé pour établir la classe ServerJeu:
- Premièrement j'ai créer une classe nommé ServerJeu qui hérite de la classe Thread
- J'ai redéfinir la méthode run dont lequel je vais créer ServerSocket
- J'ai crée le ServerSocket et j'attend jusqu'a la connexion est établie
- J'ai crée une variable qui va prendre un nombre aléatoire à chaque fois quand en démarre le serveur
- J'ai crée la classe conversation qui désigne en fait le comportement du client.
- J'ai fait la comparaison entre ce que le client saisi avec ce que le serveur défini

![serveur](https://user-images.githubusercontent.com/102219821/160020217-c9956c2a-d0f7-41ba-b2c6-8e0d84328fc6.png)


- suite du code de la classe ServerJeu

![suite2](https://user-images.githubusercontent.com/102219821/160020306-3b7b8a8f-ce8c-40d5-9f3d-802dc1d0e1f7.png)

- suite du code de la classe ServerJeu

![suite3](https://user-images.githubusercontent.com/102219821/160020350-39ac2ad6-e7a9-4128-83af-a467d5510204.png)

# Exécution

- Lancement du serveur: ****************************************************************
![démarrage du serveur](https://user-images.githubusercontent.com/102219821/160021200-b1d8dc26-e25a-4936-991c-7e694b1dbf1b.png)

- Lancement du client telnet: ****************************************************************
![démarrage du client](https://user-images.githubusercontent.com/102219821/160021224-5785140d-56cd-44c3-a4e9-ab7f5dccfedb.png)

- Le client envoi un nombre au serveur et recevoir par la suite le résultat de sa prédication
![saisir un nombre](https://user-images.githubusercontent.com/102219821/160021260-262e2c0b-fb68-465f-8686-ea1496241275.png)

- Le serveur reçoit le nombre envoyé par le client et vérifier s'il est correct ou non et de l'envoyer le résultat 
![repondre au client](https://user-images.githubusercontent.com/102219821/160021293-d6b9a7ce-f478-458c-a2b8-b4198a362ce5.png)

- le cas oû le nombre envoyé par le client est correct par rapport ce qui déja défini par le serveur
![nombre correct](https://user-images.githubusercontent.com/102219821/160021360-071ba434-c568-4890-9f8b-f8afce18a0df.png)
