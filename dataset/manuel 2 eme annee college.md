Présentation du manuel
Identification

Manuel : « @ Nous l'Informatique »
Niveau : 2ème Année du cycle Secondaire Collégial — Manuel de l'élève
Structure : 4 unités et 5 séquences, organisées de façon identique
Chaque séquence est constituée de séances


UNITÉ 1 : Environnement matériel et système d'exploitation
Compétence et prolongements de l'unité

Compétence à développer : maîtriser les technologies de base relatives au fonctionnement d'un système informatique
Prolongements : recherche documentaire, Internet (informatique) ; ondes, optique (sciences physiques) ; techniques d'expression et de communication (français)

Séquence 1 — Objectifs

Appréhender la notion de réseau informatique
Identifier les avantages d'un réseau local
Identifier les différents constituants matériels d'un réseau local
Configurer un réseau local

Séquence 1 — Pré-requis

Savoir utiliser les fonctions de base du système d'exploitation Windows

Notion de réseau (général)

Un réseau est constitué de points d'intersection appelés nœuds, reliés par un ensemble de chemins selon la matière à véhiculer
Réseau routier : transporte personnes et biens entre zones géographiques
Réseau téléphonique : fait circuler la voix entre postes téléphoniques
Réseau d'eau potable : ensemble de canaux distribuant l'eau

Notion de réseau informatique

Ensemble d'ordinateurs et périphériques connectés par des supports de transmission afin de communiquer
Deux ordinateurs connectés constituent un réseau minimal

Utilité d'un réseau informatique

Partager des ressources matérielles et logicielles (fichiers, applications, imprimante, scanner, modem)
Communiquer entre les membres du réseau
Gagner du temps
Réduire le coût d'équipement

Organisation des réseaux

Poste à poste : tous les ordinateurs sont égaux et indépendants, chacun met des ressources à disposition
Client/serveur : hiérarchie à deux niveaux (serveur et clients)
Serveur : ordinateur qui centralise les ressources partagées, disponibles en permanence
Clients : stations de travail qui exploitent les ressources du serveur

Types de réseaux selon le support

Réseau filaire : utilise des câbles pour relier les éléments
Réseau sans fil : liaison par ondes radio-électriques (radio, infrarouge) au lieu de câbles

Réseau filaire — carte et connecteurs

L'ordinateur doit avoir une carte réseau et des connecteurs normalisés
Prises RJ45 : reçoivent les câbles à paires torsadées
Prises BNC : reçoivent un câble coaxial

Types de câbles

Câble coaxial : transmission de signaux numériques ou analogiques (ex. antenne TV–télévision) ; deux variantes : coaxial fin, coaxial épais
Câble à paires torsadées (RJ45) : deux brins de cuivre entrelacés et isolés, regroupés dans une gaine protectrice ; le plus utilisé en réseaux locaux
Fibre optique : utilise la lumière au lieu du courant ; très grande vitesse, longues distances, insensible aux perturbations

Comparaison des câbles (Tableau 1)

Coaxial fin : longueur max plus d'une centaine de mètres, coût très faible, sensibilité au bruit très élevée
Coaxial épais : des centaines de mètres, coût faible, sensibilité au bruit très élevée
Paires torsadées : une centaine de mètres, coût faible, sensibilité au bruit faible
Fibre optique : plusieurs km, coût très élevé, sensibilité au bruit très faible

Réseau sans fil — équipements

Ordinateurs et périphériques équipés de récepteurs/émetteurs WiFi appelés adaptateurs sans fil
Formes : adaptateur USB WiFi, carte PCI WiFi, PCMCIA WiFi (portables)
Liaison sans fil : infrarouge ou hertzien, ondes radio-électriques, propagation en ligne droite ; satellites pour grandes distances

Topologies physiques de réseau

La topologie physique est l'arrangement physique des éléments d'un réseau
Topologie en bus : nœuds reliés à un même câble partagé ; simple à mettre en œuvre, mais vulnérable (un coupleur défectueux affecte tout le réseau)
Topologie en étoile : ordinateurs reliés à un système matériel central ; facile à surveiller, la panne d'une station n'affecte pas le réseau
Topologie en anneau : boucle où chaque ordinateur « a la parole » successivement
Critères de choix : débits, nombre d'utilisateurs maximal, temps d'accès, tolérance aux pannes, longueur de câblage, types d'applications

Configuration matérielle d'un réseau

Réseau filaire de 2 ordinateurs : 2 cartes réseau + 1 câble RJ45 croisé
À partir de 3 ordinateurs : hub ou switch + cartes réseau + câbles RJ45 classiques (non croisés)
Hub : boîtier de répartition reliant plusieurs machines en un point (structure en étoile) ; diffuse à toutes les machines
Switch : établit une liaison par aiguillage vers la machine de destination uniquement

Configuration sans fil

2 ordinateurs : un adaptateur WiFi chacun, en respectant la zone de couverture
À partir de 3 : un point d'accès + adaptateurs WiFi
Point d'accès : donne accès au réseau filaire aux stations équipées de cartes WiFi
Plusieurs points d'accès → zone de couverture élargie (roaming) ; on peut connecter réseaux filaires et sans fil

Séquence 2 — Objectifs

Appréhender la notion de système d'exploitation réseau
Gérer les utilisateurs dans un réseau local
Explorer les postes d'un groupe dans un réseau local
Partager les ressources matérielles et logicielles dans un réseau local

Séquence 2 — Pré-requis

Savoir utiliser les fonctions de base de Windows
Configuration matérielle d'un réseau

Système d'exploitation réseau

Gère l'allocation et l'utilisation des ressources, coordonne les interactions utilisateur–programmes
Fonctions : contrôle d'accès des utilisateurs (créer/gérer comptes, définir permissions : lire, enregistrer, supprimer, exécuter), partage des ressources (répertoires, fichiers, périphériques), surveillance (performances, sécurité)
Exemples de SE réseau spécialisés : Windows Server 2003, Linux
La gestion du serveur revient à l'Administrateur de réseau

Comptes utilisateurs

Compte Administrateur : tous les droits d'accès au système ; requis pour ajouter un ordinateur au réseau
Compte Limité : ne peut pas modifier les paramètres ni installer logiciel/matériel, mais peut utiliser les programmes installés

Ajouter / configurer un poste au réseau local

Démarrer → Favoris réseau → Créer un réseau domestique ou un réseau de petite entreprise → suivre l'Assistant Configuration réseau
Donner une description et un nom au poste (identifiant sur le réseau)
Nom du groupe de travail : identique pour tous les postes
Renommer un poste : Propriétés → onglet « Nom de l'ordinateur » → Modifier → vérifier le groupe de travail → OK
Les postes doivent avoir des noms significatifs et uniques

Explorer les postes du réseau

Lancer l'explorateur Windows → développer Favoris réseau → choisir son groupe ; ou ouvrir Favoris réseau → « Voir les ordinateurs du groupe de travail »
Un poste éteint n'apparaît pas parmi les membres du réseau

Partage des ressources — imprimante

Imprimante partagée : utilisable par tous les postes, branchée à l'un d'eux
Partager : vérifier la connectivité → se mettre sur le PC partageant → Démarrer/Panneau de configuration → Imprimantes et télécopieurs → « Partager cette imprimante » → onglet Partage → OK
Installer sur les autres postes : Ajouter une imprimante → Une imprimante réseau → rechercher/sélectionner → Terminer
Il existe des imprimantes réseau autonomes (propre câble), non installées sur un ordinateur mais plus coûteuses

Partage des ressources — dossier

Sélectionner le dossier → clic droit → « Partage et sécurité » → onglet Partage → cocher « Partager ce dossier sur le réseau » → cocher « Autoriser les utilisateurs réseau à modifier mes fichiers » → OK
Pour voir les utilisateurs connectés : Poste de travail → Favoris réseau → « Voir les ordinateurs du groupe de travail »


UNITÉ 2 : Échange d'informations
Compétence et prolongements de l'unité

Compétence : échanger des informations via un réseau local
Prolongements : typologie de réseaux, réseaux LAN/MAN/WAN, Internet (informatique) ; enrichissement du vocabulaire (français)

Séquence 1 — Objectifs

Explorer les postes d'un réseau local
Partager une ressource
Envoyer un fichier d'un poste à un autre sans passer par les dossiers partagés
Communiquer instantanément

Séquence 1 — Pré-requis

Maîtriser l'environnement d'un système d'exploitation
Gérer fichiers et dossiers
Identifier un réseau local et ses principaux éléments

Communication entre utilisateurs d'un réseau local

Les utilisateurs peuvent communiquer (« chat ») sans connexion Internet ; conversation sécurisable ou non, enregistrable
Logiciels spécialisés : Net Support School (NSS), Virtual Network Computing (VNC), NetMeeting ; commande Windows « Net Send »
NetMeeting : logiciel gratuit de Microsoft, à installer sur chaque poste ; chaque machine doit avoir une adresse IP

Installation de NetMeeting

Démarrer → Exécuter → taper « conf » → suivre l'assistant
Saisir prénom/nom (l'adresse de messagerie n'est pas obligatoire) ; prénom et nom servent à identifier émetteurs/récepteurs dans le Chat, pas à appeler
Laisser décochées les cases du serveur d'annuaire
Cocher « Réseau local » comme vitesse de connexion
Créer les raccourcis (bureau, lancement rapide) ; régler les paramètres audio ; répéter sur chaque poste

Environnement NetMeeting

Lancer via l'icône du bureau (double-clic)
Boutons : Raccrocher, Effectuer un appel, Rechercher un correspondant dans un annuaire, Démarrer la vidéo, Ajuster le volume audio, Conversation/Chat, Tableau blanc, Partager un programme, Transférer les fichiers

Trouver l'adresse IP

Menu « ? » → « À propos de Windows NetMeeting » → la boîte affiche l'adresse IP du poste

Numéros abrégés (remplacer les IP par des noms)

Relever les adresses IP et noms des machines (tableau Nom/adresse IP)
Appel → Créer un numéro abrégé → saisir l'adresse IP dans Adresse → mode d'appel « Réseau » (au lieu d'Annuaire) → cocher « Ajouter à la liste des numéros abrégés »
Renommer les raccourcis du dossier « C:\Program Files\NetMeeting\Numérotation abrégée » avec les noms adéquats, puis recopier le dossier sur chaque poste
Permet de travailler en collaboration sans connaître les IP, via l'annuaire

Appeler un correspondant

Bouton « Rechercher un correspondant dans l'annuaire » → sélectionner « Numérotation rapide » → choisir le correspondant → Appeler
Le correspondant doit avoir NetMeeting ouvert en tâche de fond et Accepter l'appel (boutons Accepter/Ignorer)
L'émission de l'appel et son acceptation sont indispensables pour accéder aux services NetMeeting

Conversation (Chat)

Menu Outils → Conversation, ou bouton Chat
Zone Message : saisir le message ; zone « Envoyer à » : choisir un destinataire ou « Tout le monde dans Conversation »

Tableau partagé (tableau blanc)

Bouton tableau blanc : dessin auquel contribuent tous les utilisateurs
Outils : sélection, gomme, loupe, texte, surligneur, ligne