## ./pachctl get-file

Return the contents of a file.

### Synopsis


Return the contents of a file.

```
./pachctl get-file repo-name commit-id path/to/file
```

### Options

```
  -o, --output string      The path where data will be downloaded.
  -p, --parallelism uint   The maximum number of files that can be downloaded in parallel (default 10)
  -r, --recursive          Recursively download a directory.
```

### Options inherited from parent commands

```
      --no-metrics   Don't report user metrics for this command
  -v, --verbose      Output verbose logs
```

### SEE ALSO
* [./pachctl](./pachctl.md)	 - 

###### Auto generated by spf13/cobra on 14-Apr-2017
