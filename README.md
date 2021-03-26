# RockAI

## Prepare data

- Create a folder `data/No_RA` and put all non-rock-art images in this folder.
- Create a folder `data/RA` and put all rock-art images in this folder.
- Run notebook `resize_images.ipynb` to resize images and create a `h5` file for fast reloading in experiments.

## Running

- Run notebook `train_VGG16.ipynb` for training and evaluating with VGG16 model.
- Run notebook `train_VGG16_hParams.ipynb` for searching network parameters.