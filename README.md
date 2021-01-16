# whos_that_pokemon?
In the late 90's/early 2000's the global hit series Pokemon featured a segment in their show called "**Who's that Pokemon**?" where the viewer would have to guess which Pokemon was being shown on their screen using only a silhouetted image.
This project aims to replicate that by testing whether or not a CNN can map a silhouetted image to a regular image with moderate accuracy.
The orginal dataset containing 800+ images was reduced to 703 images for this project and can be found here:
[Pokemon Images Dataset](https://www.kaggle.com/kvpratama/pokemon-images-dataset)
![Pokemon Silhouette](https://github.com/JayJJamesJr/whos_that_pokemon/blob/main/pokemon_silhouette.jpg)

The first step was to create a seperate dataset of silhouettes using OpenCV
![001](https://github.com/JayJJamesJr/whos_that_pokemon/blob/main/Screenshot%20(3).png)
![001](https://github.com/JayJJamesJr/whos_that_pokemon/blob/main/Screenshot%20(2).png)
The second step was to pass those images into a neural network and wait...
![001](![001](https://github.com/JayJJamesJr/whos_that_pokemon/blob/main/Screenshot%20(2).png))
The model was able to predict which Pokemon was which with close to 90 percent accuracy.
It ain't much but it was honest work...

