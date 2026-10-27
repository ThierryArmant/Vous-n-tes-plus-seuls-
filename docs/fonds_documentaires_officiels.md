# Fonds documentaires officiels — construction de la bibliothèque

Repérage du 27 octobre 2026. Ce document identifie des sources ; il ne prouve pas qu'elles sont importées, connectées ou testées dans l'application.

## LEGI : socle national

Source DILA : https://www.data.gouv.fr/datasets/legi-codes-lois-et-reglements-consolides

Fonds de textes consolidés : codes officiels, lois, ordonnances, décrets et sélection d'arrêtés, avec les versions modifiées, abrogées et en vigueur. Le fonds annonce l'exhaustivité des lois, décrets-lois, ordonnances et décrets depuis 1945, mais pas de tous les arrêtés ni de toutes les circulaires. L'index DILA https://echanges.dila.gouv.fr/OPENDATA/LEGI/ présente un stock et des mises à jour : ne pas supposer qu'un ancien stock suffit à être à jour, ni que chaque fichier soit un stock complet. Vérifier les fichiers et leur chronologie avant import.

Priorité : CGCT intégral, à l'article et à la version, y compris partie réglementaire ; puis autres codes et textes non codifiés pertinents. Indexer les identifiants officiels, numéros d'article, code ou texte d'origine, dates de début et de fin, état, structure, liens, textes liés et métadonnées de collecte. Préserver les versions historiques et signaler si les données datent. Vérifier les références avant publication d'une réponse.

## Jeu vectorisé de la DINUM

https://www.data.gouv.fr/datasets/legi-codes-lois-et-reglements-consolides-vectorises

Corpus structuré et vectorisé de textes consolidés décrit par son producteur comme adapté à la recherche sémantique. Données en format Parquet ; vérifier disponibilité effective, périmètre, date, champs, identifiants, modèle des vecteurs, mises à jour et limites avant adoption. Il ne remplace pas un contrôle du texte officiel ni une recherche historique correctement paramétrée.

## API Légifrance

https://www.data.gouv.fr/dataservices/legifrance

Accès gratuit après inscription sur PISTE, sous conditions et quotas. Étudier la recherche et la consultation datée pour compléter ou actualiser les données locales ; aucune clé n'est intégrée à ce dépôt public.

## Autres fonds

Circulaires et instructions : rechercher le fonds CIRCULAIRES et les bulletins officiels ministériels pertinents, sans les confondre avec LEGI. Jurisprudence : Légifrance et ArianeWeb ; guides et fiches : DGCL, DAJ, HATVP et autres organismes compétents. Actes locaux : statuts EPCI, délibérations et arrêtés de la collectivité fournis ou publiés, avec date et contexte. Établir les règles de conservation avant tout chargement de données personnelles.

## Validation attendue

Vérifier le nombre d'articles CGCT importés en comparant au sommaire officiel, la présence des parties législative et réglementaire, les versions et dates, l'accès aux articles cités, les renvois et les mises à jour ; tester des questions simples et complexes, des dates passées, les communes et EPCI, les textes abrogés et la panne de la source. Aucune couverture exhaustive ou fiabilité ne doit être annoncée avant mesure.

## Situation du prototype

Le prototype interroge actuellement un petit nombre de pages institutionnelles. Il n'interroge pas encore le fonds LEGI complet et n'est pas connecté à Albert. L'intégration, l'hébergement de l'index, le renouvellement et l'évaluation restent à construire.
