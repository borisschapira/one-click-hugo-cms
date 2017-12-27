---
layout: default
title: Tarifs et réservation
i18n-key: booking
---

# Tarifs et réservation

## Nos tarifs <small>(prix <abbr title="Toutes Taxes Comprises">TTC</abbr>)</small>

<table>
	<tbody><tr>
		<th></th>
		<th>Suite Laborie</th>
		<th>Chambre Joséphine</th>
		<th>Chambre Rocaille</th>
	</tr>

	<tr>
		<td>1 personne</td>
		<td colspan="2"></td>
		<td colspan="1">60 €</td>
	</tr>

	<tr>
		<td>2 personnes</td>
		<td>100 €</td>
		<td>90 €</td>
		<td>80 €</td>
	</tr>

	<tr>
		<td>Personne supplémentaire</td>
		<td colspan="2">22 €</td>
		<td></td>
	</tr>

	<tr>
		<td>Bébé (- 2 ans)</td>
		<td colspan="3">5 €</td>
	</tr>

	<tr>
		<td>Repas (vin compris)</td>
		<td colspan="3">30 €</td>
	</tr>

	<tr>
		<td>Repas enfant (2 à 12 ans)</td>
		<td colspan="3">12 €</td>
	</tr>

	<tr>
		<td>Panier pique-nique midi</td>
		<td colspan="3">12 €</td>
	</tr>
</tbody></table>

## Faire une demande de réservation

{% capture reassurance %}Nous vous répondrons au plus vite. Si toute fois vous aviez besoin de nous joindre, vous pouvez nous appeler au <a href="tel:{{ site.contact.phone | replace: " ", "" }}">{{ site.contact.phone }}</a>{% endcapture %}{% include form-booking.html.liquid reassurance=reassurance %}