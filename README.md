The Object Database
===================

```
tree .git/objects/
.git/objects/
├── 09
│   └── 7516a6591abed71281f2011fb966b4924d267d
├── 14
│   └── 15d355c60d68f0ea982b0446eea4cdbdc8ba42
├── 19
│   └── f8b15efa7ceef3fe0346db7b273e43910997ce
├── 2e
│   └── 2baf784fc645fb074b763807540f904028b135
├── 4a
│   └── 6161b982fa3ab86433673289c80c9b706e7b00
├── 7a
│   └── 1143d4c735876f4f20469bdcf50ac815dfdaea
├── 7e
│   └── d7ed6fa05d91ba4a8a81e33a840638b359b314
├── 7f
│   └── 3ef05c9c6e5747a2edda1fb45697bef15adea3
├── 93
│   └── b2a7124cba45f12d9649a7e11e09a2d5b5335b
├── b5
│   └── 4d0f43ac8c1e7a18de0a0be5d0dedd6cde6787
├── dd
│   └── 605fe173f2a6d3c17cab031d54e1ba90bd6b36
├── de
│   └── a2d376ea2396bc05c095d23b898cbd9c604dcf
├── e5
│   └── ea18f387a84e245fb5d20ac1362571225f05cb
├── e6
│   └── 9de29bb2d1d6434b8b29ae775ad8c2e48c5391
├── fb
│   └── 62d976f52dd7f89a1514840a0e99b5016bfa04
├── info
└── pack

17 directories, 15 files
```

```
$ git show --format=raw dd605fe173f

$ git show --format=raw 19f8b15efa

$ git ls-tree 19f8b15efa

$ git show --format=raw e5ea18f

$ git tag -l

$ git show --format=raw v0.1
```
