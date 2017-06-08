

```
$ tree .git/objects/
.git/objects/
├── info
└── pack
    ├── pack-c86e9a7ae9c898123d67a98ca45d3a52b4033b4c.idx
    └── pack-c86e9a7ae9c898123d67a98ca45d3a52b4033b4c.pack

2 directories, 2 files
```

```
$ git show --format=raw HEAD

$ git show --format=raw <tree>

$ git ls-tree <tree>

$ git show --format=raw <blob>

$ git tag -l | tail -1

$ git show --format=raw <tag>
```
