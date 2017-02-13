---
layout: event

event:
  series: "2017-02"
  date: 2017-02-18
  time: 930AM
  location: Zendesk Office, BGC

registration:
  date: 2017-02-07
  state: open # announce | limbo | open | closed | over
  signup: https://www.meetup.com/Laravel-Philippines/quick_join/?eventId=237516402&joinFrom=event&response=3

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
  map: http://bit.ly/zdeskph
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
    Jaggy, together with the Zendesk team, will discuss about Facades vs Dependency Injection, and Domain Driven Design. 

---

Let's talk about Laravel.
{:.pull-quote-heading.align-left.bottom-space-1}

Join us in our first meetup of the year!
{:.sans-pull-quote.top-collapse-0}

Meet experienced developers and learn about current trends in Laravel and PHP!
{:.sans-pull-quote.top-collapse-0}

## Speakers

{% include speaker-list.html %}

Laravel.PH meetups are usually held twice every quarter. Please subscribe to the group at [Meetup.com/Laravel-Philippines](https://www.meetup.com/Laravel-Philippines/) to know about upcoming events. 
{: .text-justify}

This event is free. Come join us and bring your friends, whether they are already experienced or just beginning web developers who are interested in Laravel.
{: .text-justify}

#### Our venue is at

{% if page.venue %}{% include location-box.html venue=page.venue %}{% else %}{% include location-box-tbd.html %}{% endif %}

{% if page.venue %} Special thanks to our generous venue sponsor, [{{ page.venue.name }}]({{ page.venue.url }}), for making our meetup possible.  {% endif %} 

#### After Party

{% include nodrinkup.html %}

### Thanks!

Need directions or any help? Would you like to share your knowledge or build our Laravel community by sponsoring our event? Please contact Ian at [idejesus@zendesk.com](mailto:idejesus@zendesk.com) or Joe at [jose.palala@live.com](mailto:jose.palala@live.com) for any inquiries. We appreciate any kind of help.
{: .text-justify}

Laravel PH is made possible by everyone in the #laravelph community. Join our slack community at [#laravelph channel](http://phackers.io) or our [facebook group](https://www.facebook.com/groups/laravelph/).
{: .text-justify}

Need a certificate to show your prof? You may print your own and we'll gladly sign it. Either Ian or Joe will sign it on the spot.
{: .text-justify}
