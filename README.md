# Drupal8 Default Sub theme in Acquia Lightning.

The module helps to enable your defined sub theme as default theme on site install.

## Notes to consider:

- Place the module in your project's module directory.
- Add `d8_default_theme` in `/docroot/sites/default/lightning.extend.yml`.

```
# List of additional modules to enable after Lightning is installed.
modules:

  - d8_default_theme
```
