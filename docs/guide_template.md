---
title: [Template for an individual How-to Guide page]
contributors: [Johan Gustafsson]
description: Add a plain text description here.
affiliations: [Australian BioCommons]
---

## Usage instructions

{% include callout.html type="warning" content="Delete this section before publishing your content." %}

Before you start using this template!

1. Update the [header content for this guide document](/docs/guide_template.md), an example of which is included below:

```
---
title: [How-to Guide template]
contributors: [Johan Gustafsson]
description: Add a plain text description here.
affiliations: [Australian BioCommons]
---   
```

{:start="2"}
2. Add your name to `CONTRIBUTORS.yml`, which can be found in the `/_data` directory
3. If you are adding a new affiliation, also update `affiliations.yml`, which can also be found in the `/_data` directory. 
   - The affiliations noted in step #1 above require this information to be available. 
   - A new example affiliation is available below: note that it also includes an image/logo which should be added to the `/images` directory.

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
> See [this link](https://elixir-belgium.github.io/elixir-toolkit-theme/markdown_cheat_sheet#message-boxes) for info on adding message boxes.

{% include callout.html type="note" content="This is a message box. Use the content included here to emphasise important points." %}

#### heading 3

> Your guide content goes here!
