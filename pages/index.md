---
layout: 2020/base
title: "Crystal Down: Scions"
date: 2020-01-12
shortlink: /s/1/
excerpt: |
  Twin orphans grow up in a remote village. They don't know much about their origins but their foster
  never tells them anything. All they have as the pendants they have. This is a story set in the same
  world as Crystal Down.
feed: /scions/chapters.xml
scribblehub: https://www.scribblehub.com/series/82746/crystal-down-scions-children-of-light-and-darkness/
---
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [{
    "@type": "ListItem",
    "position": 0,
    "name": "{{ site.title }}",
    "item": "{{ "/" | absolute_url }}"
  }, {
    "@type": "ListItem",
    "position": 1,
    "name": "Crystal Down: Scions",
    "item": "{{ page.url | absolute_url }}"
  }]
}
</script>
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Book",
  "url": "{{ page.url | absolute_url }}",
  "name": "Crystal Down Scions 01: Children of of Light and Darkness",
  "position": "1",
  "copyrightYear": "2020",
  "inLanguage": "en-CA",
  "author": {
    "@type": "Person",
    "name": "{{ site.data.staff[page.author].name }}",
    "url": "{{ site.data.staff[page.author].url }}"
  },
  "publisher": {
    "@type": "Person",
    "name": "{{ site.data.staff[page.author].name }}",
    "url": "{{ site.data.staff[page.author].url }}"
  }
}
</script>

<!-- markdownlint-disable MD025 -->
# Crystal Down: Scions Web Novel Overview

<!-- markdownlint-disable MD033 -->
<p class="social icons">
  {% if page.feed %}
  <link rel="alternate" type="application/atom+xml" href="{{ page.feed | absolute_url }}" title="{{ page.book.title }} Chapters Atom Feed">
  <a rel="alternate" type="application/atom+xml"
   href="{{ page.feed | absolute_url }}"
   title="{{ page.book.title }} Chapters Atom Feed">
    <img src="{{ '/assets/images/feed.png' | prepend: site.staticUrl | absolute_url }}" alt="Atom Feed">
  </a>
  {% endif %}
  {% if page.scribblehub %}
  <a href="{{ page.scribblehub }}" rel="alternate"
    target="_blank" rel="noopener nofollow" title="{{ page.book.title }} on Scribble Hub">
    <img src="{{ '/assets/images/scribblehub.png' | prepend: site.staticUrl | absolute_url }}" alt="Scribble Hub">
  </a>
  {% endif %}
  {% if page.wattpad %}
  <a href="{{ page.wattpad }}" rel="alternate"
    target="_blank" rel="noopener nofollow" title="{{ page.book.title }} on Wattpad">
    <img src="{{ '/assets/images/wattpad.png' | prepend: site.staticUrl | absolute_url }}" alt="Wattpad">
  </a>
  {% endif %}
</p>
<!-- markdownlint-enable MD033 -->

## Disclaimer

This is a work of fiction.
Names, characters, places, and incidents are the product of the author's imagination or are used fictitiously.
Any resemblance to actual events, locales, or persons, living or dead, is coincidental.


## Volume 01: Children of Light and Darkness

<!-- markdownlint-disable MD033 -->
<div class="row">

<div class="col-12 col-md-3">
<img src="{{ page.path | replace: 'index.md', 'thumbnail.png' | prepend: '/' | prepend: site.staticUrl }}" alt="Crystal Down: Scions Cover: a black and a white cat form a circle">
</div>
<div class="col-12 col-md-9">
Twin orphans grow up in a remote village. They don't know much about their
origins, but their foster grandfather never tells them anything. All they have
of their real parents are the pendants they have always worm. Their peaceful
world crumbles when they're forced to leave the country — and thus are forced to
leave their village.

{% assign pages = site.pages
  | where: "lang", "en-CA"
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down: Scions"
  | where: "book.number", 1
  | sort: "chapter" %}
<h3 class="mt-3">Children of Light and Darness Chapters</h3>

<ol start="0">{% for page in pages %}
{% if jekyll.environment != "unpublished" and page.published == "sponsors" %}{% break %}{% endif %}
  <li><a href="{{ page.url }}">{{page.title}}</a></li>{% endfor %}
</ol>
<!-- markdownlint-enable MD033 -->
</div>
</div>
[Prologue](./01-children-of-light-and-darkness/00-prologue/){:id="next" style="display: none"}

### Glossary

See the [Crystal Down Glossary](/crystaldown/glossary/){:.btn .btn-large .btn-primary}.

