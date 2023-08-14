# Froom: An embodied agent which tags which room you are in from the objects in the image using Automated Annotations, ChatGPT prompt engineering.

# Requirements
 - Python 3.9
 - Torchvision
 - Torch
 - Ultralytics
 - OpenAI
   
Note: Yolov8.pt and SAM_L.pt will be downloaded (automatically). You may use the base SAM model. The code is optimised for CUDA enabled GPu, change the parameters, as you deem fit.

Froom uses ChatGPT-GPT-3.5-turbo, with a prompt engineered for regularized expressions.

# Usage
 - Clone this repository.
 - Make sure you have pip installed the above requirements. Be specifically careful about the python version.
 - Make sure you replace the openai api id with your own in froom.py.
 - Create a directrory ./images. Upload images to the ./image/ directory.

If you encounter any issues, feel free to open an issue on the repository or send an email to Subhransu.Bhattacharjee@anu.edu.au.

# Citation

@misc{froom,
  author = {Subhransu Bhattacharjee},
  title = {Froom: An embodied agent that tags the room you are in based on the objects in the image},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/1ssb/froom/}}
}




