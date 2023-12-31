# JavaPC

Parallel Coordinates (PC) visualization tool for CSV stored multidimensional/multivariate data.  
Written in Java using Java Swing for GUI, with no external dependencies.  

*Parsed CSV files must have class/id in the last column for now.*  

## How to run

To plot a dataset make sure the class/id column is the last column.  
- Start program with Java by running `JavaPC/Main.java`  
- Click 'Load CSV', pick your file  
- Click 'Render Plot'  

## Datasets

- `diabetes.csv` - UCI's diabetes dataset. Classes: 0, 1  
- `heart.csv` - UCI's heart disease dataset. Classes: 0, 1  
- `wheat_seeds.csv` - UCI's wheat seeds dataset. Classes: 0, 1, 2  
- `iris.csv` - Fisher's Iris flower classification dataaset. Classes: Virginica, Versicolor, Setosa  
- `mnist_letters.csv` - MNIST's capital letter dimensions of handwriting dataset. Classes: Capital letters A - Z  
- `wbc_diag.csv` - Wisconsin breast cancer diagnosis dataset. Classes: Maglignant, Benign  

## Project Goals

- generate contrasting class colors  
- move dataset processing to preprocssing step on dataset load  
- dataset class abstraction to store mins, maxes, names, classCount  
- detect class/id column on dataset load  
- axis inversion buttons below each axis  
- hyperblock outlines  
- nD datapoint highlighting  

## Screenshots

### Iris dataset render:  
![Iris dataset render](screenshots/iris_render.png)
### Wisconsin breast cancer diagnosis render:  
![Wisconsin breast cancer diagnosis render](screenshots/wbc_render.png)
### MNIST render:  
![Wisconsin render](screenshots/MNIST_render.png)

