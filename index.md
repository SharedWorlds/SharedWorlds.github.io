---
layout: page
title: SharedWorlds.Info
tagline: Everything and Anything on Shared World Fiction
---
{% include JB/setup %}

## What is Shared World Fiction?

Shared World fiction, sometimes called Shared Universe fiction, is fiction where
multiple authors write separate pieces that share the same larger setting and
background. These pieces could be of any length but in my experience are mostly
multiple volumes of anthologies with a few novels set in the same world.

Shared worlds usually have between 1-3 coordinators that are in charge of
organizing author's works, editing, and corralling continuity.

Some better known shared worlds are:

* Known Space - Larry Niven's science fiction world depicting the wars between men and the
cat-like Kzinti aliens
* 1632-verse - Also known as the Ring of Fire world, this is Eric Flint's
alternate history series. Set in 17th century Europe, it depicts the struggles
a small West Virginian town moved from the year 2000 to the year 1631, and
dropped into the middle of Germany's Black Forest during the 30 years war
* Cthulhu Mythos - H.P. Lovecraft's works describing ancient cosmic horrors
and their incursions into our world, and the many authors that based their works
on what he wrote.
* Thieves World - Robert Lynn Asprin's gritty mystical fantasy world, primarily
revolving around Sanctuary, a dangerous port town on the fringe of a fading
empire.
* Sacred Band - Janet Morris' fantasy world based on a historical unit, with heroic
adventures of magic and military battles revolving around the demigod Tempus and
the Sacred Band of Thebes that he commands.
* Heroes in Hell - Another Janet Morris world, this Bangsian shared world depicts
a version of Hell where you can find any damned soul, from Ghengis Khan to Caesar,
and their struggles to make a life for themselves after death.
* Merovingen Nights - C.J. Cherryh's science fantasy world in her Alliance-Union
universe in the far future 3240 A.D., where technology is mostly limited to that
available in the middle-ages due to hardships and isolation.

## Upcoming Posts

* A Zelazny Retrospective
* A Heroes in Hell Retrospective
* Conlanging: A Case Study
* Book Reviews

## Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
