# browser

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/browser)
[![General Workflow](https://github.com/rolehippie/browser/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/browser/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/browser/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/browser/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/browser/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/browser/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/browser)](https://github.com/rolehippie/browser/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.browser-blue)](https://galaxy.ansible.com/rolehippie/browser)

Ansible role to install multiple browsers.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [browser_chrome](#browser_chrome)
  - [browser_chrome_arch](#browser_chrome_arch)
  - [browser_chrome_deb](#browser_chrome_deb)
  - [browser_chrome_package](#browser_chrome_package)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### browser_chrome

Enable installation of Google Chrome

#### Default value

```YAML
browser_chrome: true
```

### browser_chrome_arch

Architecture for Google Chrome

#### Default value

```YAML
browser_chrome_arch: amd64
```

### browser_chrome_deb

Download URL for the Google Chrome package to install

### browser_chrome_package

#### Default value

```YAML
browser_chrome_package: https://dl.google.com/linux/direct/google-chrome-stable_current_{{
  browser_chrome_arch }}.deb
```

## Discovered Tags

**_browser_**

**_chrome_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
