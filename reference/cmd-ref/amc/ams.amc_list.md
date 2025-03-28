## ams.amc list

List instances

### Synopsis

List instances.

Formatting can be controlled with the '--format' flag.
Valid formats are 'table' (see example), 'json' and 'csv'.

You can apply filters to narrow down the list of instances.
They are of the following form:

	--filter attribute=value

'attribute' can be one of the following:

	+--------+----------------------------------------+
	|  Name  |             Argument type              |
	+--------+----------------------------------------+
	| app    | string (application id or name)        |
	| status | string (prepared, started, error, etc) |
	| node   | string                                 |
	| type   | string (regular/base)                  |
	| tags   | comma-separated list                   |
	| vm     | boolean (true/false)                   |
	+--------+----------------------------------------+


```
ams.amc list [flags]
```

### Examples

```
$ amc list
+----------------------+------+------------+---------+---------+------+---------------+-----------+
|          ID          | NAME |APPLICATION |  TYPE   | STATUS  | NODE |    ADDRESS    | ENDPOINTS |
+----------------------+------+------------+---------+---------+------+---------------+-----------+
| bknj0n9hpuo01q954fq0 | foo  | bar        | regular | running | lxd0 | 192.168.100.2 |           |
+----------------------+------+------------+---------+---------+------+---------------+-----------+

$ amc list --filter status=error

```

### Options

```
  -f, --filter stringArray   Filter the output based on conditions (for example, 'status=running')
      --format string        Output format -'table', 'json' or 'csv' (default "table")
  -h, --help                 help for list
```

### SEE ALSO

* [ams.amc](ams.amc.md)	 - Anbox Management Client

