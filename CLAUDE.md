# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

Philip Chase's personal Jekyll site (philipbchase.com), built on the **Minimal Mistakes** theme (`remote_theme: benbalter/retlab` in `_config.yml`, theme version pinned via `minimal-mistakes-jekyll` gem). Content is primarily long-form blog posts about his hobby projects (kite buggying, the "Buggy Bar" hardware he designs and 3D-prints, harness builds, etc.).

## Common commands

- **Serve locally**: `./serve.sh` (just runs `bundle exec jekyll serve`) — builds to `_site/` and serves with live reload at `http://localhost:4000`.
- **Install Ruby deps**: `bundle install` (Gemfile pulls `jekyll` and `minimal-mistakes-jekyll`; `Gemfile.lock` is checked in for reproducible builds).
- **Install JS deps** (only needed for theme asset rebuilding): `npm install`.
- **Rebuild/minify theme JS**: `npm run build:js` (runs `uglify` over the theme's vendor/plugin JS into `assets/js/main.min.js`, then `add-banner` via `banner.js` to stamp a copyright header). `npm run watch:js` watches `assets/js/**/*.js` and rebuilds on change.
- There is no test suite, linter, or CI build for this site (the `.travis.yml` references a `docs/` Algolia build that does not exist in this repo and is effectively stale/unused).

## Content architecture

- **Posts** live in `_posts/`, named `YYYY-MM-DD-title.md`, with YAML front matter (`title`, `excerpt`, `tags`). Site-wide post defaults (layout `single`, `author_profile`, `read_time`, `comments`, `share`, `related`) are set in the `defaults:` block of `_config.yml` — individual posts don't need to repeat them.
- **Large supporting assets for posts** (PDFs, ePubs, 3D model files, image galleries, FAQ exports) live under `assets/documents/<topic>/`, e.g. `assets/documents/buggy_bar_v2/`, `assets/documents/buggy_bar_build_book/`. Posts link to these directories rather than embedding the files.
- **Images** referenced from posts live in `images/` at the repo root (e.g. `/images/finished-v2-bar.jpg`).
- **`_data/navigation.yml`** drives the site's main nav links (currently empty/commented out — the site has no top nav beyond the theme defaults).
- **`_data/ui-text.yml`** holds theme UI string overrides.
- **Comments** are configured via Staticman (`staticman.yml`), targeting the `master` branch; comment data would land in `_data/comments/`.

## Theme internals

- `_layouts/`, `_includes/`, `_sass/` contain the Minimal Mistakes theme templates/partials/styles. Changes here affect site-wide presentation — prefer overriding via `_config.yml`, `_data/`, or post front matter before editing theme partials directly, since the theme is also pulled as a remote/gem dependency.
- `assets/css/main.scss` is the entry point for site styling (imports the theme's Sass partials from `_sass/`).
- `banner.js` and the `npm run build:js`/`uglify` pipeline only matter if you're modifying the theme's bundled JavaScript in `assets/js/`.

## Versioning

`CHANGELOG.md` follows Keep a Changelog / SemVer conventions and is updated by hand when notable content or theme changes ship (e.g. new posts, theme upgrades). Check it for context on recent additions before assuming something is undocumented.
