# Mise en route — Vous n'êtes plus seuls

Prototype expérimental destiné aux élus locaux. La base est limitée à quelques pages officielles : elle ne couvre pas encore tout le droit public, n'intègre pas les versions des codes ni une vérification exhaustive des références. Ne pas utiliser les réponses comme seul fondement d'une décision. Les guides doivent être confrontés aux textes en vigueur et aux actes locaux.

## Lancer avec Streamlit Cloud

1. Créer une application depuis ce dépôt, branche main, fichier `app.py`.
2. Dans les paramètres Secrets de Streamlit Cloud, ajouter `OPENAI_API_KEY = "votre clé"`. Ne jamais placer cette clé dans le dépôt public. Un compte et une facturation auprès du fournisseur peuvent être nécessaires.
3. Déployer. L'URL GitHub Pages ne permet pas d'exécuter l'application Python ; Streamlit fournit sa propre adresse.

La conversation reste dans la session Streamlit active : elle peut disparaître au rechargement ou à la fin de session et n'est pas une mémoire durable. Les questions sont envoyées au fournisseur d'IA. Ne pas saisir de données personnelles ou confidentielles avant d'avoir défini les conditions de traitement. La récupération des sources peut échouer ou ne pas trouver une réponse ; dans ce cas le prototype s'abstient. La présence d'extraits ne garantit pas une réponse exacte : une validation humaine et des tests juridiques restent nécessaires.

Prochaines étapes : intégrer une recherche juridique sur les textes versionnés, une base documentaire vérifiée, des tests avec réponses de référence, les conditions de confidentialité, et la photo de fond fournie par l'utilisateur.
