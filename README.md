# ato24-bootc
Demo files for ATO talk 2025 Making OS updates fast, easy, and safe

fedora-base: The Containerfile to build the base image with neofetch installed

derived-image: The Containerfile to build a Flask enabled image that inherits from the base image

vm-template: The bootc-image-builder command and config.toml used to create a QCOW2 disk image for use iwith KVM

.github/workflows/build_fedora_bootc.yml The Github action workflow to build the base image

.github/workflows/build_derived_bootc.yml The Github action workflow to build the derived image


### Build status
[![Build F40 bootc image with GHA](https://github.com/nzwulfin/ato24-bootc/actions/workflows/build_fedora_bootc.yml/badge.svg)](https://github.com/nzwulfin/ato24-bootc/actions/workflows/build_fedora_bootc.yml)

[![Build F40 bootc image with GHA](https://github.com/nzwulfin/ato24-bootc/actions/workflows/build_fedora_bootc.yml/badge.svg)](https://github.com/nzwulfin/ato24-bootc/actions/workflows/build_fedora_bootc.yml)
