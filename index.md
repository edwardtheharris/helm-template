---
abstract: >-
   Helm Template documentation master file, created by
   sphinx-quickstart on Sun Apr 28 15:35:08 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
authors:
   - name: Xander Harris
     email: xandertheharris@gmail.com
date: 2024-08-04
title: Template Helm Chart
---

## Repository Contents

```{toctree}
:maxdepth: 2

workflows/index
```

```{toctree}
:caption: meta

.github/index
license
readme
security
```

## Indices and tables

* {ref}`genindex`
* {ref}`modindex`
* {ref}`search`

## Usage

Typical Helm chart rules.

### Chart

```{autoyaml} Chart.yaml
```

#### Values

```{autoyaml} values.yaml
```

```{sectionauthor} Xander Harris <xandertheharris@gmail.com>
```
