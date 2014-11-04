##Stationnement sur rue

Traitement des données ouvertes du [Portail données ouvertes][lien_portail_licence] de la ville de Montréal.

L'objectif de ce dépôt est de partager avec la communauté des données ouvertes de Montréal le travail effectué sur les données relatives au **stationnement sur rue**.

Les jeux de données regroupés ici sont:

* [Stationnement sur rue - Signalisation - Courant][lien_portail_signalisation]
* [Géobase][lien_portail_geobase]
* [Arrondissements de la Ville de Montréal][lien_portail_arrondissements]
* [Stationnements gratuits (déneigement)][lien_portail_deneigement]

##Structure

Ce dépôt contient 3 dossiers:

1. [Download][lien_depot_download]: ce sont les mêmes fichiers que l'on peut télécharger sur le [Portail données ouvertes][lien_portail].
2. [Extract][lien_depot_extract]: les mêmes fichiers que le premier dossier, avec l'extraction des fichiers ZIP. Le but étant de simplifier la navigation des données avec l'interface de GitHub.
3. [Cleanup][lien_depot_cleanup]: J'ai commencé à regrouper ici mon traitement (ou nettoyage) des données. Exemples: UTF-8 au lieu de ISO, CSV séparés par des **","** au lieu des **"|"**, [images PNG][lien_depot_imagerie] au lieu des GIF, et surtout la [traduction manuelle du règlement du stationnement][lien_depot_reglement].

##Comment contribuer

Je vous invite à *forker* le projet sur GitHub et de soumettre votre contribution avec un *pull request*.

Plusieurs projets exploitent ces mêmes données, les grands esprits se rencontrent! Ce serait dans l'intérêt de toute la communauté de collaborer sur le travail initial de nettoyage et restructuration de ces données ouvertes:
 
* Pour la ville: un meilleur processus d'export des données.
* Pour les utilisateurs Montréalais: plus d'applications, de meilleure qualité.
* Pour les développeurs: des données de meilleure qualité et plus facilement exploitables, des mises à jour compatibles.

##Projets actuels sur le stationnement

Voici une liste de quelques projets qui proposent (ou vont proposer) des solutions pour le stationnement à Montréal:

* [Montreal Parking](https://play.google.com/store/apps/details?id=com.MichaelGolfi.MontrealParking) par Michael Golfi.
* [Park Catcher Montreal](https://github.com/mudar/ParkCatcher) par Mudar Noufal.
* [Free Parking Montreal](http://www.appcto.com/?page=projects&id=1) par Azael Garcia Blancas.
* [PARXi Montréal](http://parxiapp.com/) par Christian Pocetti.
* [Parkings Gratuits Montréal](https://play.google.com/store/apps/details?id=fr.florentlamoureux.parkingmontrealdeneigement) par Florent Lamoureux.
* [Simple P](http://p.ruemtl.com) par Stationnement sur rue inc.
* [P$ Mobile Service](https://play.google.com/store/apps/details?id=tc.tc.scsm.phonegap) par Stationnement de Montréal.
* [Info neige](http://www.heritagesoftware.ca/portfolio-item/defi-info-neige-2014/) par Les Logiciels Heritage Inc.

Certains sont gratuits, d'autres couvrent le stationnement payant ou hors-rue. Personnellement, je considère que la valeur ajoutée de ces projets n'est pas dans l'analyse des données, mais dans les fonctionnalités spécifiques à chaque application. C'est pour cette raison que je propose une collaboration entre collègues plutôt qu'une vaine concurrence qui consiste à laisser les obstacles déjà franchis dans le chemin des autres développeurs.

##Crédits

* Dépôt maintenu par [Mudar Noufal][lien_github_mudar]  &lt;<mn@mudar.ca>&gt;
* Un grand merci à l'équipe des données ouvertes de la ville de Montréal: Diane Mercier, Sylvain S. Hébert, Luc Lévesque, André Jr Clément, Michel Lanthier, Service de la concertation des arrondissements et des ressources matérielles, Bureau de la ville intelligente et numérique.

##Licence ouverte Creative Commons CC-BY 4.0

Extrait de la [licence ouverte][lien_portail_licence] du [Portail données][lien_portail] ouvertes de la Ville de Montréal:

> ###Libres de réutilisation
> Vous êtes autorisé à :
> 
> * **Partager** — copier, distribuer et communiquer les données et les contenus par tous moyens et sous tous formats
> * **Adapter** — remixer, transformer et créer à partir des données et des contenus pour toute utilisation, y compris commerciale.
> 
> La Ville de Montréal ne peux retirer les autorisations concédées par la licence tant que vous appliquez les termes de cette licence.
> 
> ###Paternité – Ville de Montréal
> Selon les conditions suivantes :
> 
> * **Attribution de paternité** — Vous devez **créditer** les données et les contenus, intégrer un lien vers la licence et **indiquer** si des modifications ont été effectuées aux données et aux contenus. Vous devez indiquer ces informations par tous les moyens possibles, par exemple un hyperlien, mais vous ne pouvez pas suggérer que la Ville de Montréal vous soutient ou soutient la façon dont vous avez utilisé ses données et ses contenus.
> * **Pas de restrictions supplémentaires** — Vous n’êtes pas autorisé à appliquer des conditions légales ou des mesures techniques qui restreindraient légalement autrui à utiliser les données et les contenus dans les conditions décrites par la licence.


    Creative Commons Corporation ("Creative Commons") is not a law firm and
    does not provide legal services or legal advice. Distribution of
    Creative Commons public licenses does not create a lawyer-client or
    other relationship. Creative Commons makes its licenses and related
    information available on an "as-is" basis. Creative Commons gives no
    warranties regarding its licenses, any material licensed under their
    terms and conditions, or any related information. Creative Commons
    disclaims all liability for damages resulting from their use to the
    fullest extent possible.

    Using Creative Commons Public Licenses

    Creative Commons public licenses provide a standard set of terms and
    conditions that creators and other rights holders may use to share
    original works of authorship and other material subject to copyright
    and certain other rights specified in the public license below. The
    following considerations are for informational purposes only, are not
    exhaustive, and do not form part of our licenses.

    Considerations for licensors: Our public licenses are
    intended for use by those authorized to give the public
    permission to use material in ways otherwise restricted by
    copyright and certain other rights. Our licenses are
    irrevocable. Licensors should read and understand the terms
    and conditions of the license they choose before applying it.
    Licensors should also secure all rights necessary before
    applying our licenses so that the public can reuse the
    material as expected. Licensors should clearly mark any
    material not subject to the license. This includes other CC-
    licensed material, or material used under an exception or
    limitation to copyright. More considerations for licensors:
    wiki.creativecommons.org/Considerations_for_licensors

    Considerations for the public: By using one of our public
    licenses, a licensor grants the public permission to use the
    licensed material under specified terms and conditions. If
    the licensor's permission is not necessary for any reason--for
    example, because of any applicable exception or limitation to
    copyright--then that use is not regulated by the license. Our
    licenses grant only permissions under copyright and certain
    other rights that a licensor has authority to grant. Use of
    the licensed material may still be restricted for other
    reasons, including because others have copyright or other
    rights in the material. A licensor may make special requests,
    such as asking that all changes be marked or described.
    Although not required by our licenses, you are encouraged to
    respect those requests where reasonable. More_considerations
    for the public: 
    wiki.creativecommons.org/Considerations_for_licensees

[lien_portail]: http://donnees.ville.montreal.qc.ca/
[lien_portail_signalisation]: http://donnees.ville.montreal.qc.ca/dataset/stationnement-sur-rue-signalisation-courant
[lien_portail_geobase]: http://donnees.ville.montreal.qc.ca/dataset/geobase
[lien_portail_deneigement]: http://donnees.ville.montreal.qc.ca/dataset/stationnements-gratuits
[lien_portail_arrondissements]: http://donnees.ville.montreal.qc.ca/dataset/polygones-arrondissements
[lien_portail_licence]: http://donnees.ville.montreal.qc.ca/licence-2014/
[lien_github_mudar]: https://github.com/mudar
[lien_depot_download]: https://github.com/mudar/StationnementSurRueMontreal/tree/master/01_download
[lien_depot_extract]: https://github.com/mudar/StationnementSurRueMontreal/tree/master/02_extract
[lien_depot_cleanup]: https://github.com/mudar/StationnementSurRueMontreal/tree/master/03_cleanup
[lien_depot_imagerie]: https://github.com/mudar/StationnementSurRueMontreal/tree/master/03_cleanup/Imagerie%20des%20panneaux/png
[lien_depot_reglement]: https://github.com/mudar/StationnementSurRueMontreal/tree/master/03_cleanup/Signalisation-description-panneau/panneaux_reglement_2012.csv
[projet_montrealparking]: https://play.google.com/store/apps/details?id=com.MichaelGolfi.MontrealParking
[projet_parkcatcher]: https://github.com/mudar/ParkCatcher
[projet_appcto]: http://www.appcto.com/?page=projects&id=1
[projet_parxi]: http://parxiapp.com/
[projet_parkingmontrealdeneigement]: https://play.google.com/store/apps/details?id=fr.florentlamoureux.parkingmontrealdeneigement
[projet_scsm]: https://play.google.com/store/apps/details?id=tc.tc.scsm.phonegap
[projet_infoneige]: http://www.heritagesoftware.ca/portfolio-item/defi-info-neige-2014/
