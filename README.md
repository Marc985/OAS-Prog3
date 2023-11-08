# library-management
API that manages library.

You can check the link below to test the API specification

[TD2](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/Marc985/OAS-Prog3/oas-td2-std22095/docs/api.yml)



## Response for all quesetion
    2-b-i:UpdateBook possede uniquement l'identifiant createUpdate mais pas authorName et bookName parce c'est l'identifiant qui permet de reconnaitre un author et un book 
    ii:updateBookAuthor devrait avoir les propriétés de crupdate et author lors de la reponse

        3-a: Les paginations sont necessaire pour gerer des données  volumineuse

    4-a:oui on peut gerer la pagination à travers l'en tete des requetes car les en-tete offres une flexibilité pour ajouter  des informations supplementaire
     -b:on doit pas gerer la pagination à travers l'en-tete pour plus de visibilité