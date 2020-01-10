---
layout: default
title: Prices and Booking
permalink: /en/booking
i18n-key: booking
---

# Prices and Booking

## Prices <small>(<abbr title="Value Added Tax">VAT</abbr>)</small>

## Booking

{% capture reassurance %}We will answer you as soon as possible. If you still need to contact us, you can call us at <a href="tel:{{ site.contact.phone | replace: " ", "" | replace: ")0", "" | replace: "(", "" }}">{{ site.contact.phone }}</a>{% endcapture %}{% include form-booking.html.liquid reassurance=reassurance %}