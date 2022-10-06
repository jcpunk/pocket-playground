# setup

Things that should always run for basically any role go here. This role
does things like import default variables, make common directories, and
other primitives.

## Usage

Generally speaking, every role should include a `meta/main.yml` file with:

```yaml
---
dependencies:
  - role: fermilab.dune_daq.common_setup
```
