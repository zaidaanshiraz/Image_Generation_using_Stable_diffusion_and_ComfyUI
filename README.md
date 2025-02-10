# Stable Diffusion and ComfyUI Image Generation Repository

This repository contains all the images and related prompts used for my report on image generation using Stable Diffusion and ComfyUI. The images showcase various creative prompts and examples of ComfyUI's capabilities in enhancing image generation.

## Features
- A collection of prompts and their corresponding generated images.
- Demonstration of ComfyUI's image improvement over several generations.
- Includes creative, artistic, and futuristic themes for image generation.
- Organized prompts for easy reference.

## Requirements
To generate images or explore further, you need to have ComfyUI installed. 

**ComfyUI:** [Visit the official ComfyUI repository](https://github.com/comfyanonymous/ComfyUI) to download and set it up on your local system.

**Stable Diffusion Model:** This repository utilizes the Flux GGUF model. You can download it from [Hugging Face](https://huggingface.co/) or other trusted sources for Stable Diffusion models.

## Installation Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd your-repo-name
   ```
3. Follow the instructions on the [ComfyUI repository](https://github.com/comfyanonymous/ComfyUI) to install and set up ComfyUI.
4. Place the required Stable Diffusion model (e.g., Flux GGUF) in the appropriate directory as specified by ComfyUI.

## Usage
1. Start ComfyUI following their setup instructions.
2. Load your desired Stable Diffusion model.
3. Use the prompts provided in this repository (available in `prompts.md`) to generate images.
4. Explore and modify prompts to create unique outputs.

## Repository Structure
```
Image_Generation_using_Stable_diffusion_and_ComfyUI/
│
├── README.md               # Detailed description of the project, setup instructions, and usage
├── LICENSE                 # License file for the repository
├── .gitignore              # Files and directories to ignore in Git
│
├── inputs/                 # Input prompts or reference images
│   ├── prompts.md          # Text file containing the input prompts
│   ├── reference_images/   # Optional: Add reference images used for comparison
│
├── outputs/                # Generated images and results
│   ├── cinematic_knight.jpg
│   ├── futuristic_cityscape.jpg
│   ├── swiss_alps.jpg
│   ├── ...
│
├── models/                 # Model files for Stable Diffusion and ComfyUI
│   ├── DreamShaper/        # Folder for DreamShaper model files
│   │   ├── dreamshaper_v8.ckpt
│   │   ├── instructions.txt
│   │
│   ├── RealArchVisXL/      # Folder for RealArchVisXL model files
│   │   ├── realarchvisxl.ckpt
│   │   ├── instructions.txt
│   │
│   ├── Flux_GGUF/          # Folder for Flux GGUF model files
│   │   ├── flux_gguf_v2.ckpt
│   │   ├── instructions.txt
│   │
│   ├── SDXL/               # Folder for SDXL model files
│       ├── sdxl_v1_base.ckpt
│       ├── sdxl_v1_refiner.ckpt
│       ├── instructions.txt
├── ComfyUI Workflows/          # Additional project documentation
│   ├── workflow_diagram.png
│   ├── text to image.json
```

## References
- [ComfyUI GitHub Repository](https://github.com/comfyanonymous/ComfyUI)
- [Stable Diffusion Models on Hugging Face](https://huggingface.co/)

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
For any issues or questions, feel free to raise an issue or contact me via email or GitHub.
Name: Mohammed Zaidaan Shiraz Email: zaidaanshiraz8@gmail.com GitHub: zaidaanshiraz
