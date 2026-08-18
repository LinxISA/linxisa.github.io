# linxisa.github.io

This repository owns the default LinxISA organization documentation site at
<https://linxisa.github.io/>.

The workflow checks out `LinxISA/linx-isa@main`, validates both documentation
configurations strictly, and deploys the Chinese MkDocs build from
`mkdocs.zh.yml` as the root Pages site. The English build remains a required
validation surface but is not published as the default navigation.

Pages is deployed with GitHub's artifact-based workflow. No generated site is
committed to a `gh-pages` branch.
