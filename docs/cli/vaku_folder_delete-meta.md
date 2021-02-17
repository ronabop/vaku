## vaku folder delete-meta

Recursively delete all secrets metadata and versions in a folder. V2 engines only.

### Synopsis

Recursively delete all secrets metadata and versions in a folder. V2 engines only.

```
vaku folder delete-meta <folder> [flags]
```

### Examples

```
vaku folder delete-meta secret/foo
```

### Options

```
  -h, --help   help for delete-meta
```

### Options inherited from parent commands

```
  -p, --absolute-path                  show absolute path in output
  -a, --address string                 address of the Vault server
      --destination-address string     address of the destination Vault server
      --destination-namespace string   name of the vault namespace to use in the destination client
      --destination-token string       token for the destination vault server (alias for --token)
      --format string                  output format: text|json (default "text")
  -i, --indent-char string             string used for indents (default "    ")
  -n, --namespace string               name of the vault namespace to use in the source client
  -s, --sort                           sort output text (default true)
      --source-address string          address of the source Vault server (alias for --address)
      --source-namespace string        name of the vault namespace to use in the source client (alias for --namespace)
      --source-token string            token for the source vault server (alias for --token)
  -t, --token string                   token for the vault server
  -w, --workers int                    number of concurrent workers (default 10)
```

### SEE ALSO

* [vaku folder](vaku_folder.md)	 - Commands that act on Vault folders
