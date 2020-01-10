---
layout: default
title: Tarifs indicatifs et réservation
i18n-key: booking
permalink: /tarifs
---

# Tarifs indicatifs et réservation

## Chambres seules

<figure>
    <table>
    <thead>
        <tr>
        <th>Type</th>
        <th class="price">Prix TTC</th>
        </tr>
    </thead>
    <tbody>
        <tr>
        <td>Chambre simple</td>
        <td class="price">22 €</td>
        </tr>
        <tr>
        <td>Chambre double</td>
        <td class="price">38 €</td>
        </tr>
        <tr>
        <td>Chambre familiale<sup>*</sup></td>
        <td class="price">70 €</td>
        </tr>
        <tr>
        <td>Lit d’appoint (enfant &lt; 12 ans)</td>
        <td class="price">10 €</td>
        </tr>
    </tbody>
    </table>
    <figcaption><sup>*</sup> La chambre familiale est composée d'une chambre double adultes (avec possibilité d'ajouter un lit d'appoint) et d'une chambre double enfants, d'une salle d'eau et d'un toilette.</figcaption>
</figure>

## Repas

<figure>
    <table>
    <thead>
        <tr>
        <th>Prestation</th>
        <th class="price">Prix TTC</th>
        </tr>
    </thead>
    <tbody>
        <tr>
        <td>Petit déjeuner<sup>*</sup></td>
        <td class="price">4 €</td>
        </tr>
        <tr>
        <td>Déjeuner</td>
        <td class="price">10 €</td>
        </tr>
        <tr>
        <td>Dîner</td>
        <td class="price">10 €</td>
        </tr>
        <tr>
        <td>Café « accueil »</td>
        <td class="price">1,50 €</td>
        </tr>
    </tbody>
    </table>
    <figcaption><sup>*</sup> Une réduction de 2€ sera appliquée pour les enfants < 12 ans. </figcaption>
</figure>

Pour toute demande spécifique (repas bébé ou enfants < 12 ans, régimes particuliers), merci de nous contacter.

## Chambres et repas

<figure>
    <table>
        <thead>
            <tr>
                <th colspan="3">Semaine (6 nuits - 7 jours)</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td></td>
                <td>Demi-pension</td>
                <td>Pension complète</td>
            </tr>
            <tr>
                <td>Chambre simple</td>
                <td class="price">200 €</td>
                <td class="price">270 €</td>
            </tr>
            <tr>
                <td>Chambre double</td>
                <td class="price">380 €</td>
                <td class="price">520 €</td>
            </tr>
            <tr>
                <td>Lit d'appoint (enfant < 12 ans)</td>
                <td class="price">120 €</td>
                <td class="price">180 €</td>
            </tr>
            <tr>
                <td>Chambre famille<sup>*</sup></td>
                <td class="price">730 €</td>
                <td class="price">990 €</td>
            </tr>
        </tbody>
    </table>
    <figcaption><sup>*</sup> Les tarifs indiqués pour la chambre familiale sont à titre indicatif pour 2 adultes et 2 enfants < 12 ans. Pour toute demande particulière, n'hésitez pas à nous contacter.</figcaption>
</figure>

La taxe de séjour est de 0.60 € / nuit pour une chambre simple, 1.12 € / nuit pour une chambre double et 2.30 € / nuit pour la chambre familiale. Vous trouverez les conditions d'exonération de la taxe de séjour sur le site du Service Public (https://www.service-public.fr/particuliers/vosdroits/F2048).

## Faire une demande de réservation

{% capture reassurance %}Nous vous répondrons au plus vite. Si toute fois vous aviez besoin de nous joindre, vous pouvez nous appeler au <a href="tel:{{ site.contact.phone | replace: " ", "" | replace: "(+33)0", "+33" }}">{{ site.contact.phone }}</a>{% endcapture %}{% include form-booking.html.liquid reassurance=reassurance %}
