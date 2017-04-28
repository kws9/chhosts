# chhosts

`chhosts` is easy switching to hosts that you registered.

## Install (OSX)

```
brew tap kws9/chhosts
brew install chhosts
```

## Options

```
[-h|--help] : Display useage and registered hosts
[-n|--now ] : Confirm current hosts
[-a|--add ] : Add hosts
[-r|--rm  ] : Remove hosts
[-f|--fix ] : Fix hosts
```

## Useage

### Change hosts
`chhosts [hosts name]`

If hosts name is not specified , change hosts name => default.

### Add hosts

`chhosts [-a|--add] [hosts name]`

Create new hosts file.
After create, you can use change to hosts file that is added.

### Remove hosts
`chhosts [-r|--rm] [hosts name]`

Remove added hosts file.

### Fix hosts
`chhosts [-f|--fix] [hosts name]`

fix added hosts file.

### Confirm current hosts
`chhosts [-n|--now]`

Display current hosts configuration.
