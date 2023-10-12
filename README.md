# MaCE KDE Editions
[![iso_build](https://github.com/commonsourcecs/mace-kde-iso/workflows/iso_build/badge.svg)](https://github.com/commonsourcecs/mace-kde-iso/actions)

## description

KDE Plasma ISO for MaCE (Manjaro Linux cscs Edition). 

These are automated builds currently for testing. 

## where can I download an iso?

Images are built and uploaded in a relatively regular interval to [github releases](https://github.com/commonsourcecs/mace-kde-iso/releases).

## sources

- [iso profile](https://github.com/commonsourcecs/iso-profiles/tree/master/community/mace-kde)
- [desktop settings](https://gitlab.manjaro.org/profiles-and-settings/)

## building

1. check out the iso profile
2. `buildiso -p mace-kde`

## credentials

```
user: mace
password: mace
```
## Extracting

ISOs are provided in multipart zip files because of the filesize restriction of github.</br>
To extract the iso download all the zipped parts and open the zip file with file-roller, engrampa or 7z.</br>
This should automatically extract the iso from all the files.</br>
Of course you can also use the terminal. 
```
cat manjaro-mace-kde.iso.z* > mace-kde.iso.zip
unzip mace-kde.iso.zip
```
