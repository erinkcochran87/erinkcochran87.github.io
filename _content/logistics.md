---
section-title: Logistics

order: 2

type: "left"

icon: far fa-calendar-alt

image: general-warren-1.jpg

info:
  - item: "**Date**: {{ site.date }}"
  - item: "**Time**: TBD!"
  - item: "**Location**: [{{ site.venue }}]({{ site.venue-site }}), {{ site.venue-address }}"
  - item: "**Parking**: On-site, free"
  - item: "**Attire**: Cocktail. Need some help? [Click here!](#attire)"
  - item: "**Accommodations**: [Click here for info](#accommodations)."

ceremony-attire:
  - item: "**The ceremony will be outdoors on grass**, weather-permitting. Consider bringing along a pair of flats if you're dead-set on wearing fancy heels."
  - item: "**We're getting married in October. In Pennsylvania.** Which means it might be hot, or it could be freezing. ¯\_ (ツ)_/¯ Your guess is as good as ours, but dressing in layers is probably a good idea."

copy: |
  We'll be having an outdoor, **unplugged** ceremony. [Here's what that means](#unplugged-ceremony).

  Here's some other helpful info:

  <ul class="default">
  {% for thing in content.info %}
  <li>{{ thing.item | flatify | markdownify }}</li>
  {% endfor %}
  </ul>

  ---

  ### Unplugging at the ceremony {#unplugged-ceremony}

  While we fully encourage everyone to bring their phones, cameras, Polaroids, caricature artists, etc. to document The Big Fancy Party, **we politely request that all devices and caricature artists be put away during the ceremony**.

  We want to be present with everyone during this incredible moment, and for everyone to be present with us. We will gladly share the images from our amazing photographer with you after the wedding!

  ---

  ### Attire {#attire}

  Cocktail attire. What does that mean, exactly?

  > Just like it sounds - something that feels festive and fancy and worthy around a stiff drink. - [PureWow](https://www.purewow.com/weddings/what-does-cocktail-attire-mean)

  We want you to be comfortable, get your dancepants on, and look good doing it. That being said, here are some things to keep in mind:

  <ul class="default">
  {% for thing in content.ceremony-attire %}
  <li>{{ thing.item | flatify | markdownify }}</li>
  {% endfor %}
  </ul>

---