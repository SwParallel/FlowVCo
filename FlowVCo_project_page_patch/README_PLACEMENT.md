# FlowVCo project-page patch

This package is meant to be merged into the existing Academic Project Page Template.

Target public URL:
https://swparallel.github.io/FlowVCo/

Target code repository:
https://github.com/swparallel/FlowVCo

## Where to place it

In the `swparallel/swparallel.github.io` repository, use:

swparallel.github.io/
└── FlowVCo/
    ├── index.html
    ├── static/
    │   ├── css/          # keep from the original template
    │   ├── js/           # keep from the original template
    │   ├── images/       # merge the files in this patch
    │   └── pdfs/         # merge the files in this patch
    └── ...

So:
- replace `FlowVCo/index.html` with the `index.html` in this patch;
- merge `static/images/`;
- merge `static/pdfs/`;
- keep your original template's `static/css/` and `static/js/`.

All page assets use relative paths like `static/images/...`, which is correct for:
https://swparallel.github.io/FlowVCo/

## GitHub Pages setting

Repository:
swparallel/swparallel.github.io

Settings -> Pages:
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

Then `FlowVCo/index.html` will be published at:
https://swparallel.github.io/FlowVCo/

## Things still intentionally left for later

- arXiv button is shown as "Coming Soon" because no arXiv ID was provided.
- Author homepages are not linked because no author URLs were provided.
- If the final conference/proceedings metadata changes, update the visible "ICIP 2026"
  line, the citation meta tags, and the BibTeX block.

## Code button

The Code button already points to:
https://github.com/swparallel/FlowVCo
