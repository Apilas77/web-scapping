# Cultura Scraping

## Sujet
Parcourir les promotions du site [Cultura](https://www.cultura.com/boutiques/des-prix-des-promos.html).

Pour chaque promotion de la page :
- Cliquer sur le lien de la promotion
- Récupération des éléments *(maximum 100)*
    - Nom
    - Marque
    - Note *(si existante)*
    - Stock
    - Prix avant promotion *(si existe)*
    - Prix après promotion
- Retour à la page des promotions pour le prochain lien

Remarque : 
- Présence d'un scroll infini
- Parfois la présence d'un bouton `Voir toutes les promotions`