## ams.amc info

Provide general information about the connected AMS service

### Synopsis

Provide general information about the connected AMS service.

Formatting can be controlled with the '--format' flag.
Valid formats are 'json' and 'yaml'.

```
ams.amc info [flags]
```

### Examples

```
$ amc info
api_extensions:
- addon_backup_hook
...
- application_hooks
api_status: stable
api_version: "1.0"
auth: trusted
auth_methods:
- 2waySSL
config:
  application.addons: ""
...
scheduler.strategy: spread
service_version: 1.14.0
```

### Options

```
      --format string   Output format - 'json' or 'yaml' (default "yaml")
  -h, --help            help for info
```

### SEE ALSO

* [ams.amc](ams.amc.md)	 - Anbox Management Client

