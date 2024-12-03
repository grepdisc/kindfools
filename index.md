---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/wk-home-page-feature.jpg
excerpt: "expressing our truth, and having it listened to, heals us"

all_posts:
  - url: "/year-archive/"
    btn_label: "All Posts"
    btn_class: "btn btn--small btn--inverse"

---

# Upcoming Events
{: .text-center}

**Giving Tuesday** [Donate Today](https://communitycanvases.org/donate/
    ){: .btn .btn--success .btn--large}<br>
**WRITE ON - December 12th** at 1pm at Merriweather Library
    [Sign Up/Info](/writeon/){: .btn .btn--success}<br>
WRITE ON - Home - writing in your native language
    [Details](/home/){: .btn .btn--info}<br>
**"Heavy" Reflections** part of the Civil Writes Project
   [Details](/heavyreflections/){: .btn .btn--info}<br>
Signal Box Art Project [Info/Application](
    https://communitycanvases.org/signalboxes/northbuffalo/
    ){: .btn .btn--info}<br>
All Community Canvases [Events](
https://communitycanvases.org/events/){: .btn .btn--info}
{: .notice--info .maxwidthbox .align-center}

{% comment %}
**WRITE ON on Tuesday August 20th at 6:00pm**
    [Sign Up/Info](/writeon/){: .btn .btn--success}<br>
**Kind Conversations August 8th** [Info/Sign-up](
    /kindconversations/){: .btn .btn--success}<br>
Deadline of June 1st for **Heavy Reflections** to [Submit Your Writing](
     https://docs.google.com/forms/d/e/1FAIpQLSeGun-mNIqwkah9h1Z-uaKtSew6GD5pRmeW0_6y5PouaS0ZYw/viewform?usp=sf_link
  ){: .btn .btn--large .btn--success}
**WNY Trash Mob's Grant Street Cleanup May 18th** [Details](
    https://communitycanvases.org/events/cleanup20240518/){: .btn .btn--info}<br>
**The Woven Event** May 20th at 5:00pm [Info/Sign-up](
    /thewovenevent/){: .btn .btn--info}<br>
**Kind Conversations May 14th POSTPONED** [Info/Sign-up](
    /kindconversations/){: .btn .btn--success}<br>
Our partner - **Recovery Stories at 5:30pm March 18th** [Info/Sign-up](
    /recoverystories/){: .btn .btn--info}<br>
Partner Event: Service & Spirituality Feb 17th [Info/Sign-up](
    https://www.eventbrite.com/e/spirituality-in-everyday-life-workshop-series-service-tickets-811288544877
    ){: .btn .btn--info}<br>
**Racial Healing Circle at UUCB by NACS 1pm Feb 19th** [Info/Sign-up](
    https://brownpapertickets.com/event/6234307){: .btn .btn--info}<br>
**Community Swing** at 6pm on Jan 31st (live band) [Info](
    https://www.facebook.com/communityswing
    ){: .btn .btn--info}<br>
**Starting July 2023 for young adults (writing & art)**<br>
**Collaborative Community Art** [SIGN UP July 2023](https://communitycanvases.org/events/communityartsummer2023/){: .btn .btn--success .btn--large}<br>
{: .notice--success .maxwidthbox .align-center}
Our partner - **Recovery Stories at 5:30pm Jan 22nd** [Info/Sign-up](
    /recoverystories/){: .btn .btn--info}<br>
**100,000 Poets for Change Open Mic** 3pm September 30th [Info](
    /events/hundredthousandpoets2023/){: .btn .btn--info}<br>
{: .notice--success .maxwidthbox .align-center}

End-of-Year support for Kind Fools/Community Canvases [Donate or Volunteer here](
    https://communitycanvases.org/donate/){: .btn .btn--success}<br>
Our partner - **Recovery Stories at 5:30pm Nov 27th** [Info/Sign-up](
    /recoverystories/){: .btn .btn--info}<br>

**Grant Street Public Meeting** 5:30pm Jan 31 at M&T Bank at 130 Grant St
    [Info](https://communitycanvases.org/grantstreetjan31/
    ){: .btn .btn--info}<br>

Please check back here soon for more WRITE ON workshops.
{% endcomment %}

 Programs
{: .text-center}

<div class="grid">
    {% for project in site.data.projects %}
        <div class="grid-item">
            <a alt="{{ project.name }}" href="{{ project.link }}" title="{{ project.name }}">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        {{ project.name }}
                    </div>
                    <div class="panel-body" style="background: url('{{ project.image }}') no-repeat; background-size: cover; min-height: 200px;"></div>
                </div>
            </a>
        </div>
    {% endfor %}
</div>

# Recent Stories
{: .text-center .clear-left}

<div class="grid_wrapper">
  {% for post in site.posts limit:8 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

# [Written at WRITE ON!](/writtenat/)
{: .text-center .clear-left}

<div class="grid_wrapper">
  {% for post in site.writtenat limit:24 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

