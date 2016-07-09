---
layout: page
title: Gallery
excerpt: "So Simple is a responsive Jekyll theme for your words and images."
modified: 2014-08-08T19:44:38.564948-04:00
---
<link rel="stylesheet" href="flexslider.css" type="text/css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.2/jquery.min.js"></script>
<script src="jquery.flexslider.js"></script>

<div class="flexslider">
  <ul class="slides">
    <a href="/gallery/arduino_workshop">
      <li>
        <img src="/images/gallery/arduino_workshop.JPG" />
        <p class="flex-caption">Arduino Workshop</p>
      </li>
    </a>
      <li>
        <img src="/images/gallery/equipment.JPG" />
        <p class="flex-caption">Lab Equipment</p>
      </li>
      <li>
        <img src="/images/gallery/foundation_day.JPG" />
        <p class="flex-caption">TL Foundation</p>
      </li>
      <li>
        <img src="/images/gallery/htw.JPG" />
        <p class="flex-caption">How Things Work</p>
      </li>
      <li>
        <img src="/images/gallery/inauguration.JPG" />
        <p class="flex-caption">TL Inauguration</p>
      </li>
      <li>
        <img src="/images/gallery/lab_others.JPG" />
        <p class="flex-caption">Lab Tour</p>
      </li>
      <li>
        <img src="/images/gallery/tl_talk.JPG" />
        <p class="flex-caption">TL Talks</p>
      </li>
      <li>
        <img src="/images/gallery/visits.JPG" />
        <p class="flex-caption">Visitors</p>
      </li>

  </ul>
</div>

<script type="text/javascript" charset="utf-8">
  $(window).load(function() {
  $('.flexslider').flexslider({
    animation: "slide"
  });
});
</script>

<style type="text/css">
.flex-caption {
  width: 96%;
  padding: 2%;
  left: 0;
  bottom: 0;
  background: rgba(0,0,0,.5);
  color: #fff;
  text-shadow: 0 -1px 0 rgba(0,0,0,.3);
  font-size: 14px;
  line-height: 18px;
}
</style>