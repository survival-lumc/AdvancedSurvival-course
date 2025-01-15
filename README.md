# Advanced Survival Analysis (Leiden) course landing site

## Maintenance instructions

The Advanced Survival Analysis (ASA) course landing site is based on [Quarto](https://quarto.org/docs/websites/). Updating the website is as simple as:

1. Make changes to one or more .qmd files (each .qmd file corresponds to a page on the website) locally, after cloning this repository.

2. Use `quarto::quarto_render()` to render the changes to the docs/ directory, then double-check changes locally.

3. Push locally rendered/modified files to Github using `git add` and `git push`. You can check the URL of the site by following the steps [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site#creating-your-site). Before someone can push changes to this repository, they need to first be given appropriate [permissions](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/managing-teams-and-people-with-access-to-your-repository).

Other points:

- The schedule can be updated by modifying `asa-2024-schedule.xlsx`, which is then read-in and made into tables by `resources/schedule.qmd`. If major formatting changes are made to the excel files, these will need to be taken into account by the .qmd file.

- The structure/organization of the website can be modified using the `_quarto.yml` file.
