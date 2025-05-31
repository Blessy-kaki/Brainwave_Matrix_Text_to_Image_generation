# Task - 2
Develop a text-to-image generation application that takes textual descriptions as input and produces corresponding visual representations or images.
The application should leverage techniques from the field of generative models.

## Features

- Accepts any English text prompt.
- Generates corresponding images using a pretrained model.
- Simple, interactive user interface using Gradio.
- Examples:  "A magical forest with glowing trees","bunch of roses", "two dogs with different colors one is white 2nd is brown".

##  Model Information
This application uses the [**Stable Diffusion v1.4**](https://huggingface.co/CompVis/stable-diffusion-v1-4) model from Hugging Face.

- **Model Type**: Latent Diffusion Model (LDM)
- **Framework**: Hugging Face `diffusers`
- **Task**: Text-to-Image generation
- **Pretrained on**: Large-scale image-text pairs (like LAION-2B)




