# Vinbound plugin updates

Release files for WordPress plugins that Vinbound Marketing installs on the sites it manages. This repository is published with GitHub Pages at `https://updates.vinboundmarketing.com/`, and installed plugins read their update information from there.

## Contents

| Path | Purpose |
| --- | --- |
| `vinbound-seo-ai/info.json` | Current version, requirements, changelog, and download address for the Vinbound SEO & AI plugin. |
| `vinbound-seo-ai/vinbound-seo-ai.zip` | The installable plugin for that version. |

## Publishing a release

The zip is published first. Once the new zip is confirmed live, `info.json` follows, so a site is never told about a version before its zip can be downloaded. The files come from the plugin project's build and publish scripts. Do not edit them by hand here.

The file names and the folder name are part of the address every installed copy checks. Do not rename them.
