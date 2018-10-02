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

<th>Semaine (6 nuitées)</th>

</tr>
<tr>
<td>Chambre simple</td>
<td>20 €</td>

<td>100 €</td>
</tr>
<tr>
<td>Chambre double</td>
<td> 36 €</td>

<td>200 €</td>
</tr>

<tr>
<td>Chambre d'affaires</td>
<td>45 €</td>

<td>250 €</td>
</tr>
<tr>
<td>Chambre familiale</td>
<td>70 €</td>

<td>400 €</td>
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
<td> 5 €</td>
<td>4 €</td>
</tr>
<tr>
<td>Déjeuner</td>
<td> 12 €</td>
<td>10 €</td>
</tr>
<tr>
<td>Dîner</td>
<td> 10 €</td>
<td>8 €</td>
</tr>

<tr>
<td>Pique-nique</td>
<td> 10 €</td>
<td>8 €</td>
</tr>
</tbody></table>

## Faire une demande de réservation

{% capture reassurance %}Nous vous répondrons au plus vite. Si toute fois vous aviez besoin de nous joindre, vous pouvez nous appeler au <a href="tel:{{ site.contact.phone | replace: " ", """" | replace: ")0", "" | replace: "(", "" }}">{{ site.contact.phone }}</a>{% endcapture %}{% include form-booking.html.liquid reassurance=reassurance %}
