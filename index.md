---
layout: event

event:
  series: "2017-02"
  date: 2017-02-01
  time: 7PM
  location: Zendesk Office, BGC

registration:
  date: 2017-02-01
  state: announce # announce | open | closed | over
  signup: http://goo.gl/forms/ZNHNImCMrR

hero:
  color: "#203a4f"
  opacity: 0.23
  image: images/2017-02/zendesk-office-official.jpg
  # :: current image is under Creative Commons Zero however,
  #    so no attribution is required. Might as well though, yeah?
  attribution_source: "Zendesk"
  attribution_url: "https://d16cvnquvjw7pr.cloudfront.net/www/img/p-brand/office/hi-res/EG0A0722.jpg"

# -- Comment out the venue if it's TBD --
venue:
  name: Zendesk Offices
  icon: images/2017-02/z-logo.png
  url: https://www.facebook.com/pages/Zendesk-Philippines/716978241700279
  map: https://goo.gl/maps/8eXLYbscco12
  address: |
    30F, The W Building 
    Fifth Avenue<br>
    BGC Taguig 

# -- Comment out the drinkup if it's not available --
drinkup: 
   name: Basta sa BGC Area
   map: https://goo.gl/maps/8eXLYbscco12

## After Party:

{% include after-party.html %} 

speakers:
- name: Jaggy Gauran
  avatar: "images/2017-02/u-jpas.jpg"
  title: Zendesk
  url: https://jag.gy
  github: jaggy
  twitter: jaggygauran
  description: Web guy

mailchimp:
  group_id:

##############################################################################
---

Let's talk about Laravel.
{:.pull-quote-heading.align-left.bottom-space-1}

Let's have an evening of updates from the Laravel and PHP community. Learn from experienced developers and discuss latest PHP and Laravel 5.4 and most importantly, have fun! 
{:.sans-pull-quote.top-collapse-0}

## Speakers

{% include speaker-list.html %}

Laravel Philippines meetups are held towards the end of very  month.  Everybody's welcome! Expect to hear about using Laravel and PHP while having fun. 

Subscribe to the meetup group at [Meetup.com/Laravel-Philippines](https://www.meetup.com/Laravel-Philippines/). This event is free. Bring your friends!

#### Our venue is

{% if page.venue %}
{% include location-box.html venue=page.venue %}{% else %}
{% include location-box-tbd.html %}{% endif %}

{% if page.venue %}
Special thanks to our generous venue sponsor, [{{ page.venue.name }}]({{ page.venue.url }}), for making our meetup possible.
{% endif %}

* * * *

### Thanks!

Need directions or any help? Interested in speaking or sponsorship? Contact
Ian at [idejesus@Zendesk.com](mailto:hi@ricostacruz.com) or Joe at [joe@Palala.me](mailto:joe@palala.me).

Laravel PH is made possible by everyone in the #laravelph  community. Join us on [Phackers #laravelph channel](http://phackers.io) 
