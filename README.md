# laminas-skeleton-installer

[![Build Status](https://travis-ci.com/laminas/laminas-skeleton-installer.svg?branch=master)](https://travis-ci.com/laminas/laminas-skeleton-installer)
[![Coverage Status](https://coveralls.io/repos/github/laminas/laminas-skeleton-installer/badge.svg?branch=master)](https://coveralls.io/github/laminas/laminas-skeleton-installer?branch=master)

laminas-skeleton-installer is a composer plugin for use in the initial install 
of the [laminas-mvc-skeleton](https://github.com/laminas/laminas-mvc-skeleton).
It prompts for common requirements, adding packages to the composer 
requirements for each selection, and then uninstalls itself on completion.

The installer requires [laminas-component-installer](https://docs.laminas.dev/laminas-component-installer/),
and we recommend requiring that component in your project skeleton as well.

**Please note:** this repository is a helper to the 
[laminas-mvc-skeleton](https://github.com/laminas/laminas-mvc-skeleton) 
repository and is not inteneded to be used on its own.

- File issues at https://github.com/laminas/laminas-skeleton-installer/issues
- Documentation is at https://docs.laminas.dev/laminas-skeleton-installer/
