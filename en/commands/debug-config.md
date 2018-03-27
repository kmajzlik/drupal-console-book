# debug:config
List configuration objects names and single configuration object.

**Usage:**
```
drupal debug:config [arguments]
dc
```

## Available arguments
Argument | Details
---------|-------------
name | Configuration object name, for example "system.site".

## Examples
* List all configuration object names.
```
drupal debug:config
```
* Display system site configurations values.
```
drupal debug:config system.site
```
* List all system configuration names.
```
drupal debug:config | grep system
```
