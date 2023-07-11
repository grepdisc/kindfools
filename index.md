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

**WRITE ON! workshop at 1pm July 20th** [Learn More](/writeon/){: .btn .btn--info}<br>
**WRITE ON! workshop at 7pm July 25th** [Learn More](/writeon/){: .btn .btn--info}
{: .notice--info .maxwidthbox .align-center}

{% comment %}
**Starting July 2023 for young adults (writing & art)**<br>
**Collaborative Community Art** [SIGN UP July 2023](https://communitycanvases.org/events/communityartsummer2023/){: .btn .btn--success .btn--large}<br>
{: .notice--success .maxwidthbox .align-center}

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
  {% for post in site.writtenat limit:8 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

