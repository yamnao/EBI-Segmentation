# EBI-Segmentation

Jupyter Notebook to recover cytoplasm from actin images using nucleus-seeded watersheds. The Images folder is composed of 3 types of images: actin, dna and pH3. The DNA images are used to find the nuclei and generate markers that are then applied to the DNA images to find the cytoplasm. The final objective is to compare the morphology of different colon cancer cells.

## Installation
```bash
pip install numpy
pip install plotly
pip install matplotlib
```

## Files

EBI-YamnaOuchtar contains the pipeline code.
Report contains the report discussion.

## Note:
To run the Jupyter notebook file, you must save the Image folder in the same folder as the jupyter-notebook file or you can change the path, also called directory, of the vector_of_images function to your own path. However, all images must be saved in the same folder.  
  
