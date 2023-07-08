# Contributing to the Statistician's Guide

Hey! We're thrilled that you'd like to contribute to this website. All suggested contributions are very welcome - we want this to be a useful resource for the whole analytical community!

## About this project 
This guidance site is aimed at analysts working within DfE. Where guidance already exists elsewhere it should be linked to rather than duplicated. If you need any assistance at all, please contact [statistics.development@education.gov.uk](mailto:statistics.development@education.gov.uk).

## Creating an issue

If you think of something worth including, improving, or want to contribute, please [raise an issue on GitHub](https://github.com/dfe-analytical-services/statisticians-guide/issues/new/choose).

## Submitting a pull request

If you want to contribute to our resources then all pull requests should be made against main. Pull requests will need approval from repository admins before merging.

1. [Fork][fork] or clone the repository
2. Configure and install the dependencies if you want to run the page in your machine, otherwise none.
3. Create a new branch: `git checkout -b my-branch-name`
4. Make your change
5. Check how your change looks on our website by hosting the website locally (follow [the steps below](#contribute-to-rap-community-of-practice-website) on how to do this)
6. Push to your fork or branch and [submit a pull request][pr]

Your pull request will then be reviewed. You may receive some feedback and suggested changes before it can be approved and your pull request merged. 

To increase the likelihood of your pull request being accepted:

- If you are making visual changes, include a screenshot of what the affected element looks like, both before and after.
- Keep your change as focused as possible. If there are multiple changes you would like to make that are not dependent upon each other, consider submitting them as separate pull requests.
- Write your commit messages in the imperative, for example use "Fix heading" and not "Fixed heading" or "Fixes heading".

## Editing the contents

Don't forget to check that the links, images, headings, and contents are all working correctly.

Save any images in the `www` folder, and example data sets in the `data_examples` folder.

If you add any new R packages, remember to use `renv::snapshot()` and commit the packages to the `renv.lock` file.

### Editing existing pages

Existing pages can be edited by directly updating the relevant `.qmd` file.

### New page

To add a new file to the repository and website, you can add the file as you would normally and then add it to the `index.qmd` and the `_quarto.yml` to include the file within the site navigation list. The folders contain `.qmd` files and provide the headings that pages sit under.

### Quarto guidance
For more information, and examples of what is possible within a static quarto site, see the main [Quarto website](https://quarto.org/).

<!-- TODO: add more details on

- adding images (in the right folder, code to do so)
- adding links (within page, within site, external to site)]
- adding videos / other content
- redirecting pages where changing / removing
- checking for broken links when changing headings
- building locally before raising a pull request

-->

## Resources

- [Contributing to Projects](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)
- [Using Pull Requests](https://help.github.com/articles/using-pull-requests/)
- [GitHub Help](https://help.github.com)
