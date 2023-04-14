---
title: Welcome to the How-to Guides template
toc: false
---

> **Before you start using this template repository**

> 1. Update the title for your guide in the [markdown header for this page](https://github.com/AustralianBioCommons/how-to-guide-template/blob/main/index.md?plain=1#L2): this will be the title for the deployed web page.
> 2. Consult the instructions in [**contributing.md**](/docs/contributing.md).
> 3. Review the structure of the [**guide_template**](/docs/guide_template.md).
> 4. Make sure all How-to Guide documents are added to the [**/docs**](https://github.com/AustralianBioCommons/how-to-guide-template/tree/main/docs) directory: this is to ensure proper functionality and organisation of the repository should you wish to add more than one guide document.
> 5. Update the licence, if needed, to another open source option (it is currently Apache Version 2.0): visit https://choosealicense.com/ for more information.
> 6. Don't forget to add to the acknowledgments section below.
> 7. Delete all these comments before publishing your content!

> **Note:** the instructions above are for a simple guide that can accommodate a few pages only: if you require more complicated structures, please contact @supernord 


## About 

> Add 2-3 sentences here explaining the purpose of the specific guide you are creating.

## Guide sections


### Adding ALL guides as navigation tiles

**OPTIONAL:** You can use this section to add tiles for all guide documents in `/docs` using the following code:

1. Add the following code to this page:

        {% include section-navigation-tiles.html type="docs"%}


2. Add the following section to the bottom of the [`_config.yml](/_config.yml) file

        -
        scope:
            path: "docs"
            type: "pages"
        values:
            type: guide_documents


An example can be viewed here: https://australianbiocommons.github.io/how-to-guides/

### Adding SPECIFIC navigation tiles

To create tiles for a specific subset of your guides add the following to the bottom of the [`_config.yml](/_config.yml) file.

    -
    scope:
      path: "docs/genome_assembly"
      type: "pages"
    values:
      type: assembly_guides

The `path` field above (value = `docs/genome_assembly`) refers to a new directory called `genome_assembly`, which needs to be created in the `docs` directory.
The guides you wish to appear as tiles need to be in this new directory. The `type` field above (value = `assembly_guides`) is the ID for this subset of guide documents.

Finally add the following code to this page, including the `type`:

    {% include section-navigation-tiles.html type="assembly_guides"%}



## Acknowledgements

> Don't delete anything from this section, only add.

This guide makes use of the ELIXIR toolkit theme: [![theme badge](https://img.shields.io/badge/ELIXIR%20toolkit%20theme-jekyll-blue?color=0d6efd)](https://github.com/ELIXIR-Belgium/elixir-toolkit-theme)


## References

> Add references as needed.



