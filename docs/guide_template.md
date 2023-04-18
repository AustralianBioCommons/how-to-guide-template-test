---
title: [Template for individual guide page]
contributors: [Johan Gustafsson]
description: Add a plain text description here.
affiliations: [Australian BioCommons]
---

## Usage instructions

{% include callout.html type="warning" content="Delete this section before publishing your content." %}

Before you start using this template!

1. Update the [header content for this guide document](https://github.com/AustralianBioCommons/how-to-guide-template/blob/main/docs/guide_template.md?plain=1#L3), an example of which is included below:

```
---
title: [How-to Guide template]
contributors: [Johan Gustafsson]
description: Add a plain text description here.
affiliations: [Australian BioCommons]
---   
```

{:start="2"}
2. Add your name to [`CONTRIBUTORS.yml`](https://github.com/AustralianBioCommons/how-to-guide-template/blob/04eba24a187202304df7dee73e867cfe5db10d31/_data/CONTRIBUTORS.yml)
3. If you are adding a new affiliation!, make sure to also update [`affiliations.yml`](https://github.com/AustralianBioCommons/how-to-guide-template/blob/04eba24a187202304df7dee73e867cfe5db10d31/_data/affiliations.yml). The affiliations noted in step #1 above require this information to be available. Example affiliation is available below: 

```
- name: Galaxy Australia
  image_url: /images/infrastructures/galaxy-aust-logo-portrait-CMYK.png
  expose: true
  type: infrastructure
  url: https://usegalaxy.org.au/
```
{% include callout.html type="note" content="You can add logos to the `/images` directory." %} 

{:start="4"}
4. Add citation information in the format provided below:

> **Note:** if this guide helped you, please cite it as follows
>
> [Citation information goes here]


## heading 1

> Your guide content goes here!
>
> See [this link](https://elixir-belgium.github.io/elixir-toolkit-theme/markdown_cheat_sheet#images) for info on adding images.

### heading 2

> Your guide content goes here!
>
> Below is an example message box, which comes in multiple styles: `note`, `important`, `tip` and `warning`.
>
> See [https://elixir-belgium.github.io/elixir-toolkit-theme/markdown_cheat_sheet#message-boxes) for info on adding message boxes.

{% include callout.html type="note" content="If you need help, the Galaxy community is both approachable and helpful. [Ask them questions!](https://help.galaxyproject.org/)" %}

#### heading 3

> Your guide content goes here!
