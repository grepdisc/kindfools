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

**WRITE ON! April 4, 2023 at 6:00pm on Zoom** [Register](/signups/writeon20230404/){: .btn .btn--success}<br>
**WRITE ON! April 11, 2023 at 6:00pm at Sol Rise (226 East Utica St)** [Register](/signups/writeon20230411/){: .btn .btn--success}<br>
**WRITE ON! workshops** [Learn More](https://kindfools.org/writeon/){: .btn .btn--info}
{: .notice--info .maxwidthbox .align-center}

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

