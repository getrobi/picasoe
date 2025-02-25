# Picasoe

## Model description

Picasoe is a text-to-image model that features improved performance in image quality, typography, complex prompt understanding, and resource-efficiency.

## Model Description

- Developed by: [Robi Team](https://www.robiai.com/)
- Model type: text-to-image generative model
- Model Description: This model generates images based on text prompts.

## How to use?

The model is available via HuggingFace Inference API

```
from huggingface_hub import InferenceClient

client = InferenceClient(
	provider="hf-inference",
	api_key="hf_xxxxxxxxxxxxxxxxxxxxxxxx"
)

image = client.text_to_image(
	"Astronaut riding a horse",
	model="robiai/picasoe"
)

```
