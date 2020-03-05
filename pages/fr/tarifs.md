---
layout: default
title: Tarifs et réservation
i18n-key: booking
permalink: /tarifs
---

# Tarifs et réservation

## Nuitées

Notre établissement est composé de 20 chambres simples, 6 chambres doubles et 1 chambre familiale (composée de deux chambres doubles, d'une salle d'eau et d'un sanitaire indépendant). Certaines chambres offrent la possibilité d'ajouter un lit d'appoint (enfant&nbsp;<&nbsp;12 ans) ou un lit bébé (lit parapluie disponible gratuitement sur demande lors de la réservation).

<figure>
    <table>
    <thead>
        <tr>
        <th>Type</th>
        <th class="price">Tarif hors ménage<sup>*</sup></th>
        <th>Taxe de séjour<sup>**</sup></th>
        </tr>
    </thead>
    <tbody>
        <tr>
        <td>Chambre simple</td>
        <td class="price">22 €</td>
        <td>0.73 €</td>
        </tr>
        <tr>
        <td>Chambre double</td>
        <td class="price">35 €</td>
        <td>1.16 €</td>
        </tr>
        <tr>
        <td>Chambre familiale</td>
        <td class="price">70 €</td>
        <td>2.15 €</td>
        </tr>
        <tr>
        <td>Lit d’appoint (enfant &lt; 12 ans)</td>
        <td class="price">10 €</td>
        <td> - </td>
        </tr>
    </tbody>
    </table>
    <figcaption>
        <p><sup>*</sup> Un forfait ménage sera appliqué, en sus de ces tarifs, pour chaque séjour (4 € pour les chambres simples et doubles, 5 € pour la chambre familiale), en plus des tarifs de nuitées indiqués ci-dessous.</p>
        <p><sup>**</sup> Ces tarifs sont donnés à titre indicatifs et sont susceptibles d'évoluer en fonction de la réglementation en vigueur au moment de votre séjour. Vous pouvez trouver les conditions d'exonération de la taxe de séjour sur le site du Service Public ("<a href="https://www.service-public.fr/particuliers/vosdroits/F2048">Qu'est-ce que la taxe de séjour ?</a>").</p>
    </figcaption>
</figure>

## Repas

<table>
<thead>
    <tr>
    <th></th>
    <th colspan="2">Tarif</th>
    </tr>
    <tr>
    <th>Prestation</th>
    <th>Adulte</th>
    <th>Enfant&nbsp;<&nbsp;12 ans</th>
    </tr>
</thead>
<tbody>
    <tr>
    <td>Petit déjeuner</td>
    <td colspan="2" class="price">5 €</td>
    </tr>
    <tr>
    <td>Déjeuner</td>
    <td class="price">12 €</td>
    <td class="price">10 €</td>
    </tr>
    <tr>
    <td>Dîner</td>
    <td class="price">10 €</td>
    <td class="price">8 €</td>
    </tr>
    <tr>
    <td>Pique-nique</td>
    <td class="price">10 €</td>
    <td class="price">8 €</td>
    </tr>
    <tr>
    <td>Collation</td>
    <td colspan="2" class="price">1,50 €</td>
    </tr>
</tbody>
</table>

Merci de nous préciser, lors de la réservation, toute demande spécifique (repas bébé, régime particulier).

## Séjours

<figure>
    <table>
        <thead>
            <tr>
                <th colspan="5">Semaine (6 nuits - 7 jours)</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td></td>
                <td>Demi-pension</td>
                <td>Pension complète</td>
                <td>Taxe de séjour<sup>**</sup></td>
            </tr>
            <tr>
                <td>Chambre simple</td>
                <td class="price">230 €</td>
                <td class="price">280 €</td>
                <td class="price">4.38 €</td>
            </tr>
            <tr>
                <td>Chambre double</td>
                <td class="price">400 €</td>
                <td class="price">500 €</td>
                <td class="price">6.96 €</td>
            </tr>
            <tr>
                <td>Chambre famille<sup>*</sup></td>
                <td class="price">780 €</td>
                <td class="price">1 000 €</td>
                <td class="price">12.90 €</td>
            </tr>
            <tr>
                <td>Lit d'appoint (enfant < 12 ans)</td>
                <td class="price">140 €</td>
                <td class="price">180 €</td>
                <td class="price"> - </td>
            </tr>
        </tbody>
    </table>
    <figcaption>
        <p><sup>*</sup> Les tarifs indiqués pour la chambre familiale sont à titre indicatif pour 2 adultes et 2 enfants < 12 ans. Pour toute demande particulière, n'hésitez pas à nous contacter.</p>
        <p><sup>**</sup> Ces tarifs sont donnés à titre indicatifs et sont susceptibles d'évoluer en fonction de la réglementation en vigueur au moment de votre séjour. Vous pouvez trouver les conditions d'exonération de la taxe de séjour sur le site du Service Public ("<a href="https://www.service-public.fr/particuliers/vosdroits/F2048">Qu'est-ce que la taxe de séjour ?</a>").</p>
    </figcaption>
</figure>

## Faire une demande de réservation

{% capture reassurance %}Nous vous répondrons au plus vite. Si toute fois vous aviez besoin de nous joindre, vous pouvez nous appeler au <a href="tel:{{ site.contact.phone | replace: " ", "" | replace: "(+33)0", "+33" }}">{{ site.contact.phone }}</a>{% endcapture %}{% include form-booking.html.liquid reassurance=reassurance %}
