[![DOI](https://zenodo.org/badge/5466/bgruening/docker-galaxy-stable.svg)](https://zenodo.org/badge/latestdoi/5466/bgruening/docker-galaxy-stable)
[![Build Status](https://travis-ci.org/bgruening/docker-galaxy-sequence-tools.svg?branch=master)](https://travis-ci.org/bgruening/docker-galaxy-sequence-tools)
[![Docker Repository on Quay](https://quay.io/repository/bgruening/galaxy-sequence-tools/status "Docker Repository on Quay")](https://quay.io/repository/bgruening/galaxy-sequence-tools)

Galaxy Workbench for basic sequence manipulation
================================================

:whale: Galaxy Docker repository for basic sequence manipulation

# Installed tools

 * [Bowtie2](http://bowtie-bio.sourceforge.net/bowtie2)
 * [FASTQC](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/)
 * [deepTools](http://fidelram.github.io/deepTools/)
 * [BWA](http://bio-bwa.sourceforge.net/)
 * [Bowtie2](http://bowtie-bio.sourceforge.net/bowtie2)

# Requirements

 - [Docker](https://docs.docker.com/installation/) for Linux / Windows / OSX
 - [Kitematic](https://kitematic.com/) for Windows / OS-X (Optional)

# Usage

To launch:

```
docker run -i -t -p 8080:80 bgruening/galaxy-sequence-tools
```

For more details about this command line or specific usage, please consult the
[`README`](https://github.com/bgruening/docker-galaxy-stable/blob/master/README.md) of the main Galaxy Docker image, on which the current image is based.

# Contributers

 - Bjoern Gruening


# Support & Bug Reports

You can file an [github issue](https://github.com/bgruening/docker-galaxy-ngs-preprocessing/issues) or ask us on the [Galaxy development list](http://lists.bx.psu.edu/listinfo/galaxy-dev).
