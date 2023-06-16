# Scraping_Github
Ce code est un script Python qui utilise l'API GitHub pour collecter des informations sur les dépôts créés entre une date de début et une date de fin spécifiées par l'utilisateur. Il récupère les détails tels que le nom du dépôt, l'URL, la description, le nombre d'étoiles, la date de création, le langage utilisé, le nombre de forks, le nombre de watchers, le nombre d'issues ouvertes et le nom du propriétaire. Le script utilise une approche de pagination pour récupérer un certain nombre de dépôts par jour, conformément à la valeur fournie par l'utilisateur. Il gère également les erreurs de requête en cas de dépassement des limites de l'API. Une fois les données collectées, le script les écrit dans un fichier CSV spécifié par l'utilisateur, avec des en-têtes correspondant aux informations extraites. En fin d'exécution, le script affiche un message indiquant que les dépôts ont été collectés avec succès et enregistrés dans le fichier CSV.
## Instructions de configuration
Avant d'utiliser ce projet, assurez-vous de remplacer les éléments suivants dans le code :
1. **GitHub username**: Remplacer `'Yours'` par votre nom d'utilisateur GitHub.
2. **GitHub access token**: Replace `'Yours'` par votre jeton d'accès GitHub.

