# Search engine optimization

## Create valuable content

The most important thing to remember about search engine optimization is to provide **real, valuable content for humans**. If it’s useful, people will link to it, tweet it, and talk about it and it will show up in search results.

**Things that matter**

- *Honest, naturally keyword rich text*: if there are too many keywords for natural content, search engines will think you’re targeting them and penalize your site
- *More content than code markup*
- *Clear information hierarchy*: good navigation, good structure, good headings, etc.
- *First line of first paragraph*
- *Proper semantics*: search engines care what elements you choose and rank your content based on them
- *Faster the website the better*: Google penalizes websites that are slow
- *Links to your site from reputable sources*: the more incoming links from good, real sources, the better
- *Clean, meaningful URLs & filenames*: the words in URLs are extremely important
- *Older domains*: brand new domains have less power than domains that have existed for a while
- *Visible to search engines without barriers*: public, not behind a sign-in, not hidden by Javascript
- *Metadata*: enhanced semantics, rich information, [Microformats](http://microformats.org/), [Microdata](http://schema.org/), [RDFa Lite](http://rdfa.info/)

**Important Tags**

- `<title>` — the most important for keywords, also visible as the link on search results
- `<a>` — search engines look for keywords to apply to your site as well as the site you are linking to
- `<h1>`, `<h2>`, `<h3>`, etc. — very important for keywords
- `<strong>`, `<em>`
- `<meta name="description">` — sometimes used for keywords, other times not; also often used as the description in search results, but if the search engine deems it’s inappropriate something else will be used
- `<img alt="">` — Alt attributes are how search engines classify images

**Helpful resources**

- **[Web Developers SEO Cheat Sheet](http://moz.com/blog/the-web-developers-seo-cheat-sheet-2013-edition)**
- [Common Sense SEO Checklist](http://css-tricks.com/common-sense-seo-checklist/)
- [SEO Fundamentals for Web Designers](http://webdesign.tutsplus.com/sessions/seo-fundamentals-for-web-designers/)
- [The Beginners Guide to SEO](http://www.seomoz.org/beginners-guide-to-seo)
- [Thoughts on SEO (39:46)](http://css-tricks.com/video-screencasts/83-thoughts-on-seo/)
- [New SEO process](http://www.seomoz.org/blog/the-new-seo-process-quit-being-kanye)
- [Writing useful page titles](http://www.456bereastreet.com/archive/201102/writing_useful_page_titles/)
- [SEO Strategies for Designers](http://www.sitepoint.com/seo-strategies-designers-part-2/)
- [Duplicate Content Penalty](http://www.webdesignfromscratch.com/seo/google-duplicate-content-penalty/)

**Tools**

- **[HTML5 Outliner](http://gsnedders.html5.org/outliner/)**
- [HTML5 Outliner Chrome Extension](https://chrome.google.com/webstore/detail/afoibpobokebhgfnknfndkgemglggomo)
- **[Lynx Viewer](http://www.clickability.co.uk/lynx-viewer.php)** (Also good for checking accessibility)
- **[Google Search Engine Results Previewer](http://seo-website-designer.com/Google-SERP-Emulator)**
- [Keyword Frequency Counter](http://www.yellowpipe.com/yis/tools/wordcount/index.php)
- [Keyword Density Analyzer](http://tools.seobook.com/general/keyword-density/)
- [Complete List of Best SEO-Tools by Smashing Magazine](http://www.smashingmagazine.com/2006/09/22/complete-list-of-best-seo-tools/)

**Blogs, books & bodies**

- [Building Findable Websites](http://www.amazon.ca/dp/0321526287/) by Aarron Walter
- [SEOmoz](http://www.seomoz.org/)
- [Search Engine Land](http://searchengineland.com/)
- [Matt Cutts](http://www.mattcutts.com/blog/) [@mattcutts](https://twitter.com/mattcutts)

## Sitemaps

[⬇ Download sample sitemap.xml](sitemap.xml)

Providing a sitemap specifically for search engines is a great way to suggest what pages exist and how important they are.

The `sitemap.xml` file is specifically formatted and targeted at search engines.

- [Sitemaps.org](http://www.sitemaps.org/)

## Robots & humans

[⬇ Download sample robots.txt](robots.txt) • [⬇ Download sample humans.txt](humans.txt)

Two other files that are very useful are targeted at robots (search engines) and humans.

- `robots.txt` — used to block search engines from seeing parts of your site; includes a reference to the `sitemap.xml` file
- `humans.txt` — a way to show who created the site, what tools where used, resources, and references

*Helpful resources*

- <http://robotstxt.org/>
- <http://en.wikipedia.org/wiki/Robots_exclusion_standard>
- <http://humanstxt.org/>