Image Generation from Text Prompts

This repository contains a Jupyter notebook that demonstrates how to generate images from text prompts using a Stable Diffusion model via the diffusers library from Hugging Face. It uses the pre-trained model CompVis/stable-diffusion-v1-4 to create AI-generated images based on user-provided text descriptions.

Requirements

Python 3.11+ (tested on 3.11)
GPU recommended for faster inference (e.g., via CUDA), but CPU works (slower)

Run the cells step-by-step:
The notebook installs required libraries (if not already installed).
It loads the Stable Diffusion pipeline.

Provide a text prompt (e.g., "A futuristic cityscape at sunset") in the prompt variable.
Run the generation cell to create and display the image.

Example output:
The generated image will be displayed inline in the notebook.
You can save it manually using image.save("output.png").


Example
Here's a sample prompt and generated image :

Prompt: "A majestic spaceship soaring through a vibrant nebula in deep space, surrounded by twinkling stars and glowing purple and blue cosmic clouds, in a hyper-detailed, sci-fi cinematic style"

Image Generated:

![alt text](image.png)

Notes

Generation can take 10-60 seconds per image depending on hardware.