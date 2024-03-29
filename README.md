# Creator Assertions Working Group Metadata Assertion

This repository contains the source material for the current working draft of the [Creator Assertions Working Group](https://creator-assertions.github.io/)'s metadata assertion. A rendered version of this specification can be found [here](https://creator-assertions.github.io/metadata/).

## Governance

This specification is subject to the [Community Specification License 1.0](https://github.com/CommunitySpecification/1.0).

## Site build process

The site content is built using [Antora](https://antora.org), which takes Asciidoc (.adoc) plain text files and renders them to HTML and other formats.

The primary content of this document is available in [docs/modules/ROOT/pages/index.adoc](https://github.com/creator-assertions/metadata-assertion/blob/main/docs/modules/ROOT/pages/index.adoc) in this repo.

## Local preview

You can render the site of this content locally if you wish to test the appearance of changes you are making. To do this:

1. Ensure that you have a current version of node.js installed. ([Installers are here.](https://nodejs.org/en/download/))
2. Install Antora and other project dependencies.

```
$ cd (root of this repo)
$ npm install
```

Each time you wish to preview content, run the following:

```
$ npx antora antora-playbook-local.yml
Site generation complete!
Open file:///(root of this repo)/build/site/index.html in a browser to view your site.
```

Antora does not have a live-preview feature, so you will need to re-run this command to ensure that the rendered site reflects any changes you have made.
