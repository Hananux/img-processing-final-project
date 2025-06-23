## Img Processing final project
Name: Hanan
Surname: Abazah
Student ID: B2280.060166
Major: Software Dev

## About the Project

This is my final project for the Image Processing course. The project includes 6 problems that cover different image processing techniques using Python and OpenCV. I used only the images that were shared with us in the project folder.

Everything was done in a Jupyter Notebook, and I tried to explain each step using markdown and comments in the code. All results are shown with images.

# How to Run the Notebook (in VS Code)

Open the .ipynb file in VS Code using the Jupyter extension.

make sure the image files are in the same folder as the notebook (Theyre included)

Run each cell in order. I kept each problem in its own section to stay organized.

The images (original and processed) will show up under each part side by side 

I added comments in the code and markdown cells to explain what I did and why.

If anything doesn’t work, make sure all the required libraries are installed

# Used Libraries
-  cv2 (OpenCV): for image processing functions
    
-  numpy: for numerical operations and array handling
    
-   matplotlib.pyplot: for displaying images and plots

-   random: for selecting random pixels

# problemes faces: 
I started the project using colab and had to redo it on a different software to store it locally.

When applying inverse log transform directly, the image appeared black cuz the values were out of range
so I scalled the imgs before expm1 to avoid that