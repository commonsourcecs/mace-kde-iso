# MaCE KDE Editions
[![iso_build](https://github.com/commonsourcecs/download/workflows/iso_build/badge.svg)](https://github.com/commonsourcecs/download/actions)

## description

Development branch for KDE Plasma Edition of MaCE (Manjaro Linux cscs Edition). These are daily builds for testing purposes and not fit for production.

## where can I download an iso?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/commonsourcecs/download/releases)

## sources

- [iso profile](https://github.com/commonsourcecs/iso-profiles/tree/master/community/mace-kde)
- [desktop settings](https://gitlab.manjaro.org/profiles-and-settings/manjaro-gnome-settings)

## building

1. check out the iso profile
2. `buildiso -p mace-kde`

## credentials

```
user: mace
password: mace
```
## Extracting
The isos bigger than certain threshold are provided in multipart zip files because of the filesize restriction of github. To extract the iso, download all the zipped parts, and open the zip file with file-roller, engrampa or 7z. This should automatically extract the iso from all the files.
