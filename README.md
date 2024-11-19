# Digital Image Processing on Licence Plate Segmentation

### Damion Harvey&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Wen Guan Gavin Chen

<!-- TOC -->

## Table of Contents:
* [How to run](#how-to-run--compile)
* [Project File Structure is as follows](#project-file-structure-is-as-follows)
    * [Other information](#other-information)


<!-- TOC -->

## How to run & compile

This project was written in a Jupyer notebook and thus requires a Jupyer Kernel to work. This can be done through the Jupyter client itself or through a Jupyter extension in a text-editor like Visual Studio Code. Once the notebook has been opened properly, multiple cells or blocks of Python code should be visible in the file. These can then be run with the green "play" button at the top of the Jupyter editor. Once run the notebook will generate all the figures used in the report (and save them to the Figures folder) - and will also display these figures in the notebook.


## Project File Structure is as follows
```
DIP-Project
│
│   │   
│   │   licence_plate_segmentor.ipynb
│   │   README.md
│   │   
│   └───carplates
│   │   │   carx.png
│   │
│   └───Figures
│   │   │   Figurex.png
│   │   │   
│   │   └───Steps
│   │       │   stepx.png

```

### Other information

All code was written using Python version 3.9, with the following dependencies:
- numpy (1.21.5)
- scipy (1.9.1)
- scikit-image (0.19.2)
- matplotlib (3.5.2)
