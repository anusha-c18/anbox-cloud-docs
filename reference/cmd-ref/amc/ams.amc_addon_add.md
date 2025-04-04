## ams.amc addon add

Add an addon

### Synopsis

Add an addon.

Addons can be created from plain directories or tarballs or zip archives.
A valid addon must contain a manifest and hooks.

Addons are not used automatically, but they must be enabled for an application
by adding them to the application manifest.
Alternatively, you can enable them globally by setting the configuration item
'application.addons'.

```
ams.amc addon add <name> (<directory> | <.tar.bz2 tarball> | <.zip zip archive>) [flags]
```

### Examples

```
$ tree my-addon
my-addon/
├── hooks
│   └── install
└── manifest.yaml

$ amc addon add foo my-addon/

```

### Options

```
  -h, --help             help for add
  -t, --timeout string   Maximum time to wait for the operation to complete (default "5m")
```

### SEE ALSO

* [ams.amc addon](ams.amc_addon.md)	 - Manage addons

