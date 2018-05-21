# test-split-master

This repository is a demo for [jderusse/docker-gitsplit](https://github.com/jderusse/docker-gitsplit).

This is the main repository split into several parts:

- `src/partA` is pushed into [jderusse/test-split-a](https://github.com/jderusse/test-split-a)
- `src/partB` is pushed into [jderusse/test-split-b](https://github.com/jderusse/test-split-b) and [jderusse/test-split-z](https://github.com/jderusse/test-split-z)
- `src/subTree/partC` is merged with `src/subTree/partZ` and pushed into [jderusse/test-split-c](https://github.com/jderusse/test-split-c)
