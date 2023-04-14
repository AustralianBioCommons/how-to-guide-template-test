---
title: [How-to Guide template]
contributors: [Johan Gustafsson]
description: Add a plain text description here.
affiliations: [Australian BioCommons]
---

> **Start of instruction section - TO BE DELETED WHEN GUIDE IS COMPLETE**

Before you start using this template!

1. Make sure to update the [header content for this guide document](https://github.com/AustralianBioCommons/how-to-guide-template/blob/main/docs/guide_template.md?plain=1#L3), an example of which is included below:

```
---
title: [How-to Guide template]
contributors: [Johan Gustafsson]
description: Add a plain text description here.
affiliations: [Australian BioCommons]
---   
```

- Add your name to [`CONTRIBUTORS.yml`](https://github.com/AustralianBioCommons/how-to-guide-template/blob/04eba24a187202304df7dee73e867cfe5db10d31/_data/CONTRIBUTORS.yml)
- If you are adding a new affiliation!, make sure to also update [`affiliations.yml`](https://github.com/AustralianBioCommons/how-to-guide-template/blob/04eba24a187202304df7dee73e867cfe5db10d31/_data/affiliations.yml). The affiliations noted in step #1 above require this information to be available. Example affiliation is available below: 

```
- name: Galaxy Australia
  image_url: /images/infrastructures/galaxy-aust-logo-portrait-CMYK.png
  expose: true
  type: infrastructure
  url: https://usegalaxy.org.au/
```
{% include callout.html type="note" content="You can add logos to the `/images` directory." %} 

- Add citation information in the format provided below:

> **Note:** if this guide helped you, please cite it as follows
>
> Citation information goes here!

- Delete these instructions!

> **End of instruction section**


## heading 1

Content goes here!

Add an image by adding this code:

`{% include image.html file="Australian-Biocommons-Logo-Horizontal-144dpi-Transparent.png" caption="Fig 1. Australian BioCommons logo"%}`

{% include image.html file="Australian-Biocommons-Logo-Horizontal-144dpi-Transparent.png" caption="Fig 1. Australian BioCommons logo"%}

See [this link](https://elixir-belgium.github.io/elixir-toolkit-theme/markdown_cheat_sheet#images) for more info on images.

### heading 2

Content goes here!

Below is an example callout, which comes in multiple styles: `note`, `important`, `tip` and `warning`.
The bold section of the script below should include one of these styles. The content text in *italics* can be modified as needed.
        
`{% include callout.html type="**note**" content="*callout content text*" %}`

{% include callout.html type="note" content="If you need help, the Galaxy community is both approachable and helpful. [Ask them questions!](https://help.galaxyproject.org/)" %}

See examples of these callouts [here](https://elixir-belgium.github.io/elixir-toolkit-theme/markdown_cheat_sheet#message-boxes).

#### heading 3

Content goes here!
