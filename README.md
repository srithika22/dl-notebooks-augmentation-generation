# Deep Learning Practice: Image Augmentation & Text-to-Image Generation

This repository includes two Google Colab notebooks documenting my practical learning on:

1. **Image Augmentation Techniques**
2. **Text-to-Image Generation using Pretrained Models**

These notebooks demonstrate key implementations, visual outputs, and code used to understand and apply core deep learning concepts.

---

## 1. Image Augmentation (`Augmentation.ipynb`)

### Topics Covered:
- Purpose of image augmentation in deep learning
- Common augmentation techniques for image classification tasks
- Implementing transformations using `torchvision.transforms`

### Techniques Implemented:
- Horizontal and Vertical Flip
- Random Rotation and Rescale
- Random Brightness/Contrast Adjustments
- Chaining multiple transforms to build custom augmentation pipelines

### Tools:
- PyTorch
- Torchvision
- PIL for image loading and manipulation

Augmentation helps improve model generalization by introducing controlled variation in training data.

---

## 2. Text-to-Image Generation (`Text_Image_generation.ipynb`)

### Topics Covered:
- Introduction to generative AI and multimodal learning
- How text-to-image generation models work
- Using pre-trained models from Hugging Face

### Tasks Performed:
- Generated images from text prompts using Hugging Face `diffusers`
- Visualized and saved output images from natural language descriptions
- Experimented with prompt changes to influence output

### Tools:
- Hugging Face Transformers & Diffusers
- Torch + Matplotlib

These models combine language understanding and image generation, opening possibilities in art, design, and creative AI.

---

## ✅ Learning Outcomes
- Understood how to apply data augmentation in training pipelines
- Gained practical experience using PyTorch and Hugging Face libraries
- Learned prompt-based control of generative image models
- Developed skills in visualizing and interpreting model outputs

---

## Setup Requirements
- Python 3.x
- `torch`, `torchvision`, `matplotlib`, `transformers`, `diffusers`, `PIL`
- Google Colab (preferred for GPU support)
