# Tikibase Github Action

This Github Action runs [Tikibase](https://github.com/kevgo/tikibase) on your
repo content fails the build if there are issues.

## Usage

Add this to your Github Action file:

```yml
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: kevgo/tikibase-github-action@main
```
