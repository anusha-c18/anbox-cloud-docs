## ams.amc application list

List created applications

### Synopsis

List created applications.

Formatting can be controlled with the '--format' flag.
Valid formats are 'table' (see example), 'yaml', 'json' and 'csv'.

You can apply filters to narrow down the list of applications.
They are of the following form:

	--filter attribute=value

'attribute' can be one of the following:

	+------------------------+----------------------------+
	|     Name               |       Argument type        |
	+------------------------+----------------------------+
	| instance-type          | comma-separated list       |
	| addons                 | comma-separated list       |
	| tag                    | (deprecated)               |
	| tags                   | comma-separated list       |
	| published              | Boolean (true/false)       |
	| immutable              | Boolean (true/false)       |
	| status                 | string (ready, error etc.) |
	| vm                     | Boolean (true/false)       |
	| parent_image_variant   | string                     |
	+------------------------+----------------------------+



```
ams.amc application list [flags]
```

### Examples

```
$ amc application list
+----------------------+------+---------------+--------+------+-----------+--------+---------------------+
|          ID          | NAME | INSTANCE TYPE | ADDONS | TAGS | PUBLISHED | STATUS |    LAST UPDATED     |
+----------------------+------+---------------+--------+------+-----------+--------+---------------------+
| bkmtdm9hpuo01q954fng | foo  | a2.3          |        |      | true      | ready  | 2019-07-16 13:53:32 |
+----------------------+------+---------------+--------+------+-----------+--------+---------------------+

$ amc application list --filter published=true

```

### Options

```
  -f, --filter stringArray   Filter the output based on conditions (for example, 'published=true')
      --format string        Output format - 'table', 'json', 'yaml' or 'csv' (default "table")
  -h, --help                 help for list
```

### SEE ALSO

* [ams.amc application](ams.amc_application.md)	 - Manage applications

