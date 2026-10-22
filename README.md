# VCMI-FV-Launcher Realms Repository

This repository hosts "Realms" that the VCMI-FV-Launcher can download and install directly.
A realm is a self-contained VCMI mod combination with its own settings and save space;
realms never interfere with each other.

## How to use

1. Start the VCMI-FV-Launcher (official releases already include this repository — no setup needed).
2. Open the `Realms` tab and go to the `Switch Realm` page.
3. Click `Online Realms` to browse the available realms.
4. Pick one you like and click `Download` (you can `Cancel` at any time).
5. Back on `Switch Realm`, select the realm you just installed and enter it, then start the game as usual.

The list supports searching by name and filtering by tag, and is grouped into
`Updatable` / `Available` / `Installed`.

> Is the list empty? Open `Repository Sources` and make sure the index URL below is in it;
> if not, click `Add` and paste it.

## JSON index file URL

https://raw.githubusercontent.com/future-view/vcmi-fv-launcher-realms/main/index.json

## FAQ

- **Download is slow or fails**: realm packages are downloaded straight from GitHub, so make sure
  `raw.githubusercontent.com` is reachable. Already installed realms work offline.
- **"Missing external mods"**: that realm needs mods you have to install yourself. Follow the prompt
  and install them from the `Mods` page or the official preset, then enter the realm again.
- **A newly published realm does not show up**: the list is cached for about 30 minutes —
  click `Refresh` to fetch it right away.
- **Want your original setup back**: just switch to another realm on the `Switch Realm` page.
- **Can I edit a downloaded realm?**: remote realms are read-only by default so updates cannot
  overwrite your changes; when an update appears you can choose to update or keep the current one.

## Want to share your own realm

Export it with the launcher's "Export Realm" to produce a `.vcmirealm` package, then open a
Pull Request in this repository or contact the maintainers.
