### Jumpstart Examples

This repository contains all the jumpstart examples for R, Python, and Quarto apps.

This is primarily used as a data source for test automation such as Connect Marketplace testing where we use this public repo to enable the tests to publish using Git.

## Adding new bundles

- Add the bundle to the `bundles` directory
- Create a `manifest.json`
- Create a `expected_result.txt` that includes a short, but unique, snippet of text that is visible on the first page of the published bundle. This is used by Connect Marketplace test automation to validate the bundle was successfully deployed, rendered/executed, and is usable by the user
