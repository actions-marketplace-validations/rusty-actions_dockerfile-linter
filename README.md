# dockerfile-linter <br/>![gh-test-status]![gh-release-status]

# GitHub action to lint a dockerfile using squid123/dockerfilelint

A simple action to lint a Dockerfile using the squid123/dockerfilelint image

## Inputs

### `dockerfile`

**Required** The path to the dockerfile

Example usage: 

```yaml
jobs:
  lint_docker_file:
    runs-on: ubuntu-latest
    steps:
      - name: lint docker file
        uses: rusty-actions/dockerfile-linter@v1
        with:
          dockerfile: ./path/to/Dockerfile
```

<!-- Badge links -->

[gh-test-status]: https://github.com/rusty-actions/dockerfile-linter/actions/workflows/test.yml/badge.svg
[gh-release-status]: https://github.com/rusty-actions/dockerfile-linter/actions/workflows/release.yml/badge.svg
