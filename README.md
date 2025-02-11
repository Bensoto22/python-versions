# Python for Actions
This repository contains the code and scripts that we use to build Python packages used in [runner-images](https://github.com/actions/runner-images) and accessible through the [setup-python](https://github.com/actions/setup-python) Action.
File [versions-manifest.json](./versions-manifest.json) contains the list of available and released versions.

> Caution: this is prepared for and only permitted for use by actions `runner-images` and `setup-python` action.

**Status**: Currently under development and in use for beta and preview actions.  This repo is undergoing rapid changes.

Some versions are pre-installed on [runner-images](https://github.com/actions/runner-images) images.
More versions will (soon!) be available to install on-the-fly through the [`setup-python`](https://github.com/actions/setup-python) action.

## Adding new versions
We are trying to build and release new versions of Python as soon as they are released. Please open an issue in [actions/setup-python](https://github.com/actions/setup-python/issues) if any versions are missing.

## Contribution
Contributions are welcome! See [Contributor's Guide](./CONTRIBUTING.md) for more details about contribution process and code structure
