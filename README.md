# Manjaro Search
![GitHub](https://img.shields.io/github/license/Mirdarthos/firefox-extension-manjaro-search)

A set of Web Extensions that adds Manjaro (forum, packages, wiki, Arch Linux AUR) as a search engine to the Firefox browser
(using the [chrome_settings_overrides](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/chrome_settings_overrides) manifest key).
Submits the query via GET request for compatibility with [Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/).

Available search engines:

name                                   | shortcut   | Install
---------------------------------------|------------|-----------
Manjaro Packages Search              | `@maanp`   | [AMO][manjaro-pkgs]
Manjaro Wiki Search                  | `@manw`   | [AMO][manjaro-wiki]
Arch Linux User Repository (AUR) Search | `@aur`    | [AMO][arch-aur]
Manjaro Forum (by keywords) Search     | `@manf` | [AMO][manjaro-forum]

## Install

- Install the extensions manually via AMO (**A**ddons **MO**zilla) following the links above

This is my First extension, adapted from https://github.com/noraj/firefox-extension-arch-search, so credit where credit is due. Probably not me.