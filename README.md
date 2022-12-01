# Part des véhicules à faibles émissions dans le renouvellement d'un parc

Spécification du fichier d'échange pour les données de renouvellement du parc automobile et la part des véhicules à faibles émissions parmi ceux-ci.

Pour les sociétés de location de véhicules, de location-vente, de crédit-bail (leasing), les plateformes de livraison, ainsi que pour les centrales de réservation de taxis ou de VTC, il existe un schéma de données spécifique [sur cette page](https://schema.data.gouv.fr/etalab/schema-vehicules-faibles-emissions-renouvellement-parc-synthese/).


## Contexte

Dans le but de constituer un suivi national des renouvellements de flotte des acteurs publics et privés soumis aux obligations d'intégration de véhicules à faibles émissions dans ces renouvellements prévues par la loi du 24 décembre 2019 d'orientation des mobilités, ouvert et accessible à tous, les personnes mentionnées aux articles `L. 224-7` à `L. 224-10` du code de l'environnement doivent, au plus tard le 30 septembre de chaque année, publier sur la plateforme [data.gouv.fr](https://www.data.gouv.fr/fr/) les données statiques relatives aux renouvellements de flotte effectués l'année précédente conformément aux dispositions de l'arrêté du 29 décembre 2020 modifié.

## Documents de cadrage juridique

- [Décret n° 2020-1726 du 29 décembre 2020 relatif au suivi et à la publication du pourcentage de véhicules à faibles et à très faibles émissions parmi les véhicules ayant fait l’objet d’un renouvellement de parc conformément aux dispositions applicables à certaines personnes, pris pour l’application de l’article 79 de la loi no 2019-1428 du 24 décembre 2019 d’orientation des mobilités](https://www.legifrance.gouv.fr/jorf/id/JORFTEXT000042754268)
- [Arrêté du 29 décembre 2020 fixant les termes et modalités de publication du pourcentage de véhicules à faibles et à très faibles émissions parmi les véhicules intégrés dans un renouvellement de parc, modifié par l’arrêté du 28 avril 2021.](https://www.legifrance.gouv.fr/loda/id/JORFTEXT000042754492/2021-09-16/)

## Création d'un fichier de données conforme

Les données collectées doivent respecter un formalisme particulier (schéma de données) décrit dans la section documentation de cette [page](https://schema.data.gouv.fr/etalab/schema-vehicules-faibles-emissions-renouvellement-parc/latest/documentation.html).

Les données sont à remplir au format `CSV`, encodage `UTF-8`.

## Utilisation de notre outil d'aide à la saisie

Pour faciliter le remplissage des données, Etalab met à disposition un générateur `CSV` conforme au schéma de données, vous permettant de remplir les différents champs demandés. Cet outil vous permet de vous assurer que les données que vous remplissez sont au bon format et sont correctement référencées sur [data.gouv.fr](https://www.data.gouv.fr/fr/). Pour l'utiliser, rendez-vous sur [publier.etalab.studio](https://publier.etalab.studio/select?schema=etalab%2Fschema-vehicules-faibles-emissions-renouvellement-parc), vous pourrez alors publier votre fichier à partir : 
- d'un formulaire,
- d'un tableur,
- d'un fichier `csv` déjà existant.

Une fois vos données chargées ou remplies, un formulaire vous proposera de les publier sur [data.gouv.fr](https://www.data.gouv.fr/fr/).

Veuillez utiliser [publier.etalab.studio](https://publier.etalab.studio/select?schema=etalab%2Fschema-vehicules-faibles-emissions-renouvellement-parc) pour publier vos données afin qu'elles ne se soient pas dispersées dans [data.gouv.fr](https://www.data.gouv.fr/fr/).
