---
layout: event

event:
  series: "2017-02"
  date: 0000-00-00
  time: Around 7PM
  location: Zendesk Office, BGC

registration:
  date: 2017-02-13
  state: announce # announce | limbo | open | closed | over
  signup: http://goo.gl/forms/ZNHNImCMrR

hero:
  color: "#203a4f"
  opacity: 0.32
  image: images/2017-02/zendesk-office-official.jpg
  # :: current image is under Creative Commons Zero however,
  #    so no attribution is required. Might as well though, yeah?
  attribution_source: "Zendesk"
  attribution_url: "https://d16cvnquvjw7pr.cloudfront.net/www/img/p-brand/office/hi-res/EG0A0722.jpg"

# -- Comment out the venue if it's TBD --
venue:
  name: Zendesk Philippines
  icon: logos/zendesklogo.png
  url: https://www.facebook.com/pages/Zendesk-Philippines/716978241700279
  map: https://goo.gl/maps/8eXLYbscco12
  address: |-
    30F, The W Building<br>
    Fifth Avenue<br>
    BGC Taguig 

speakers:
- name: Jaggy Gauran
  avatar: "images/2017-02/u-jaggy.jpg"
  title: Zendesk
  url: https://jag.gy
  github: jaggy
  twitter: jaggygauran
  description: |- 
    Jaggy will be talking about Facades vs Dependency Injection and possibly Domain Driven Design<br>

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

{% if page.venue %}{% include location-box.html venue=page.venue %}{% else %}{% include location-box-tbd.html %}{% endif %}
{% if page.venue %} Special thanks to our generous venue sponsor, [{{ page.venue.name }}]({{ page.venue.url }}), for making our meetup possible.  {% endif %} 

#### After Party

{% include drinkup.html %}

### Thanks!

Need directions or any help? Interested in speaking or sponsorship? Contact
Ian at [idejesus@Zendesk.com](mailto:idejesus@zendesk.com) or Joe at [jose.Palala@live.com](http://bit.ly/2lbmME0).

Laravel PH is made possible by everyone in the #laravelph  community. Join us on [Phackers #laravelph channel](http://phackers.io) 
