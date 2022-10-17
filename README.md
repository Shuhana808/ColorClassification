# ColorClassification
The color classification task is to predict the distinct color category based on the three 
input values for RGB (R: Red, G: Green, B: Blue) color code. Each of these three numbers is 
basically an integer ranging from 0 to 255 and these combined Red, Green & Blue values are 
used to generate a distinct solid color. The dataset contains 11 basic color categories for 
classification. These basic colors are Red, Green, Blue, Yellow, Orange, Pink, Purple, Brown, 
Grey, Black and White.

### Run the Code


Create an environment with the packages specified:

```conda create --name classification  -c conda-forge python=3.10 pandas=1.5.0 numpy=1.23.3 scikit-learn=1.1.2  ipykernel notebook nb_conda_kernels```

Activate the environment:

`conda activate classification`

Run the `main.ipynb` notebook:

```jupyter notebook main.ipynb```
