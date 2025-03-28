## ams.amc image list

List available images

### Synopsis

List available images.

Formatting can be controlled with the '--format' flag.
Valid formats are 'table' (see example), 'yaml', 'json' and 'csv'.


```
ams.amc image list [flags]
```

### Examples

```
$ amc image list
+----------------------+------+--------+----------+----------------+---------+
|          ID          | NAME | STATUS | VERSIONS |  ARCHITECTURE  | DEFAULT |
+----------------------+------+--------+----------+----------------+---------+
| bkkbiaphpuo3mh78ain0 | foo  | active | 1        |  x86_64        | true    |
+----------------------+------+--------+----------+----------------+---------+

```

### Options

```
      --format string   Output format - 'table', 'json' or 'csv' (default "table")
  -h, --help            help for list
```

### SEE ALSO

* [ams.amc image](ams.amc_image.md)	 - Manage images

