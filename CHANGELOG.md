# Notes de version

## 3 novembre 2026

### Sauvegarde et récupération
- Une copie de secours locale est conservée automatiquement au fil des modifications.
- L’application signale clairement si l’enregistrement ou la mise à jour de la copie échoue.
- Une copie de secours valide peut être restaurée depuis le menu **Sauvegarde**.

### Expirations et stocks restants
- Le stock créé après l’expiration conserve un récapitulatif de l’annonce d’origine : quantités listée, vendue et remise en stock, prix et taxe déjà payée.
- La taxe déjà payée sur l’annonce expirée est affichée comme information et n’est pas recalculée sur le nouveau stock.

### Corrections et calculs
- Les champs d’une opération restent modifiables pour corriger une erreur.
- Les quantités vendues, prix de vente et taxes des annonces clôturées peuvent être corrigés dans leur historique.
- Le prix minimum de vente tient compte du taux de taxe estimé ou du montant de taxe saisi comme réellement payé.
- La taxe estimée se recalcule quand le prix de vente change ; une taxe réelle saisie manuellement reste inchangée.

### Catalogue et confort d’utilisation
- Le catalogue propose les noms français et anglais des items connus et regroupe les variantes redondantes.
- Le sélecteur de grande liste utilise une recherche et limite le nombre de résultats affichés à la fois pour rester réactif.

### Données
- Les données personnelles et les opérations restent stockées localement dans le navigateur ; cette publication ne contient pas la sauvegarde personnelle du propriétaire.
