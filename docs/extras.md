---
title: Adding extras to improve your How-to Guide
contributors: [Johan Gustafsson]
description: How to add and configure elements from the ELIXIR Toolkit theme that will improve the appearance and function of your How-to Guides.
affiliations: [Australian BioCommons]
toc: true
---


## Navigation tiles

An example can be viewed here: https://australianbiocommons.github.io/how-to-guides/

See the [ELIXIR Toolkit theme](https://elixir-belgium.github.io/elixir-toolkit-theme/overview_tiles#section-tiles-with-information) for more information.


### Include navigation tiles for all pages

To add tiles for the guide pages that you have created:

1. Ensure they are all in the same directory (e.g. the `docs/` directory for this guide)
2. Add the following code to the page you would like the tiles to appear on:

{% include image.html file="nav_image.png" alt="nav_image"%}

3. Add the following code to the bottom of the `_config.yml` file:

```
-
scope:
   path: "docs"
   type: "pages"
values:
   type: docs
```


### Example

{% include section-navigation-tiles.html type="docs" %}


### Include navigation tiles for a subset of pages

To create tiles for a specific subset of your guide pages:

1. Ensure the subset pages are in the same directory (e.g. the `docs/start` directory for this guide)
2. Add the same code as above to the page where you would like the tiles to appear: just change the type value (e.g. to `start`)
3. Change the code at the bottom of the [`_config.yml](/_config.yml) file so that:
   - the `path` field is the directory containing your pages: i.e. `docs/start`
   - the `type` field matches that for the code that includes the tiles on your page: i.e. `start`

```
-
scope:
   path: "docs/start"
   type: "pages"
values:
   type: start_here
```

### Example

{% include section-navigation-tiles.html type="start_here" %}
