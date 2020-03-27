# Singularity

[![Build Status](https://travis-ci.org/sylabs/singularity.svg?branch=master)](https://travis-ci.org/sylabs/singularity)
[![CircleCI](https://circleci.com/gh/sylabs/singularity/tree/master.svg?style=svg)](https://circleci.com/gh/sylabs/singularity/tree/master)

- [Guidelines for Contributing](CONTRIBUTING.md)
- [Pull Request Template](.github/PULL_REQUEST_TEMPLATE.md)
- [Project License](LICENSE.md)
- [Documentation](https://www.sylabs.io/docs/)
- [Citation](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0177459)

Singularity is an open source container platform designed to be simple, fast,
and secure. Singularity is optimized for compute focused enterprise and HPC
workloads, allowing untrusted users to run untrusted containers in a trusted
way.

Check out [talks about Singularity](https://www.sylabs.io/videos) and some [use
cases of Singularity](https://sylabs.io/case-studies) on our website.

## Getting Started with Singularity

To install Singularity from source, see the [installation
instructions](INSTALL.md). For other installation options, see [our
guide](https://www.sylabs.io/guides/3.5/admin-guide/installation.html).

System administrators can learn how to configure Singularity, and get an
overview of its architecture and security features in the [administrator
guide](https://www.sylabs.io/guides/3.5/admin-guide/).

For users, see the [user
guide](https://www.sylabs.io/guides/3.5/user-guide/) for details on how to use
and build Singularity containers.

## Contributing to Singularity

Community contributions are always greatly appreciated. To start developing
Singularity, check out the [guidelines for contributing](CONTRIBUTING.md).

We also welcome contributions to our [user
guide](https://github.com/sylabs/singularity-userdocs) and [admin
guide](https://github.com/sylabs/singularity-admindocs).

## Support

**This version of Singularity is no longer officially supported.**

This singularity version is a continuation of Singularity version 2. Singularity version 2 was written in C, but this version became difficult to maintain, and Version 3, although very similar at first sight, was a complete rewrite in Go.

Now a version in C is straightforward to compile, whereas for Go, you need a *bit* more. Therefore, many sites still use version 2. With a recent Linux kernel update, version 2 became unusable - which is why I decided to apply a small patch; and a fork was born...

For general singularity version 2 documentation, see the Singularity site.

For reporting bugs and errors, keep in mind that version 2 is no longer officially supported. I will fix bugs and add features as time permits.

## Cite as:

```
Kurtzer GM, Sochat V, Bauer MW (2017) Singularity: Scientific containers for mobility of compute. PLoS ONE 12(5): e0177459. https://doi.org/10.1371/journal.pone.0177459
```

We also have a Zenodo citation:

```
Kurtzer, Gregory M.. (2016). Singularity 2.1.2 - Linux application and environment
containers for science. 10.5281/zenodo.60736

https://doi.org/10.5281/zenodo.60736
```

## License

_Unless otherwise noted, this project is licensed under a 3-clause BSD license
found in the [license file](LICENSE.md)._
