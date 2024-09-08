# Version Control Course

[![Quarto Publish](https://github.com/lnnrtwttkhn/version-control-course-uhh-2024/actions/workflows/publish.yml/badge.svg)](https://github.com/lnnrtwttkhn/version-control-course-uhh-2024/actions/workflows/publish.yml)

# Usage

## Update project for new course

Adapt the following commands as needed:

```bash
git checkout -b update
git mv version-control-course-mpib-2024.Rproj version-control-course-uhh-2024.Rproj
git commit -m "Rename .Rproj file"
```

```bash
make objectives
make cheatsheet
make images
```

### Setup `renv`

```r
# Bootstrapping renv 1.0.5 ---------------------------------------------------
- Downloading renv ... OK
- Installing renv  ... OK

- Project '~/edu/version-control-course-uhh-2024' loaded. [renv 1.0.5]
- None of the packages recorded in the lockfile are currently installed.
```

Run `renv::restore()` to restore the project environment:

```r
renv::restore()
```