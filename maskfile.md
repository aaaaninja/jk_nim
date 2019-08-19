build
-----

### build debug

```sh
fd . src/ | xargs --replace nim c --outdir:dist/debug {}
```

### build release

```sh
fd . src/ | xargs --replace nim c --outdir:dist/release -d:release {}
```

### build run

```sh
fd . src/ | xargs --replace nim c --outdir:dist/debug -r {}
```
