# kubernetes-lab 2 : Créer un service de type nodeport

1) Ecrire un manifest namespace qui crée un namespace nommé production et lancer la création de ce namespace à partir du manifest
2) Toutes les prochaines ressources doivent être créées dans le namespace produciton
3) Ecrivez un manifest pod-red.yml pour déployer un pod avec l'image mmumshad/simple-webapp-color en précisant que la couleur souchaitée est la rouge(red) et le pod doit posséder le label "app: web"
4) Ecrivez un manifest pod-blue.yml pour déployer un pod avec l'image mmumshad/simple-webapp-color en précisant que la couleur souchaitée est la bleu(blue) et le pod doit posséder le label "app: web"
5) Lancer la création des 2 pods
6) Ecrire un manifest service-nodeport-web.yml qui permettra d'exposer les pods via un service de type node port, le nodeport devra être le 30008 et les target les ports 8080 de nos pods dont le label est "app: web"
7) Lancer la création du service et vérifier qu'il trouve les deux pods(champ endpoint en utilisant la commande kubectl describe)
8) vérifier que l'application est bien disponible en ouvrant le port 30008 de votre noeud.


# Les commandes tapées suivront ASAP
