A project built with Astro, plain HTML and css. It is built using GitHub Actions and deployed to GitHub pages.

# GitHub pages setup
I used the following guide for setting up. 
[Astro deploy guide](https://docs.astro.build/en/guides/deploy/github/)

it boils down to the following:
1. A `deploy.yml` file in the `.github/workflows/` folder
2. Adding `site` and `base` settings to the `astro.config.mjs` file
3. Changing the source in GitHub pages to an Action
