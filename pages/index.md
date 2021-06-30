---
layout: 2020/base
title: "Crystal Down: Scions Web Novel Overview"
date: 2020-01-12
shortlink: /s/1/
excerpt: |
  Twin orphans grow up in a remote village. They don't know much about their origins but their foster
  never tells them anything. All they have as the pendants they have. This is a story set in the same
  world as Crystal Down.
book:
  series: "Crystal Down: Scions"
intermediate_breadcrumbs:
  -
    title: Archived Projects
    url: /archive/
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
# {{ page.title }}

{% include series-overview/urls.html %}

## Disclaimer

{% include series-overview/disclaimer.md %}

## Volume 01: Children of Light and Darkness

<!-- markdownlint-disable MD033 -->
<div class="row">

<div class="col-12 col-md-3">
{% if page.canonical_domain %}
<img loading="lazy" src="thumbnail.webp" alt="Crystal Down: Scions Cover: a black and a white cat form a circle">
{% else %}
<img loading="lazy" src="{{ '/scions/thumbnail.webp' | prepend: site.static_url | absolute_url }}" alt="Crystal Down: Scions Cover: a black and a white cat form a circle">
{% endif %}
</div>
<div class="col-12 col-md-9">
<p>
Twin orphans grow up in a remote village.
They don't know much about their origins, but their foster grandfather never tells them anything.
All they have of their real parents are the pendants they have always worm.
Their peaceful world crumbles when they're forced to leave the country — and thus are forced to leave their village.
</p>
<p>
This story is set in the the same universe as <a href="{{'/crystaldown/' | absolute_url }}">Crystal Down</a>.
</p>

<h3 class="mt-3">Children of Light and Darness Chapters</h3>

{% assign pages = site.pages
  | where: "lang", "en-CA"
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down: Scions"
  | where: "book.number", 1
  | sort: "chapter" %}

{% include series-overview/chapter-list.html %}

</div>
</div>
<!-- markdownlint-enable MD033 -->

[Prologue](./01-children-of-light-and-darkness/00-prologue/){:id="next" style="display: none"}

### Glossary

See the [Crystal Down Glossary](/crystaldown/glossary/){:.btn .btn-large .btn-primary}.
