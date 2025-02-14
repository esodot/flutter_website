---
title: Supported deployment platforms
short-title: Supported platforms
description: The platforms that Flutter supports by platform version.
---

## Support tiers

We define three tiers of support for the platforms on
which apps built with Flutter might be deployed:

1. **Supported**<br>
   Google-tested platforms that
   are automatically tested on every commit
   by continuous integration testing.
1. **Best effort**<br>
   Platforms that we intend to support through
   coding practices,
   but are only tested on an ad-hoc basis.
1. **Unsupported**<br>
   Platforms that we don't test or support.
   
{% comment %}
**IMPORTANT NOTE**:
When changing the minimum support version of macOS, Windows, or Linux,
make sure to make a corresponding change in the get started pages:
  * /src/get-started/install/macos.md
  * /src/get-started/install/windows.md
  * /src/get-started/install/linux.md
{% endcomment -%}


## Deploying Flutter

As of the current stable release,
support for deploying Flutter apps is shown in the
following table:

<div class="table-wrapper" markdown="1">
|Platform version|Supported|Best effort|Unsupported|
|----------------|---------|-----------|-----------|
| Android SDK    |21-34|19-20|18-|
| iOS            |16|12-15, 17|11-, arm7v 32-bit|
| Linux Debian   |10-12|9-|any 32-bit|
| Linux Ubuntu   |20.04 LTS|20.10-23.04|any 32-bit|
| macOS          |Ventura (13)|Mojave (10.14) to Monterey (12), Sonoma (14)|High Sierra (10.13-) |
| web - Chrome   |latest 2 releases|96+| |
| web - Firefox  |latest 2 releases|99+| |
| web - Safari   |latest 2 releases|14+| |
| web - Edge     |latest 2 releases|96+| |
| Windows        |10|7, 8, and 11|Vista-, any 32-bit|
{:.table.table-striped.table-centered-after-first}
</div>

{{site.alert.note}}
  A `plus` sign (`+`) in the table indicates "and higher releases".
  A `minus` (`-`) sign directly following a version (with no spaces)
  indicates "and lower releases".
{{site.alert.end}}
