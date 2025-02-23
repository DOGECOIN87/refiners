<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/finegrain-ai/refiners/main/assets/logo_dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/finegrain-ai/refiners/main/assets/logo_light.png">
  <img alt="Finegrain Refiners Library" width="352" height="128" style="max-width: 100%;">
</picture>

**The simplest way to train and run adapters on top of foundation models**

[**Manifesto**](https://refine.rs/home/why/) |
[**Docs**](https://refine.rs) |
[**Guides**](https://refine.rs/guides/adapting_sdxl/) |
[**Discussions**](https://github.com/finegrain-ai/refiners/discussions) |
[**Discord**](https://discord.gg/mCmjNUVV7d)

</div>

## Installation

The nodes are published at https://registry.comfy.org/publishers/finegrain/nodes/comfyui-refiners.

To easily install the nodes, run the following command:
```bash
comfy node registry-install comfyui-refiners
```

You may also download the nodes by cliking the "Download Latest" button and unzipping the content of the archive into you custom_nodes directory.

See https://docs.comfy.org/registry/overview for more information.

## Example Workflows

### [Box Segmenter](assets/box_segmenter.json)

This simple workflow leverages GroundingDINO and our [BoxSegmenter](https://huggingface.co/finegrain/finegrain-box-segmenter) to extract objects from an image.
[![Box Segmenter Workflow](assets/box_segmenter.png)](assets/box_segmenter.json)
