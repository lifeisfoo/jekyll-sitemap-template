# jekyll-sitemap-template

Generate your jekyll sitemap without plugin.

## Install

1. Copy `sitemap.xml` inside your jekyll website folder.
2. Run `jekyll build`
3. Your sitemap is ready inside `_site/sitemap.xml`

## Config - front matter

Optional

```
    sitemap:
        lastmod: 2014-01-23
        priority: 0.7
        changefreq: 'monthly'
        exclude: 'yes' 
```

### Thanks
To [David Ensinger](http://davidensinger.com/2013/11/building-a-better-sitemap-xml-with-jekyll/) for the inital code.
