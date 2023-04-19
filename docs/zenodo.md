---
title: Creating GitHub releases and Zenodo DOIs for How-to Guides
contributors: [Johan Gustafsson]
description: How to create GitHub releases for your How-to Guide and link this to Zenodo to generate digital object identifiers (DOIs).
affiliations: [Australian BioCommons]
toc: false
---


### [Create a GitHub release]()

### Link your repository to Zenodo

More information is [available in GitHub docs](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content). 

### Update your guides

#### Add the DOI into your how-to-cite instructions on the `index.md` page

#### Update the DOI field in the `CITATION.cff` file. 

A blank `CITATION.cff` example is provided below. Don't forget to fill out the other metadata in this file!

```
cff-version: 0.0.0
message: "Please cite as below."
authors:
  - family-names: [family name goes here]
    given-names: [given names go here]
    orcid: [ORCID goes here]
title: "Title of repository goes here"
version: 0.0.0
doi: [DOI goes here]
date-released: YYYY-MM-DD
```
