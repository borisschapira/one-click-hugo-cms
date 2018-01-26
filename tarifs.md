---
layout: default
title: Tarifs et réservation
i18n-key: booking
---
# Tarifs et réservation

## Nos tarifs hôtellerie <small>(prix <abbr title="Toutes Taxes Comprises">TTC</abbr>)</small>

<table>
<tbody><tr>
<th></th>
<th>Nuitée</th>

<th>Semaine</th>

<th>Mois</th>
</tr>
<tr>
<td>Chambre simple</td>
<td>18 €</td>
</tr>
<tr>
<td>Chambre double</td>
<td> 34 €</td>
</tr>
<tr>
<td>Chambre familiale (4 à 6 lits)</td>
<td>66 €</td>
</tr>
<tr>
<td>Le Cascadeur</td>
<td>38 €</td>
</tr>
<tr>
<td>Le Prédicateur</td>
<td>38 €</td>
</tr>
<tr>
<td>Les Capucines</td>
<td> </td>
<td>350 €</td>
<td>1 200 €</td>
</tr>
<tr>
<td>La familiale</td>
<td> </td>
<td>350 €</td>
<td>1 200 €</td>
</tr>
</tbody></table>

## Nos tarifs restauration <small>(prix <abbr title="Toutes Taxes Comprises">TTC</abbr>)</small>

<table>
<tbody><tr>
<th></th>
<th>Individuel</th>
<th>Groupe (> 20 pers)</th>
</tr>
<tr>
<td>Pension complète</td>
<td>€</td>
<td>€</td>
</tr>
<tr>
<td>Demi-pension</td>
<td> €</td>
<td>€</td>
</tr>
<tr>
<td>Petit-déjeuner</td>
<td> €</td>
<td>€</td>
</tr>
<tr>
<td>Déjeuner</td>
<td> €</td>
<td>€</td>
</tr>
<tr>
<td>Dîner</td>
<td> €</td>
<td>€</td>
</tr>
<tr>
<td>Collation</td>
<td> €</td>
<td>€</td>
</tr>
</tbody></table>

## Faire une demande de réservation

{% capture reassurance %}Nous vous répondrons au plus vite. Si toute fois vous aviez besoin de nous joindre, vous pouvez nous appeler au <a href="tel:{{ site.contact.phone | replace: " ", """" | replace: ")0", "" | replace: "(", "" }}">{{ site.contact.phone }}</a>{% endcapture %}{% include form-booking.html.liquid reassurance=reassurance %}
