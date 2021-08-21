---
title: Anneli Ulsberg - Web and interaction designer
---

<div class="content" id="intro" markdown="1">
# Anneli
## Interaction designer

I am a creative person who enjoys to unfold my creativity either digitally or hands on with paint, brushes and canvas.

I espessially like to use my creativity to make beautiful, userfriendly and interactive web designs.
</div>

<div class="content" id="tools" markdown="1">
    {% include card.html text="[I Git it!](https://github.com/anneliulsberg)" %}
    {% include card.html %}
    {% include card.html %}
    {% include card.html text="“Good artists copy. Great artists steal. - Picasso”"%}
</div>

<div class="content" id="slogan-wrapper">
    <div id="slogan" >
        <h1>Creativity is my game</h1>
    </div>
</div>

<br class="space">
<br class="space" />

<div class="content" id="portfolio" markdown="1">
#### Portfolio

These projects portray my skills in responsive design, CSS, HTML and illustration

{% assign main_projects = site.pages | where: 'project', 'main' | sort: 'order' %}
<ul id="main-portfolio">
{% for project in main_projects %}
<li><a href="{{ project.url }}"><span>{{ project.title }}</span></a></li>
{% endfor %}
</ul>

##### New Element AS

{:.text-hover}
Here is some of the work I did for [New Element AS](https://www.newelement.no/).

{% assign ne_projects = site.pages | where: 'project', 'new-element' | sort: 'order' %}
<ul id="ne-portfolio">
{% for project in ne_projects %}
<li><a href="{{ project.url }}"><span>{{ project.title }}</span></a></li>
{% endfor %}
</ul>
</div>

<div class="content" id="contact" markdown="1">
### Contact

You can reach me on one or more of these places

* [<span>Linkedin</span>](https://no.linkedin.com/pub/anneli-ulsberg/97/287/88)
* [<span>Facebook</span>](https://www.facebook.com/anneli.ulsberg)
* [<span>mail</span>](mailto:anneli@ulsberg.no)
* [<span>Github</span>](https://github.com/anneliulsberg)
* [<span>Twitter</span>](https://twitter.com/litntweet)
</div>
