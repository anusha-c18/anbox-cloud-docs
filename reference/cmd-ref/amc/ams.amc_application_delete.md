## ams.amc application delete

Delete an application

### Synopsis

Delete an application.

Deleting an application removes all of its versions. If you want to remove
only a specific version, you can use the '--version' flag.

Applications downloaded from the registry cannot be deleted unless
you specify the '--force'|'-f' flag.


```
ams.amc application delete ( <id> | <name> ) [flags]
```

### Examples

```
$ amc application delete foo
The following application will be REMOVED:
  - foo
Do you want to continue? [Y/n]:

```

### Options

```
  -a, --all              Delete all existing applications
  -f, --force            Force deletion of the application even if it is immutable
  -h, --help             help for delete
      --no-wait          Don't wait for the delete operation to finish
  -t, --timeout string   Maximum time to wait for the operation to complete (default "5m")
  -v, --version int      Version of the application to delete. If not specified, all versions are deleted.
  -y, --yes              Assume 'yes' as answer to all prompts and run non-interactively
```

### SEE ALSO

* [ams.amc application](ams.amc_application.md)	 - Manage applications

