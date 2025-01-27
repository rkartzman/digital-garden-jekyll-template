---
layout: page
title: About
permalink: /about
---

I live in Los Angeles. I am currently working at [Updater](https://updater.com/) as a Software Engineer. I also run a Shopify app called [Gifted](https://apps.shopify.com/gifted-1).

### Elsewhere

- Send me a DM on [twitter](twitter.com/remykartz)
- Email me. my full name at gmail.
- [rkartzman](https://github.com/rkartzman) on Github

### Currently reading

- [Common Stocks and Uncommon Profits](https://www.amazon.com/Common-Stocks-Uncommon-Profits-Writings)
- [The Zurich Axioms](https://www.amazon.com/Zurich-Axioms-reward-generations-bankers/dp/1897597495)
- [The Intelligent Investor](https://www.amazon.com/Intelligent-Investor-Definitive-Investing-Essentials/dp/0060555661)

### Book Notes

<ul>
{% for book in site.books %}
  <li>
    <a href="{{ book.url }}">
      {{ book.title }}
    </a>
  </li>
{% endfor %}
</ul>

### About this site

this site is built/written with jekyll/markdown and is based on this open-source template [available on GitHub here](https://github.com/maximevaillancourt/digital-garden-jekyll-template).

You can read about the [step-by-step guide explaining how to set this up from scratch](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll).
