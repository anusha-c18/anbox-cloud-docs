## ams.amc application update

Update an existing application

### Synopsis

Update an existing application.

Updating an application creates a new version that must run through
the bootstrap process.

If no package is provided, AMS checks what updates are possible by looking
at newer images and addons and applies any pending changes if necessary.

Depending on which updates you want to do to your existing application,
consider using the 'application set' command instead. That command allows
to update specific fields of the application without updating the application.


```
ams.amc application update <id> [<package_path>] [flags]
```

### Examples

```
$ tree foo-app
foo-app/
├── app.apk
└── manifest.yaml

$ amc application update foo foo-app/

```

### Options

```
  -h, --help             help for update
  -t, --timeout string   Maximum time to wait for the operation to complete (default "5m")
```

### SEE ALSO

* [ams.amc application](ams.amc_application.md)	 - Manage applications

