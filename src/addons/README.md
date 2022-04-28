# Addons Support
Addons are experimental. They are tested on a case by case basis but not all addons maybe tested. Any issues should be reported here or by making a ticket in the Cube Enix discord.

## Documentation
entry.js exports a function that begins running addons.

pull.js is a magical script that automatically pulls code from GitHub, parses it with regex, applies some more automated patches, and copies everything to the proper folders.

Directory structure:

addons - the addons (managed by pull.js)
addons-l10n - addon translations used at runtime (managed by pull.js)
addons-l10n-settings - addon translations used by the settings page (managed by pull.js)
libraries - libraries used by addons (managed by pull.js)
generated - additional generated files (managed by pull.js)
settings - the settings page and its translations
