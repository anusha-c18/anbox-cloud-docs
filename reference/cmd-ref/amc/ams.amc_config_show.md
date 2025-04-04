## ams.amc config show

Show all configuration items

```
ams.amc config show [flags]
```

### Examples

```
$ amc config show
config:
  application.addons: ""
  application.auto_publish: "false"
  application.max_published_versions: "3"
  container.default_platform: ""
  container.security_updates: "true"
  core.trust_password: false
  gpu.type: none
  images.allow_insecure: "false"
  images.update_interval: 5m
  images.url: ""
  registry.filter: ""
  registry.fingerprint: ""
  registry.mode: pull
  registry.update_interval: 1h
  registry.url: ""
  image.auth: ""

```

### Options

```
  -h, --help   help for show
```

### SEE ALSO

* [ams.amc config](ams.amc_config.md)	 - Manage AMS configuration

