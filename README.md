## About
This repository is a buildroot build for a Lacie 2 Big Network V2 NAS. It is a work-in-progress.

## Prerequisites
Prerequisites for buildroot [https://buildroot.org/downloads/manual/manual.html#requirement-mandatory]()

## Getting started
Clone the repository
```
git clone https://github.com/bertouttier/2bignetv2-buildroot
cd 2bignetv2-buildroot
git submodule update --init
cd buildroot
```
To build:
```
make BR2_EXTERNAL=../ 2bignetv2_defconfig
make BR2_EXTERNAL=../
```
Use the option ```BR2_JLEVEL=<number>``` to set the ```J=<number>``` for make. Then wait...

