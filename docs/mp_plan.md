## mp plan

Plan changes by running a command against cloned repos

### Synopsis


Plan changes by running a command against cloned repos

```
mp plan [cmd] [args...] [flags]
```

### Examples

```
mp plan -b microplaning -m 'microplane fun' -r app-service -- sh -c /absolute/path/to/script
mp plan -b microplaning -m 'microplane fun' -r app-service -- python /absolute/path/to/script
```

### Options

```
  -b, --branch string    Git branch to commit to
  -h, --help             help for plan
  -m, --message string   Commit message
```

### Options inherited from parent commands

```
  -r, --repo string   single repo to operate on
```

### SEE ALSO
* [mp](mp.md)	 - Microplane makes git changes across many repos

###### Auto generated by spf13/cobra on 13-Apr-2018
