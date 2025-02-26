---
layout: default
title: Blag
permalink: /blog
---
# Blog

Random ramblings. My current blog project is an introductory guide to the University of Waterloo.

## Guide to UW

As I am a computer engineering student, any information I have will focus on my program. However, the information is also applicable to other programs in the faculty of engineering, and perhaps useful in general with regards to UW.

***Disclaimer: Use this information at your own risk. Always check with official sources and with people who are more qualified than I am. I will not be held liable for anything that goes wrong from this website.***

### Author Recommendations

* [Is UW the right choice? (and UW CE vs UW CS)](/blog/1-F)
* [3-1. Onboarding Guide](/blog/3-1)
* [3-3. Co-op](/blog/3-3)
* [Xierumeng's Guide to R&eacute;sum&eacute; Creation](/resources/resume-guide)

### Graduation Series:

Coming soon! Topics will include fourth year, TEs, full-time offers (and negotiation), Iron Ring ceremony, convocation.

### Upper Year Series:

Coming soon (TODO): CSEs, NSEs, US co-ops (NVIDIA REMOTE WOOT), extracurriculars I found enjoyable.

<ul class="post-list archive-ul">
  {% for post in site.categories.blogUWUpper %}
    <li class="archive-li">
      {{ post.date | date: "%Y-%m-%d" }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
  <br>
</ul>

TODO: Dates will be fixed when I add more detail to my satisfaction.

### Onboarding Series:

First year advice.

<ul class="post-list archive-ul">
  {% for post in site.categories.blogUWOnboarding %}
    <li class="archive-li">
      {{ post.date | date: "%Y-%m-%d" }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
  <br>
</ul>

### Acceptance Series:

After accepting and meeting the conditional offer.

<ul class="post-list archive-ul">
  {% for post in site.categories.blogUWAcceptance %}
    <li class="archive-li">
      {{ post.date | date: "%Y-%m-%d" }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
  <br>
</ul>

### Admissions Series:

Application and admissions process.

<ul class="post-list archive-ul">
  {% for post in site.categories.blogUWAdmissions %}
    <li class="archive-li">
      {{ post.date | date: "%Y-%m-%d" }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
  <br>
</ul>

## Resources

Miscellaneous information and guides.

<ul class="post-list archive-ul">
  {% for post in site.categories.guide %}
    <li class="archive-li">
      {{ post.date | date: "%Y-%m-%d" }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
  <br>
</ul>

## Future stuff

* Xierumeng's Guide to Academics?
* Xierumeng's Guide to C++ setup?
* Xierumeng's Guide to Command-Line Compiling C++?
* Xierumeng's Guide to Concurrency?
