##Stationnement sur rue

Traitement des données ouvertes du [Portail données ouvertes][lien_portail] de la ville de Montréal.

L'objectif de ce dépôt est de partager avec la communauté des données ouvertes de Montréal le travail effectué sur les données relatives au **stationnement sur rue**.

Les jeux de données regroupés ici sont:

* [Stationnement sur rue - Signalisation - Courant][lien_portail_signalisation]
* [Géobase][lien_portail_geobase]
* [Arrondissements de la Ville de Montréal][lien_portail_arrondissements]
* [Stationnements gratuits (déneigement)][lien_portail_deneigement]

##Structure

Le dépôt contient 3 dossiers:

1. **Download:** ce sont les mêmes fichiers que l'on peut télécharger sur le [Portail données ouvertes][lien_portail].
2. **Extract:** les mêmes fichiers que le premier dossier, avec l'extraction des fichiers ZIP. Le but étant de simplifier la navigation des données avec l'interface de GitHub.
3. **Cleanup:** J'ai commencé à regrouper ici mon traitement (ou nettoyage) des données. Exemples: UTF-8 au lieu de ISO, CSV séparés par des **","** au lieu des **"|"**, [images PNG][lien_depot_imagerie] au lieu des GIF, etc.

Je vous invite particulièrement à consulter la [traduction manuelle du règlement du stationnement][lien_depot_reglement], avec ses 1910 lignes!

##Comment contribuer

Je vous invite à *forker* le projet sur GitHub et de soumettre votre contribution avec un *pull request*.

##Credits

* Dépôt maintenu par [Mudar Noufal][lien_mudar_ca]  &lt;<mn@mudar.ca>&gt;
* Un grand merci à l'équipe des données ouvertes de la ville de Montréal: Diane Mercier, Luc Lévesque, André Jr Clément, Michel Lanthier, Service de la concertation des arrondissements et des ressources matérielles.

##[Licence ouverte Creative Commons CC-BY 4.0][lien_portail_licence]

    Using Creative Commons Public Licenses

    Creative Commons public licenses provide a standard set of terms and conditions that creators and other rights holders may use to share original works of authorship and other material subject to copyright and certain other rights specified in the public license below. The following considerations are for informational purposes only, are not exhaustive, and do not form part of our licenses.

    Considerations for licensors: Our public licenses are intended for use by those authorized to give the public permission to use material in ways otherwise restricted by copyright and certain other rights. Our licenses are irrevocable. Licensors should read and understand the terms and conditions of the license they choose before applying it. Licensors should also secure all rights necessary before applying our licenses so that the public can reuse the material as expected. Licensors should clearly mark any material not subject to the license. This includes other CC-licensed material, or material used under an exception or limitation to copyright. More considerations for licensors.

    Considerations for the public: By using one of our public licenses, a licensor grants the public permission to use the licensed material under specified terms and conditions. If the licensor’s permission is not necessary for any reason–for example, because of any applicable exception or limitation to copyright–then that use is not regulated by the license. Our licenses grant only permissions under copyright and certain other rights that a licensor has authority to grant. Use of the licensed material may still be restricted for other reasons, including because others have copyright or other rights in the material. A licensor may make special requests, such as asking that all changes be marked or described. Although not required by our licenses, you are encouraged to respect those requests where reasonable. More considerations for the public.


[lien_portail]: http://donnees.ville.montreal.qc.ca/
[lien_portail_signalisation]: http://donnees.ville.montreal.qc.ca/dataset/stationnement-sur-rue-signalisation-courant
[lien_portail_geobase]: http://donnees.ville.montreal.qc.ca/dataset/geobase
[lien_portail_deneigement]: http://donnees.ville.montreal.qc.ca/dataset/stationnements-gratuits
[lien_portail_arrondissements]: http://donnees.ville.montreal.qc.ca/dataset/polygones-arrondissements
[lien_portail_licence]: http://donnees.ville.montreal.qc.ca/licence-2014/
[lien_mudar_ca]: http://www.mudar.ca/
[lien_depot_imagerie]: 03_cleanup/Imagerie des panneaux/png
[lien_depot_reglement]: 03_cleanup/Signalisation-description-panneau/panneaux_reglement_2012.csv