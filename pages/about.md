---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I am a 4th year PhD student at Vanderbilt University studying chemistry under Dr. Timothy Hanusa. You are reading my personal website, so thank you for visiting! I wanted to make a website to have a place on the internet that would serve as an online CV and I could blog from, and make me searchable. I have made this website using GitHub Pages, which implements Jekyll. This is based on the PortfolYOU template at https://github.com/YoussefRaafatNasry/portfolYOU by Youssef Raafat. Please excuse any non-functional sections, it's a work in progress :)

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
