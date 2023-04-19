---
title: How-to Guide for creating a How-to Guide
toc: false
---

## Usage instructions

{% include callout.html type="warning" content="Delete this section before publishing your content." %}

### About this template

This template is intended to house material for step-by-step guides and other associated documentation that support the reuse of bioinformatics tools, workflows and data on Australian compute systems and infrastructure.

The template aims to:
- Reduce time spent creating guides by providing a standard structure to develop and maintain guidance material; and,
- Allow linking to Zenodo, and creation of DOIs for each release. More information is [available in GitHub docs](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content).

### To start using this template

1. Consult the instructions in the [**README**](/README.md).
2. Review the structure of the [**guide_template**](/docs/guide_template.md) and the instructions included there.
3. Update the title for your guide in the [markdown header for this page](https://github.com/AustralianBioCommons/how-to-guide-template/blob/main/index.md?plain=1#L2): this will be the title for the deployed web page.
4. Make sure all How-to Guide documents are added to the [**/docs**](https://github.com/AustralianBioCommons/how-to-guide-template/tree/main/docs) directory: this is to ensure proper functionality and organisation of the repository should you wish to add more than one guide document.
5. Update the licence, if needed, to another open source option (it is currently Apache Version 2.0): visit [https://choosealicense.com/](https://choosealicense.com/) for more information.
6. Don't forget to add to the `About` and `Acknowledgments` sections below.
7. You can also add navigation tiles that link to each guide page: see the `Guide sections` instructions below for more information.

{% include callout.html type="note" content="the instructions above are for a simple guide that can accommodate a few pages only: if you require more complicated structures, please contact @supernord" %}


## About

You are viewing a web page that describes How-to create new How-to Guides using a GitHub repository template. What are How-to Guides? They are step-by-step guides that support the reuse of bioinformatics tools, workflows and data on Australian compute systems and infrastructure.

The template described in these docs aims to:
- **Reduce the time you spend** creating guides by providing a standard structure to develop and maintain guidance material;
- Allow you to **easily deploy these guides** using GitHub pages and a remote theme provided by ELIXIR; and,
- Allow linking to Zenodo and **creation of DOIs** for each release. You created the content, others should be able to cite it!

{% include callout.html type="note" content="the instructions below are for a simple guide that can accommodate a few pages only: if you require more complicated structures, please contact @supernord" %}


## Guide sections

{% include callout.html type="important" content="Click the tiles below to view the pages for creating new How-to Guides!" %} 

{% include section-navigation-tiles-simple.html type="template" %}


## Please cite this guide as follows

> [Citation information goes here]


## Acknowledgements

This guide makes use of the ELIXIR toolkit theme: [![theme badge](https://img.shields.io/badge/ELIXIR%20toolkit%20theme-jekyll-blue?color=0d6efd)](https://github.com/ELIXIR-Belgium/elixir-toolkit-theme)


## References

> CFF file reference
> ELIXIR Tool Kit theme citation
> BioCommons reference
> 


