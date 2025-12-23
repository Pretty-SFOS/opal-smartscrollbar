<!--
SPDX-FileCopyrightText: 2024 Mirian Margiani
SPDX-License-Identifier: GFDL-1.3-or-later
-->

# Changelog

## 1.0.2 (2025-12-23)

- Fixed packaging to actually include `opal.pri` and `.gitignore` files for
  easier integration into apps. Add `include(libs/opal.pri)`
  to your `harbour-myapp.pro` file to enable Opal in your app.
- **Note:** you *still* must modify your `yaml` or `spec` file for Harbour compliance!
  See [here](https://github.com/Pretty-SFOS/opal/blob/main/README.md#using-opal)
  for updated instructions.
- Fixed documentation to exclude some unnecessary generated parts.

## 1.0.1 (2025-12-22)

- Updated packaging to make it easier to integrate this module in apps

## 1.0.0 (2024-09-12)

- first public release
