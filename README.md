# TP-RMI
Mon rendu pour le TP-RMI en Architectures Distribués

Travail de : Sanchez Martin

Il y a 4 projets fait sur éclipse:
 TP-RMI: Tout est dans le même projet, donc on utilise pas de codebase pour
    	 télécharger du code chez le client.
 
 TP-RMI-Common: Projet contenant uniquement les interfaces.
 TP-RMI-Client: Projet qui contiens le client, et une interface utile au serveur.
 TP-RMI-Server: Projet qui contiens le serveur.

Comment executer ?
 1. Importer les 4 projet dans eclipse
 2. Pour TP-RMI: Lancer le serveur, puis le client
    Pour le reste: Ajouter 'TP-RMI-Common' dans le classpath des deux autres
                   Ajouter 'TP-RMI-Client' dans le classpath du serveur
                   Lancez le serveur, puis le client
