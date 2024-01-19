# Stable Bud - Image Generation with Stable Diffusion

Stable Bud is a Python application that uses the Stable Diffusion model to generate images from textual prompts. This project is built using Tkinter for the graphical user interface and the Hugging Face Transformers library for natural language processing.

## Installation
- Clone the repository to your local machine:
    '''bash
        git clone https://github.com/sravanthishoroff/generate_images_sd.git
- Install the required Python packages:
    ```bash 
        pip install -r requirements.txt
## Usage
- Run the application:
    ```bash 
        python app.py
- Enter a textual prompt in the input field and click the "Generate" button to create an image based on your prompt.
- The generated image will be displayed in the GUI, and it will also be saved as generatedimage.png in the project directory.

## Models
- The application uses the CompVis/stable-diffusion-v1-4 model from the Hugging Face Model Hub for image generation.

## Configuration
- You can configure the model and other settings in the stable_bud.py file, including the model ID, device (CPU or CUDA), and guidance scale.
    modelid = "CompVis/stable-diffusion-v1-4"
    device = "cuda"  # Use "cpu" for CPU
    guidance_scale = 8.5

## Acknowledgments
- Hugging Face for providing pre-trained models and transformers.
- The Stable Diffusion model authors for their research.

## Author
- Sravanthi Shoroff

## Contact 
For any questions or issues, please contact sravanthi.shoroff955@gmail.com
