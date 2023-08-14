# Roomie: An embodied agent which tags which room you are in from the objects in the image using Automated Annotations & ChatGPT prompt engineering.

# Requirements
 - Python 3.9
 - Torchvision
 - Torch
 - Ultralytics (Make sure you also download the dependecies: https://docs.ultralytics.com/reference/data/annotator/) as ``pip install ultralytics``
 - OpenAI as ``pip install openai``
   
# Note

1. Yolov8.pt and SAM_L.pt will be downloaded (automatically). You may use the base SAM model. The code is optimised for CUDA enabled GPU, change the parameters, as you deem fit. Make sure you have sufficient memory on disk.

2. Images used for demo are scraped off the internet, the copyright lies with the creators. 

# Usage
 - Clone this repository: ``git clone https://github.com/1ssb/roomie.git``
 - Make sure you have pip installed the above requirements. Be specifically careful about the python version.
 - Make sure you replace the openai api id with your own in froom.py. Follow this link: https://elephas.app/blog/how-to-get-chatgpt-api-key-clh93ii2e1642073tpacu6w934j
 - Upload images to the ./images/ directory.

If you encounter any issues, feel free to open an issue on the repository or send an email to Subhransu.Bhattacharjee@anu.edu.au.

# Citation
``
@misc{froom,
  author = {Subhransu Bhattacharjee},
  title = {Froom: An embodied agent that tags the room you are in based on the objects in the image},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/1ssb/froom/}}
}
``



