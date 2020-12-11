# bitcaskfs

A FUSE filesystem for the [Bitcask](https://github.com/prologic/bitcask) database.

> Inspired by [etcfs](https://github.com/polyrabbit/etcdfs).

## Getting Started

Install `bitcaskfs`:

```#!console
go get github.com/prologic/bitcaskfs
```

Mount a Bitcask database:

```#!console
bitcaskfs -; /path/to/db /path/to/mount
```

## License

`bitcaskfs` is licensed under the terms of the [MIT License](/LICENSE)
