## ams.amc addon list

List available addons

### Synopsis

List available addons.

Formatting can be controlled with the '--format' flag.
Valid formats are 'table' (see example), 'json' and 'csv'.


```
ams.amc addon list [flags]
```

### Examples

```
$ amc addon list
+------+----------+---------+
| NAME | VERSIONS | USED BY |
+------+----------+---------+
| foo  | 1        |         |
+------+----------+---------+

```

### Options

```
      --format string   Output format - 'table', 'json' or 'csv' (default "table")
  -h, --help            help for list
```

### SEE ALSO

* [ams.amc addon](ams.amc_addon.md)	 - Manage addons

