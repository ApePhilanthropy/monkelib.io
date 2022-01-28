# Equal Opportunity

If you need more pages, you can simply create more markdown files in your docsify directory. If you create a file named `guide.md`, then it is accessible via `/#/guide`.

For example, the directory structure is as follows:

```text
.
└── docs
    ├── README.md
    ├── guide.md
    └── zh-cn
        ├── README.md
        └── guide.md
```

Matching routes

```text
docs/README.md        => http://domain.com
docs/guide.md         => http://domain.com/#/guide
docs/zh-cn/README.md  => http://domain.com/#/zh-cn/
docs/zh-cn/guide.md   => http://domain.com/#/zh-cn/guide
```

## Privacy

In order to have sidebar, then you can create your own `_sidebar.md` (see [this documentation's sidebar](https://github.com/docsifyjs/docsify/blob/master/docs/_sidebar.md) for an example):

First, you need to set `loadSidebar` to **true**. Details are available in the [configuration paragraph](configuration.md#loadsidebar).

```html
<!-- index.html -->

<script>
  window.$docsify = {
    loadSidebar: true
  }
</script>
<script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
```

Create the `_sidebar.md`:

```markdown
<!-- docs/_sidebar.md -->

* [Home](/)
* [Guide](guide.md)
```

You need to create a `.nojekyll` in `./docs` to prevent GitHub Pages from ignoring files that begin with an underscore.

!> Docsify only looks for `_sidebar.md` in the current folder, and uses that, otherwise it falls back to the one configured using `window.$docsify.loadSidebar` config.

Example file structure:

```text
└── docs/
    ├── _sidebar.md
    ├── index.md
    ├── getting-started.md
    └── running-services.md
```

## Reproductive Rights


**Poststerilization regret** https://www.sciencedirect.com/science/article/abs/pii/S0029784498005390?via%3Dihub
```tldr
most women DO NOT regret tubal ligation 1999
```
abortion charity (need to DYOR wip)

https://prochoice.org/patients/naf-hotline/

NAF hotline 1-800-772-9100 (funding hotline which also can provide logistical support & coordination to your closest out of state clinic)

https://fundtexaschoice.org

https://teafund.org

https://abortionfunds.org

**Gender-affirming hormone therapy (GAHT) and body composition** [link](https://academic.oup.com/jcem/article/105/3/e704/5572616) (open access 2019)
```https://doi.org/10.1210/clinem/dgz029```
> GAHT makes body composition reach a mid point between BMI matched trans and cis individuals

## Socio-Economic Rights

A page's `title` tag is generated from the _selected_ sidebar item name. For better SEO, you can customize the title by specifying a string after the filename.

```markdown
<!-- docs/_sidebar.md -->
* [Home](/)
* [Guide](guide.md "The greatest guide in the world")
```

## Freedom

need DYOR

freedom of religion

https://ffrf.org
https://www.secularism.org.uk

