# Open-source SAEs for SDXL-Turbo

[[`Blog - TODO`]()]
[[`Model`](https://huggingface.co/Goodfire/SDXL-Turbo-SAE-ldown.attns.2.1)]

We're open-sourcing an SAE trained on the image generation model Stable Diffusion XL-Turbo. The SAE is trained on block `down.2.1` of SDXL-Turbo's UNet.

## Usage

For an example of loading the model and exploring the top features for the model's activations, see [`inference_example.ipynb`](inference_example.ipynb). This notebook downloads and loads the SAE model from Hugging Face and explores the top features in our sample activations.

