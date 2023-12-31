:description: Here lists the releases notes of Shibuya Sphinx theme.

Changelog
=========

Shibuya uses date based release segments. For pre-releases, it follows :pep:`440`.

2024.1.1
--------

- **Breaking**: ``--sy-rc-theme`` CSS variable has been removed in favor of :ref:`accent-colors`.
- **Breaking**: Several CSS variable names are changed.
- **Breaking**: ``light_css_variables`` and ``dark_css_variables`` theme option has been removed.
- **New**: Added many pre-defined :ref:`accent-colors`.
- **New**: Added style for ``sphinx-gallery`` and ``xarray``, via :issue:`20`.
- **New**: Added **simple** and **landing** layout templates.
- **New**: Added two image containers.
- **Fix**: Improve style for ``sphinx-design``, ``sphinx-jupyter``, and etc.
- **Fix**: Improve style for search page.

2023.10.26
----------

- Add ``gitlab_url`` and ``bitbucket_url``
- Update Twitter icon to X icon
- Integrate with numpydoc extension
- Improve CSS for ``sphinx.ext.autosummary`` extension
- Add ``light-only`` and ``dark-only`` class

2023.10.5
---------

- Fix deprecated links in relations.html and searchbox.html

2023.9.3
--------

- Improve sidebar CSS for compatibility
- Add an alias template of ``localtoc.html``
- Add deprecated warning templates of ``relations.html`` and ``searchbox.html``
- Improve CSS for ``nbsphinx`` extension
- New feature for :ref:`globaltoc` configuration
- Improve CSS for global TOC

2023.7.28
---------

- Remove current ``hreflang`` link
- Fix nested TOC links, via :issue:`7`
- Use theme color for code blocks, via :issue:`5`
- Remove version parameter on assets URLs

2023.7.16
---------

- Fix multiple languages links for index pages
- Add ``hreflang`` links for SEO
- Add locale data of theme templates

2023.7.15
---------

- Change multiple languages configuration

2023.7.14
---------

- Add YouTube link
- Improve style for versions and languages
- Improve breadcrumbs style
- Add expand and collapse global TOC

2023.7.11
---------

- Fix style for genindex
- Add breadcrumbs for small screen
- Move TOC controllers to breadcrumbs block
- Move RTD versions to left sidebar
- Add multiple languages switcher

2023.6.30
---------

- Fix normalize toc with ``xml.etree``
- Fix local toc style
- Fix style of main part for large screen

2023.6.27
---------

- Fix style of copybutton for dark code mode
- Fix style for modindex page

2023.6.25
---------

- Apply ``dark_css_variables`` in templates
- Fix code block style in dark code mode for sphinx design
- Fix colors for API docs in dark code mode
- Fix stderr background for ``nbsphinx``

2023.6.21
---------

- Add support for ``sphinx-togglebutton`` extension
- Add support for ``nbsphinx`` extension
- Rename template ``partials/sidebar-links`` to ``partials/globaltoc-above``
- Add template ``extensions/buysellads``

2023.6.18
---------

- Fix edit this page link
- Fix nav links style
- Update style for :ref:`sphinx-jupyter`

2023.6.8
--------

- Add external-link icon for external nav links
- Add highlight background color for search results
- Fix search results page nav links for mobile devices
- Add native built-in carbon ads

2023.6.7
--------

- Fix ``scroll-margin-top`` for sections
- Change "edit this page" link
- Add an option to use your own Ethical Ads publisher ID
- Update navbar links style
- Add navbar children links

2023.3.19
---------

- Enable ``repo-stats`` sidebar by default
- Improve colors for dark mode

2023.3.11
---------

- Auto resize announcement banner
- Fix context for readthedocs

2023.3.7
--------

- Add "edit this page" in sidebar
- Add GitHub / Gitlab repository stats
- Fix versions on css files


2023.3.5
--------

- Add dark code mode
- Improve style for print media
- Improve style for sphinx-design


2023.3.2
--------

- Improve style for quotes
- Add github link on nav bar


2023.3.1
--------

- Fix margins for "kbd"
- Add style for sphinx-tabs
- Improve style for code blocks


2023.2.25a2
-----------

- Fix templates when ``pageurl`` is None
- Improve opengraph with more theme options
- Tweak style, fix for a11y
- Move theme switch to site head
- Add logos and colors

2023.2.23a1
-----------

Initial release.
