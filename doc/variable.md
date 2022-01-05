# Variables

## Bâtiment

### Ancienneté du bâtiment

Variable : **age**
Type : **integer**

### BBC

Le bâtiment atteint une performance après travaux de niveau BBC - Etiquette énergie A ou B

Variable : **bbc**
Type: **boolean**

### Energie de chauffage principale

Variable : **energieChauffage**
Type : **string**

| Intitulé | Description |
|:--------:|-------------|
| electricite | Electricité (hors pompe à chaleur) |
| gaz_naturel | Gaz naturel |
| fioul | Fioul |
| pac | Pompe à chaleur |
| bois | Bois |
| gpl | GPL |
| charbon | Charbon |

### Etiquette énergie du bâtiment

Variable : **etiquetteEnergie**
Type : **string**

| Intitulé | Description |
|:--------:|-------------|
| A | Etiquette énergie A |
| B | Etiquette énergie B |
| C | Etiquette énergie C |
| D | Etiquette énergie D |
| E | Etiquette énergie E |
| F | Etiquette énergie F |
| G | Etiquette énergie G |

### Surface habitable du bâtiment

Variable : **surface**
Type : **float**

### Type de bâtiment

Variable : **type**
Type : **string**

| Intitulé | Description |
|:--------:|-------------|
| maison | Maison individuelle|
| appartement | Appartement individuel |
| immeuble | Immeuble résidentiel collectif |

### Zone climatique

Variable : **zoneClimatique**
Type : **string**

| Intitulé | Description |
|:--------:|-------------|
| H1 | Zone climatique H1 |
| H2 | Zone climatique H2 |
| H3 | Zone climatique H3 |

## Bénéficiaire

### Bénéfice d'un PTZ

Le demandeur a bénéficié d'un PTZ dans les 5 ans précédent a demande

Variable : **ptz**
Type : **boolean**

### Statut

Variable : **statut**
Type : **string**

| Intitulé | Description |
|:--------:|-------------|
| proprietaire_occupant | Propriétaire occupant |
| proprietaire_bailleur | Propriétaire bailleur |
| proprietaire_occupant_sci | Propriétaire occupant membre d'une SCI |
| proprietaire_bailleur_sci | Propriétaire bailleur membre d'une SCI |
| locataire | Locataire |
| occupant_gratuit | Occupant à titre gratuit |

### Tranche de revenus

Variable : **tranche**
Type : **string**

| Intitulé | Description |
|:--------:|-------------|
| tres_modeste | Catégorie de ressource **très modeste** |
| modeste | Catégorie de ressource **modeste** |
| intermediaire | Catégorie de ressource **intermédiaire** |
| superieur | Catégorie de ressource **supérieure** |

## Actions

### Coût total HT

Variable : **coutTotalHT**
Type : **float**

### Coût total TTC

Variable : **coutTotalTTC**
Type : **float**

### Coefficient de performance saisonnier - SCOP

Variable : **scop**
Type : **float**

### Efficacité énergétique saisonnière - Etas

Variable : **etas**
Type : **float**

### Montant des aides hors CEE

Variable : **montantAides**
Type : **float**

### Montant des aides CEE

Variable : **montantCee**
Type : **float**

### Quantité

Variable : **quantite**
Type : **float**

### Surface chauffée

Surface chaufée par l'équipement installé

Variable : **surfaceChauffee**
Type : **float**

### Valorisation CEE classique

Variable : **valorisationCeeClassique**
Type : **float**

### Valorisation CEE précarité

Variable : **valorisationCeePrecarite**
Type : **float**
