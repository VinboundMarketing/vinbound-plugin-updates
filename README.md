# Vinbound plugin updates

Release files for WordPress plugins that Vinbound Marketing installs on the sites it manages. This repository is published with GitHub Pages at `https://updates.vinboundmarketing.com/`, and installed plugins read their update information from there.

## Contents

| Path | Purpose |
| --- | --- |
| `vinbound-seo-ai/info.json` | Current version, requirements, changelog, and download address for the Vinbound SEO & AI plugin. |
| `vinbound-seo-ai/vinbound-seo-ai.zip` | The installable plugin for that version. |

## Publishing a release

Both files are replaced together in a single commit, so a site never sees a new `info.json` that points at an old zip. The files come from the plugin project's build script. Do not edit them by hand here.

The file names and the folder name are part of the address every installed copy checks. Do not rename them.
