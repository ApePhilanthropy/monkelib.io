# Climate Change

[**IPCC Special Report on the impact of global warming of 1.5°C above pre industrial levels**](http://www.vliz.be/en/imis?module=ref&refid=323552) (2019, open access)

> mitigation options, risk assessment, socio-economic impact, sustainable development, eradication of poverty

## Historical Trends



## Impact

**Climate Change and Health, 25 years of inaction and impact on human wellbeing** [link]( http://sro.sussex.ac.uk/id/eprint/70859/) (2017)
```10.1016/S0140-6736(17)32464-9```
> The importance of limiting emissions to preserve human health and recommended interventions to limit damage on economic systems, communities and health services.

**Climate Change and Health (Review)** [link](https://bmjopen.bmj.com/content/11/6/e046333) (open access 2019)
```10.1136/bmjopen-2020-046333```
> A review on how metereological changes affect the spread of infectious disease, mortality, respiratory/neurological/cardiovascular/soft tissue diseases, mental and occupational health.

**Climate Change and Health (Lancet 2020 report)** [link]( https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(20)32290-X/fulltext) (2020)
```https://doi.org/10.1016/S0140-6736(20)32290-X```
> A comprehensive report on how climate change affects health, focusing on the impact on resources, communities and necessary interventions to mitigate damage.


## What people can do

A page's `title` tag is generated from the _selected_ sidebar item name. For better SEO, you can customize the title by specifying a string after the filename.

```markdown
<!-- docs/_sidebar.md -->
* [Home](/)
* [Guide](guide.md "The greatest guide in the world")
```

## Table of Contents

Once you've created `_sidebar.md`, the sidebar content is automatically generated based on the headers in the markdown files.

A custom sidebar can also automatically generate a table of contents by setting a `subMaxLevel`, compare [subMaxLevel configuration](configuration.md#submaxlevel).

```html
<!-- index.html -->

<script>
  window.$docsify = {
    loadSidebar: true,
    subMaxLevel: 2
  }
</script>
<script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
```

## Forecasts

When `subMaxLevel` is set, each header is automatically added to the table of contents by default. If you want to ignore a specific header, add `<!-- {docsify-ignore} -->` to it.

```markdown
# Getting Started

## Header <!-- {docsify-ignore} -->

This header won't appear in the sidebar table of contents.
```

To ignore all headers on a specific page, you can use `<!-- {docsify-ignore-all} -->` on the first header of the page.

```markdown
# Getting Started <!-- {docsify-ignore-all} -->

## Header

This header won't appear in the sidebar table of contents.
```

Both `<!-- {docsify-ignore} -->` and `<!-- {docsify-ignore-all} -->` will not be rendered on the page when used.