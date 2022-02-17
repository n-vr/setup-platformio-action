# Setup PlatformIO
This actions sets up PlatformIO for use in actions.

# Usage
See [action.yml](action.yml)

## Basic
```yaml
- name: Setup PlatformIO
  uses: n-vr/setup-platformio-action@v1
```

## Specify PlatformIO version
```yaml
- name: Setup PlatformIO
  uses: n-vr/setup-platformio-action@v1
  with:
    platformio-version: "5.2"
```

## Inputs
> Use the `with` keyword to specify these inputs

### `platformio-version` (optional)
Specify the PlatformIO to set up. Use semantic versioning (e.g. "5.2.5", "5.2" or "5").

# License
Distributed under the MIT license. See [LICENSE.md](LICENSE.md) for more information.

# Acknowledgements
- [PlatformIO](https://docs.platformio.org/en/stable/integration/ci/github-actions.html)