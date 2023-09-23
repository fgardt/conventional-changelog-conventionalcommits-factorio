[![Release](https://github.com/fgardt/conventional-changelog-conventionalcommits-factorio/actions/workflows/release.yml/badge.svg?branch=main)](https://github.com/fgardt/conventional-changelog-conventionalcommits-factorio/actions/workflows/release.yml)

# conventional-changelog-conventionalcommits-factorio

conventional-changelog preset for factorio mod changelogs

Uses [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) to generate the changelog in factorios format.

Scopes will be used as a prefix for the description in the changelog. \
`compat(SE): allowed to place entity in space` will turn into `[SE] allowed to place entity in space` in the changelog section `Compatibility`.

### Commit types and their corresponding changelog section 

_"Official" sections picked from [this forum thread](https://forums.factorio.com/viewtopic.php?p=409587#p409587)._

| Commit type                 | Changelog section |
| ---------------------       | ----------------- |
| `feat` or `feature`         | `Features`        |
| `fix`                       | `Bugfixes`        |
| `perf` or `performance`     | `Optimizations`   |
| `compat` or `compatibility` | `Compatibility`   |
| `balance`                   | `Balancing`       |
| `graphics`                  | `Graphics`        |
| `sound`                     | `Sounds`          |
| `gui`                       | `Gui`             |
| `info`                      | `Info`            |
| `locale`                    | `Locale`          |
| `translate`                 | `Translation`     |
| `control`                   | `Control`         |
| `other`                     | `Changes`         |
