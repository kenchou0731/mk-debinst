# mk-debinst

`mk-debinst` is a tool for creating self-extracted Debian packages install script on Debian-based systems.

```
    |----------|
  |----------| |   mk-debinst    |------------|
|----------| |-|  ============>  | install.sh |
| deb_file |-|                   |------------|
|----------|

```

## Usage

```
# ./mk-debinst <deb_file1> [<deb_file2> ...]
```

The output install script will be `install.sh`.
