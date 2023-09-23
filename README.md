# block-index
This is KubeBlocks' Addon and Plugin extensions index repository. It is meant to be useful only for extensions developers.

## Submitting new extensions

To learn how to create an `Addon` or `Plugin` extension and submit it to `block-index`, read the [Developer Guide][dev-guide]
and make a pull request to this repository.


## The `block-index` file and directory structure

```bash
addons/              # A directory containing `addons.extensions.kubeblocks.io` manifests.
tools/               # A directory containing `tools.extensions.kubeblocks.io` manifests.
applicatinos/        # A directory containing `applicatinos.extensions.kubeblocks.io` manifests.
cli-plugins/         # A directory containing `cliplugins.extensions.kubeblocks.io` manifests.
krew-plugins/        # A directory containing `plugins.krew.googlecontainertools.github.com` manifests.
```