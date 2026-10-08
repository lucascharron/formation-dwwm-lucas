# Retour de ticket – Madame Roussel

## Partie A – Définitions

- **Internet :** Internet est un vaste réseau d’ordinateurs qui communiquent entre eux.  
  **Source :** https://developer.mozilla.org/fr/docs/Learn_web_development/Howto/Web_mechanics/How_does_the_Internet_work

- **Web :** Le Web est un système d’information permettant de consulter des pages reliées entre elles par des hyperliens, accessibles sur Internet à l’aide d’un navigateur comme Google Chrome ou Mozilla Firefox.  
  **Source :** https://fr.wikipedia.org/wiki/World_Wide_Web

- **Client :** Appareil ou logiciel qui demande des ressources à un serveur, par exemple un navigateur installé sur un ordinateur connecté à Internet.  
  **Source :** https://developer.mozilla.org/fr/docs/Learn_web_development/Getting_started/Web_standards/How_the_web_works

- **Serveur :** Machine ou logiciel qui héberge des pages, des sites ou des applications et répond aux demandes des clients.  
  **Source :** https://developer.mozilla.org/fr/docs/Learn_web_development/Getting_started/Web_standards/How_the_web_works

- **Navigateur :** Logiciel installé sur un appareil permettant de consulter des sites web.  
  **Source :** https://www.firefox.com/fr/more/what-is-a-browser/

- **Nom de domaine :** Adresse facile à mémoriser permettant de retrouver un site ou un service sur Internet.  
  **Source :** https://www.afnic.fr/noms-de-domaine/tout-savoir/

- **Hébergement :** Service mettant à disposition un espace et des ressources pour stocker et rendre accessibles les fichiers d’un site web.  
  **Source :** https://www.net-concept.fr/actualites/quest-ce-que-l-hebergement-dun-site-web/

- **DNS :** Le *Domain Name System* est un système qui permet notamment de retrouver l’adresse IP associée à un nom de domaine.  
  **Source :** https://developer.mozilla.org/fr/docs/Learn_web_development/Getting_started/Web_standards/How_the_web_works

- **URL :** Une *Uniform Resource Locator* est l’adresse d’une ressource sur le Web, par exemple https://www.google.com.  
  **Source :** https://www.numacom.fr/blog/qu-est-ce-qu-une-url-definition-et-fonctionnement

- **HTTP :** *HyperText Transfer Protocol*, protocole de communication utilisé pour échanger des ressources entre un client et un serveur.  
  **Source :** https://www.urbilog.com/lexique-experts/http

- **HTTPS :** Version sécurisée de HTTP, qui chiffre les échanges entre le navigateur et le site web.  
  **Source :** https://www.nameshield.com/ressources/lexique/protocole-https/

- **Requête :** Demande envoyée par un client à un serveur pour obtenir une ressource ou transmettre des données.  
  **Source :** https://blog.hubspot.fr/website/reduire-nombre-requetes-http

- **Réponse :** Message envoyé par un serveur à un client après réception d’une requête HTTP.  
  **Source :** https://brightdata.fr/glossary/http-response

- **Code de statut :** Code à trois chiffres envoyé par un serveur pour indiquer le résultat d’une requête. Par exemple, **404** signifie que la ressource demandée est introuvable.  
  **Source :** https://developer.mozilla.org/fr/docs/Web/HTTP/Reference/Status

- **API :** Interface de programmation permettant à des applications ou systèmes de communiquer et d’échanger des données.  
  **Source :** https://www.cnil.fr/fr/definition/interface-de-programmation-dapplication-api

## Partie B – Adresses et extraits

### Adresse 1 – La boutique

https://fleurs-roussel.fr/boutique/bouquets?couleur=rouge&tri=prix

### Adresse 2 – Le blog

Le blog contient un formulaire de commentaires.

http://blog.fleurs-roussel.fr/2026/livraison-express

### Adresse 3 – Le service météo

https://api.meteo-service.fr/v1/previsions?ville=bordeaux&jours=3

### Tableau explicatif

| Élément | Définition |
|---|---|
| Protocole | Définit comment le navigateur communique avec le serveur. |
| Extension | Indique la catégorie ou parfois le pays associé au domaine. |
| Sous-domaine | Permet d’identifier une section ou un service du domaine. |
| Chemin | Indique la ressource ou la page demandée sur le site. |
| Nom de domaine | Nom permettant d’identifier le site web. |
| Paramètres | Transmettent des informations supplémentaires au serveur. |

## Partie C – Schéma du trajet

*Emplacement réservé au schéma du trajet d’une page web.*

<!-- Insérer ici le chemin de l’image : ![Schéma du trajet](images/schema-trajet.png) -->

## Partie D – Classement des huit extraits

### HTML

**Extraits :** 1, 4 et 7.

Ces extraits sont du HTML car ils utilisent des balises délimitées par des chevrons (`<` et `>`).

### CSS

**Extraits :** 3 et 6.

Ces extraits sont du CSS car ils sont composés de propriétés comme `color`, `gap` et `font-size`, associées à des valeurs comme `#c0392b`, `1rem` ou `1.25rem`, séparées par deux-points (`:`).

### JavaScript

**Extraits :** 2, 5 et 8.

Ces extraits sont du JavaScript car ils contiennent notamment des mots-clés ou éléments de syntaxe comme `let`, `function` ou `click`.

## Partie E – Réponse à la cliente

### Avant de répondre

Si la cliente décide de ne pas renouveler son nom de domaine, son site et les adresses e-mail liées à ce domaine risquent de ne plus être accessibles. À terme, elle peut perdre le droit d’utiliser ce nom de domaine.

### Réponse pour la cliente

Bonjour Madame,

Voici les réponses à vos questions.

Concernant l’erreur 404, cela signifie que le serveur ne trouve pas le fichier correspondant à votre page « Livraison ». Le fichier a peut-être été déplacé, renommé ou supprimé.

Dans les deux premiers cas, il faut vérifier que le fichier est bien placé au bon endroit et qu’il porte le bon nom. S’il a été supprimé et qu’aucune sauvegarde n’est disponible, il faudra faire recréer la page « Livraison » par un développeur.

Concernant la mention « Non sécurisé » que vous voyez sur votre blog, cela signifie que votre site utilise le protocole HTTP et non HTTPS. La principale différence est que le HTTPS permet de sécuriser et de chiffrer les échanges de données entre le site et ses visiteurs.

Avec un site en HTTP, certaines informations échangées peuvent être interceptées par un tiers. Je vous conseille donc de passer votre blog en HTTPS afin de mieux sécuriser les échanges et de rassurer vos visiteurs.

Enfin, le nom de domaine correspond à l’adresse et à l’identité de votre site web, tandis que l’hébergement correspond à l’espace dans lequel sont stockés les fichiers de votre site.

Il est important de conserver et de renouveler les deux. Si le nom de domaine n’est pas renouvelé, vous risquez de perdre l’utilisation de cette adresse. Si l’hébergement n’est pas renouvelé, le site ne sera plus accessible en ligne.