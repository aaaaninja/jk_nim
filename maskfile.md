build
-----

### build debug

```sh
nim c --outdir:dist/debug jk.nim
```

### build release

```sh
nim c --outdir:dist/release -d:release jk.nim
```

### build run

```sh
nim c -r jk.nim
```
