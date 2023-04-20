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

To add tiles for the guide pages that you have created, add the following code to the page you would like the tiles to appear on:

{% include image.html file="nav_image.png" alt="nav_image"%}


### Example

{% include section-navigation-tiles.html %}


### Include navigation tiles for a subset of pages

To create tiles for a specific subset of your guide pages:

1. Add a `type` field to the header for each of the guides that are included in your subset. For example:

```
---
title: Creating a new How-to Guide repository
type: start_here
contributors: [Johan Gustafsson]
description: How to create and begin updating a repository for your new How-to Guide, based on the template repository provided by the Australian BioCommons.
affiliations: [Australian BioCommons]
toc: false
---
```

{:start="2"}
2. Add the same code as above to the page where you would like the tiles to appear: just add a type value (e.g. to `type="start_here"`)


### Example

{% include section-navigation-tiles.html type="start_here" %}
