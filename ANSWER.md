# Answers

Nom : Savary  
Prénom : Matthias

# 1.
Qu'est-ce qu'une instance EC2 ?
Une instance EC2 est un serveur virtuel hébergé dans Elastic Compute Cloud (EC2) pour exécuter des applications sur l'infrastructure Amazon Web Services (AWS).


# 2.
Qu'est-ce qu'un VPC ?
Un Virtual Private Cloud est un groupe de ressources informatiques configurables à la demande dans un environnement de cloud public, qui fournit un certain niveau d'isolement entre les différentes organisations (appelées utilisateurs) qui utilisent ces ressources. L'isolation entre le VPC et les autres utilisateurs du cloud est habituellement obtenue par l'utilisation d'un sous-réseau IP et d'un mécanisme de communication virtuel (tel qu'un VLAN ou un groupe de canaux chiffrés) pour chaque utilisateur.
# 3.
A quoi sert un NSG 
Un Network Security Group est constitué d'un ensemble de règles de contrôle d'accès décrivant les filtres de trafic. Ceux-ci peuvent être associés à une machine virtuelle ou à un sous-réseau de la même région. Les règles définies dans le NSG servent de filtres. Sur le chemin d'entrée, ils sont appliqués avant que le trafic entre dans la VM.

# 4.
Quelles sont les 5 propriétés désirables du cloud ?
Paiement à l'usage
Elastique
Ouvert
Mutualisé
Libre-service

# 5.
Qu'est-ce que l'A/B Testing ?
Le but de l'A/B testing est de determiner quelle version d'un visuel (par exemple un site web) est la 
efficace. Pour cela, on divise les utilisateurs en 2 parties de façon totalement aleatoire. Chaque groupe de personne utilisera une version differente du site web. On pourra ainsi voir laquelle des 2 versions est la plus efficace en fonction de ce que l'on recherche (fluidite dans la navigation, suggestion d'achat...)
# 6.
Comment programmer le cloud ?
Il faut utiliser la configuration "Infrastructure as code".

# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?
Il faut faire du ZDD (Zero Downtime Deployment). 
# 8.
Qu'est-ce que le Canary release ?
L'objectif est de faire basculé les utilisateurs petit à petit vers la version N+1. Donc on demarre avec une portion de 5% des utilisateurs, puis progressivement si il n'y a pas de probleme, on deploie la mise à jour pour le reste des utilisateurs. C'est une des technique du ZDD.

# 9.
Comment changer de taille de machine virtuelle ?

# 10.
Qu'est-ce que le Blue/Green deployment ?
Le Blue Green deployment propose d’avoir un environnement de production identique à celui qui est utilisé par les utilisateurs qui recevra une nouvelle version. Ainsi si un probleme survient, il sera plus facile de faire un rollback
