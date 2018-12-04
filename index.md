---
title: Boulder DSA
display-title: "<img src=\"/images/logos/letterhead.png\" srcset=\"/images/logos/letterhead@2x.png 2x\" alt=\"Boulder Democratic Socialists of America\" class=\"img-responsive center-block\">"

carousel:
  - mayday-2018-2.jpg  - mayday-2017.jpg  - mayday-2018.jpg  - sign-making.jpg  - teachers-march.jpg
---

<div id="main-carousel" class="carousel slide" data-ride="carousel" data-interval="5000">
  <!-- Indicators -->
  <ol class="carousel-indicators">
	{% for image in page.carousel %}
    <li data-target="#main-carousel" data-slide-to="{{ forloop.index0 }}"{% if forloop.first %} class="active"{% endif %}></li>
    {% endfor %}
  </ol>

  <!-- Wrapper for slides -->
  <div class="carousel-inner">
	{% for image in page.carousel %}
    <div class="item{% if forloop.first %} active{% endif %}">
      <img src="/images/main-carousel/{{ image }}" alt="Pictures of the Boulder DSA">
    </div>
    {% endfor %}
  </div>

  <!-- Controls -->
  <a class="left carousel-control" href="#main-carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left"></span>
  </a>
  <a class="right carousel-control" href="#main-carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div> <!-- Carousel -->

<div markdown="1" class="row">
<div markdown="1" class="col-md-10 col-md-offset-1">

{: .bg-black .text-center .lead }
Boulder Democratic Socialists of America is an activist organization which seeks to democratize not only our government but also our economy, our workplaces, and our society.

</div>

<div markdown="1" class="col-md-12" style="font-size: larger">

**Last year, Benjamin Harvey froze to death on a park bench on Christmas after being denied a bed at the Boulder Shelter for the Homeless due to a year-long suspension.**

The Shelter continues to kick out residents or deny entrance for minor offenses. With winter here, and no substantive changes made since Benjamin's death, we are certain to lose even more friends to the cold.

**We won't sit idly by as our neighbors freeze on our streets while beds sit empty in the homeless Shelter.**

**[Sign our letter](https://actionnetwork.org/petitions/protect-boulders-homeless-from-unfair-treatment-at-the-shelter
) to the Executive Director, Greg Harms, to demand justice for the poorest among us.**

</div>

<link href='https://actionnetwork.org/css/style-embed-v3.css' rel='stylesheet' type='text/css' /><script src='https://actionnetwork.org/widgets/v3/petition/protect-boulders-homeless-from-unfair-treatment-at-the-shelter?format=js&source=widget'></script><div class="col-md-12" id='can-petition-area-protect-boulders-homeless-from-unfair-treatment-at-the-shelter' style='width: 100%'><!-- this div is the target for our HTML insertion -->test</div>

<div markdown="1" class="col-md-12 scroll">

A call to action:

Are you angry about inequality and injustice in the US? Do you see the problems of racism, sexism, xenophobia and poverty getting worse rather than better? Are you finished with electing representatives that vote with their donors and not their constituents?
 
It’s time to radically re-define US democracy. Workers have a right to participate in the decisions of their employers. Residents of a community have the right to say whether oil companies can put wells next to their children’s schools. That the wealthiest country in the world can’t adequately feed, shelter, and medically treat all of its citizens is a travesty and embarrassment.

With American life expectancy falling, the wealth gap growing, the public education system under siege, and a President who is the worst example of a racist, sexist, and incredibly incompetent Boss with no virtue but his Extreme Wealth—we are not waiting for someone to save us with promises of Hope and Change. This time, Change will come from below, and it will be overwhelming. Join us and fight. Join us and win.

In solidarity,

_—Boulder County Democratic Socialists of America_

</div>
</div>
