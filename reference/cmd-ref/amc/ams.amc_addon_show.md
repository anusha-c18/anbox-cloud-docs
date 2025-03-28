## ams.amc addon show

Show more information about a specific addon

### Synopsis

Show more information about a specific addon.

Formatting can be controlled with the '--format' flag.
Valid formats are 'json' and 'yaml'.

```
ams.amc addon show <name> [flags]
```

### Examples

```
$ amc addon show foo
name: foo
versions:
  0:
    size: 273B
    created-at: 2019-07-15 14:02:30 +0000 UTC
used_by: []

```

### Options

```
      --format string   Output format - 'json' or 'yaml' (default "yaml")
  -h, --help            help for show
```

### SEE ALSO

* [ams.amc addon](ams.amc_addon.md)	 - Manage addons

