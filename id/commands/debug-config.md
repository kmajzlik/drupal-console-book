# debug:config
Tunjukkan konfigurasi terkini.

**application.gitbook.messages.usage:**
```
drupal debug:config [arguments]
dc
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Nama konfigurasi.

## application.gitbook.messages.examples
* List all configuration object names.
```
drupal config:debug
```
* Display system site configurations values.
```
drupal config:debug system.site
```
* List all system configuration names.
```
drupal config:debug | grep system
```