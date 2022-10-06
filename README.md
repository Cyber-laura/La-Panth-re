# La-Panthère
**Contexte**

La panthère est une agence de web design basée à Lyon. L’activité de l’entreprise a bien démarré mais aujourd’hui, elle est en perte de vitesse. La fondatrice de l’entreprise, Sophie, cherche une solution pour faire repartir l’activité. La concurrence est rude et le site apparaît qu'en deuxième page des moteurs de recherche. Sophie organise une réunion pour préciser le périmètre de la mission. 

# Mission
**1.** Analyser l'état actuel de SEO du site fourni.

**2.** Améliorer le SEO du site en choissisant 10 recommandations à appliquer.

**3.** Comparer les résultats. 

# Analyse de l'état actuel
Pour faire l'audit SEO On-Page du site La Panthère, j'ai choisi d'utiliser différents outils comme ; Ligthouse, Wave, aXe, Heading Map, Search consol, Answer The Public, et l'inspecteur. 

● L'attribut de la balise lang dans le fichier index.html et page2.html est incorrect, cela pose problème pour les lecteurs d'écrans ou les traducteurs de page. (choix n°1) 

● La balise title et description doivent contenir un mot-clé visé et donner envie au visiteur. (choix n°2)

● Les mots-clés sont répétitifs et non pertinents, ils doivent être appropriés au contexte. L'accumulation a des effets négatifs sur l'expérience utilisateur et peut nuire au classement du site. (choix n°3)

● Les balises <script> chargent au moment de l'ouverture du site, ce qui demande un temps de chargement plus long, de plus le site n'a pas besoin de certains scripts inutilisés dans le site. (choix n°4)

● La balise "robots.txt" n'est pas présente dans le code source, Robots permet d'indexer la page sur les moteurs de recherche et suivre les liens présents sur celle-ci.

● Problème d'architecture : La structure du code source est basée sur des balises « div » hors le HTML sémantique améliore le SEO et l'accessibilité pour un utilisateur.

● Le nom de la page 2 n'est pas approprié, il s'agit d'un point ou « page2 », le nom doit être unique et descriptif, 70 caractères maximum selon le contenu.

● Le poids des fichiers images retarde le chargement du site, les éléments d'images ne possèdent pas de structure de taille, ils seront alors affiché en utilisant leur taille intrinsèque ce qui rend le chargement plus long. Pour un chargement optimisé le poids idéal est de moins 100ko.

● Certaines rubriques sont vides, comme le menu élément « li » ce qui perturbe les utilisateurs de lecteur d’écrans.

● La hiérarchie des niveaux de titre n'est pas respectée, ce qui perturbe les TA. (choix n°5)

● Les images de texte peuvent poser un problème si un utilisateur souhaite modifier les caractères. C'est également un manque à gagner pour le SEO. (choix n°6)
 
● Le site intègre des images/icônes sans texte alternatif, ce qui empêche de définir une légende non visible associée à l’élément dont le sens est transmis par le visuel. (choix n°7)

● Certaines ancres sont vides, par exemple, aucun des liens ne renvoie vers une page de réseaux sociaux. (choix n°8)

● La typographie de certains textes est illisible, elle doit être accessible pour tous, il existe deux concepts à respecter, la lisibilité et la différentiabilité.

● La navigation alternative avec un clavier n'est pas optimisée, l'indicateur de focus est invisible. Toutes les fonctions ne sont alors pas accessibles au clavier, de plus il manque des liens d'accès direct au contenu.

● Le code source comporte des erreurs au validateur HTML et CSS.

● L'ordre programmatique de la page 2 ne correspond pas a l'ordre visuel. Il important de fournir une présentation alternative au utilisateur tout en préservant l'ordre de lecture nécessaire pour en comprendre le sens.

● Les liens du menu dans la page 2 n’apparaissent pas dans le même ordre sur les différentes pages. Il est important d'assurer une identification cohérente pour que les personnes qui utilisent un lecteur d’écran s’appuient sur leur familiarité. 

● Plusieurs éléments ont un contraste de couleurs insuffisantes dont les titres ainsi que les paragraphes doivent être visible pour les utilisateurs. Le contraste attendu est de 4.5:1(texte normal) 3:1(texte 18pt+) ou gras (14pt+) (choix n°9)

● Le formulaire ne comporte pas d'attribut d'auto-complétion, il est important de faciliter le remplissage des formulaires, en particulier pour les personnes souffrant de troubles cognitifs. (choix n°10)

# Recommandations

● Recommandation n°1 : Langue de la page – Accessibilité

● Recommandation n°2 : Page intitulée – SEO / Performance

● Recommandation n°3 : Mots-clés répétitifs et non pertinent – SEO / Performance

● Recommandation n°4 : Les balises <script> - Performance

● Recommandation n°5: Niveau de titre – Performance / Accessibilité

● Recommandation n°6 : Image de texte – Accessibilité

● Recommandation n°7: Nom, Rôle, Valeur, Aria-label – Accessibilité

● Recommandation n°8: Objectif du lien – Accessibilité

● Recommandation n°9 : Contraste non textuel et minimum – Performance / Accesibilité / SEO

● Recommandation n°10 : Formulaire – Accessibilité / SEO / Performance

# Score page Accueil et Contact avant optimisation 
**Page Accueil**

● Performance: 55

● Accessibilité: 84

● Bonnes pratiques: 92 

● SEO: 78

**Page Contact**

● Performance: 71

● Accessibilité: 76

● Bonnes pratiques: 92

● SEO: 72

# Score page Accueil et Contact après optimisation 
**Page Accueil**

● Performance: 75 (+20)

● Accessibilité: 100 (+16)

● Bonnes pratiques: 92 

● SEO: 100 (+22)

**Page Contact**

● Performance: 83 (+12)

● Accessibilité: 96 (+20)

● Bonnes pratiques: 92 

● SEO: 92 (+20)

# Modifications incluses 
Certaines recommandations, en plus de celle choisie, ont été appliqué de manière à ce que le code passe au validateur HTML et CSS.

● Le contenu de la balise « li » du menu à été complété. 

● La taille des images a été optimisée.

● Les valeurs de padding-left/right ont été modifiés.

● La caractéristique max-device-width est dépréciée, nous l'avons remplacé par max-width.

● Tous les éléments sont focusables.

● Suppression des fichiers inutilisés tels que des images et le fichier gmap.js
