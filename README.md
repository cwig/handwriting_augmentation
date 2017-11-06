# Usage

## Run the python function directy
```
python grid_distortion.py input_image.png output_image.png
```
 
#### Input
![alt text](https://github.com/cwig/handwriting_augmentation/raw/master/input_image.png)
#### Output
![alt text](https://github.com/cwig/handwriting_augmentation/raw/master/output_image.png)
 
## warp_image function  

```python
from grid_distortion import warp_image
img = warp_image(img)
```

#### kwargs options:
* w_mesh_interval: grid interval for width dimension
* h_mesh_interval: grid interval for height dimension
* w_mesh_std: standard deviation for width dimension perturbations
* h_mesh_std: standard deviation for height dimension perturbations
* fit_interval_to_image: adjust the interval so the grid fits the images height/width exactly
* draw_grid_lines: draw warp grid lines for visualization
* interpolation: linear|cubic
