# Themes

The standard theme that comes with a new project is [hexojs/hexo-theme-landscape](https://github.com/hexojs/hexo-theme-landscape).


## Configuring the theme

Copied from the theme's docs - these are field you can override in your top-level [config](/_config.yml).

```yaml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml
banner: images/banner.jpg

# Content
excerpt_link: Read More
fancybox: true
recent_posts_limits: 5

# Sidebar
sidebar: right
widgets:
  - category
  - tag
  - tagcloud
  - archives
  - recent_posts

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
```


## Adding a theme

The standard way of installing a theme is by cloning the repo.

Example:

```sh
git clone --depth 1 https://github.com/hexojs/hexo-theme-landscape themes/landscape
```

The setup used for this quickstart project is submodules rather:

```sh
git submodule add https://github.com/hexojs/hexo-theme-landscape themes/landscape
```

See [submodules](https://gist.github.com/MichaelCurrin/38816f5a511b265eddaa60aa73362b04) guide.

Once the theme is in the repo, apply it in the [\_config.yml](/_config.yml) file.

e.g.

```yaml
theme: landscape
```
