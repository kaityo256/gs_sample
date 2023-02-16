# Ghostscript sample

## Docker image

If you do not have an environment where you can use gs, you can use docker as follows.

```sh
git clone https://github.com/kaityo256/gs_sample.git
cd gs_sample
cd docker
make
make run
```

You need to X Window server with appropriate permissions.

## Run Ghostscript

```sh
# gs
```

You can specify the size of the window as follows.

```sh
# gs -dDEVICEWIDTHPOINTS=200 -dDEVICEHEIGHTPOINTS=200
```

## LICENSE

MIT
