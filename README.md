# [LibreRTOS Projects](https://github.com/djboni/librertos_projects)

Copyright (c) 2022 Djones A. Boni - MIT License

LibreRTOS is a portable Single-Stack Real-Time Operating System.

This repository contains a few IDE projects using
[LibreRTOS](https://github.com/djboni/librertos).

Note: This repository is used as a submodule in LibreRTOS repository, using
linked resources from the parent repository. Just cloning this repository is not
supposed to "work". To be able to compile and try the IDE projects just follow
the instructions below.

## Using This Repository

1. Clone the main LibreRTOS repository and initialize the submodules:

```sh
git clone https://github.com/djboni/librertos.git --recurse-submodules
```

2. If you cloned without `--recurse-submodules`, you can initialize the
   submodules manually:

```sh
git submodule update --init
```

3. Now you can look into `librertos/projects` and use the available IDE
   projects.
