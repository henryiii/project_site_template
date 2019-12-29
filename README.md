## Project site template


See the [preview here](https://henryiii.github.io/project_site_template). To use:

1. Click ["Use this template"](https://github.com/henryiii/project_site_template/generate) on the [GitHub landing page](https://github.com/henryiii/project_site_template).
2. Fill in the repository settings (name, etc).
3. Set up the details for your site:
    1. `_config.yml` has basic settings like names.
    2. `_data/navigation.yml` has the menu structure.
    3. `index.md` is the landing page.
    4. Other pages are in `pages/`.
    5. You can customize the footer message at `_includes/footer.html`

Other tips can be found at [chrisrhymes/bulma-clean-theme](https://github.com/chrisrhymes/bulma-clean-theme), the theme for the site. A few important ones:

* The large banner with image background is called the `hero`:
    * `hero_image=address` will set it.
    * `hide_hero=false` will enable the hero on other pages.
* Posts are disabled, but can be enabled manually (the theme supports them)
* Other menu options include sidebar, tabs, and footer links. See the theme page for more details.

