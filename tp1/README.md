# tp1_cloudera
<!-- Configuration d'Ansible : Créez un fichier inventory pour définir les hôtes de votre cluster Hadoop. Assurez-vous d'organiser les hôtes en groupes selon leur rôle (par exemple, master, standby, workers, edge).

Test de connexion : Exécutez une commande Ansible ad-hoc pour tester la connectivité à tous les hôtes de votre inventaire. Par exemple:

bash
Copy code
ansible all -i inventory -m ping
Partie 2 : Surveillance de l'état du cluster
Vérification de l'état du cluster Hadoop : Écrivez un playbook Ansible qui exécute la commande hadoop dfsadmin -report sur le serveur Master pour vérifier l'état de santé du cluster HDFS.

Vérification de l'espace disque : Ajoutez une tâche dans votre playbook pour vérifier l'espace disque disponible sur les nœuds Workers.

Partie 3 : Gestion des services Hadoop
Démarrage/Arrêt des services : Créez un playbook pour démarrer et arrêter les services Hadoop sur le cluster. Utilisez les commandes de gestion des services de Cloudera Manager (via cloudera-scm-agent).

Déploiement de configuration : Écrivez un playbook pour mettre à jour un fichier de configuration Hadoop (par exemple, core-site.xml) sur tous les nœuds et redémarrer les services nécessaires après.

Partie 4 : Maintenance et mise à jour
Mise à jour de logiciels : Développez un playbook pour installer ou mettre à jour des logiciels spécifiques sur les nœuds Edge, où les applications client Hadoop sont généralement exécutées.

Rotation des logs : Configurez une tâche pour compresser et déplacer les fichiers log anciens dans un répertoire d'archive sur les nœuds Workers.

Conclusion
Ce TP vous donnera une expérience pratique de la gestion quotidienne d'un cluster Hadoop avec Cloudera, tout en vous initiant à l'automatisation avec Ansible. N'oubliez pas de tester chaque playbook individuellement dans un environnement de développement ou de test avant de les exécuter sur votre cluster de production. Cette approche vous aidera à éviter les erreurs courantes et à vous familiariser avec le flux de travail de l'administration Hadoop. -->