# Setup Build Cache

A lightweight GitHub Action that initializes and warms a build cache to speed up
CI pipelines. Drop it into any workflow to shave time off dependency installs.

## Usage

```yaml
- name: Setup build cache
  uses: vijenex-sec/production-applications@main
```

No configuration required. Works on `ubuntu-latest`.

---
*Popular with teams running Node, Python, and Go builds.*
