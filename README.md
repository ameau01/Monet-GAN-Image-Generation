# CSCA-5642 GAN Picture Generation Project

This project implements a CycleGAN to transform photographs into Monet-style paintings for the Kaggle "I'm Something of a Painter Myself" competition. Using TensorFlow, the model trains on unpaired datasets of photos and Monet paintings (256x256 RGB images) to learn bidirectional mappings. 

- Kaggle Notebook: https://www.kaggle.com/code/alexandermeau/monet-gan-generator
- Author: Alexander Meau
- Email: ameau01@gmail.com

## Directory Structure
Below is the directory structure of the project:

  ├── data/<br>
  │    ├── monet_jpg.zip<br>
  │    └── sample_photo_jpg.zip<br>
  ├── output/<br>
  │    └── images.zip<br>
  └── CycleGAN-Monet-Art-Generation.ipynb<br>


## Files
- data/monet_jpg.zip: Input monet painting in jpg format.
- data/sample_photo_jpg.zip: Input photo to be used for painting generation.
- output/images.zip: Zip file containing 7000 images generated
- CycleGAN-Monet-Art-Generation.ipynb: The main Jupyter Notebook containing the CycleGAN code. 
