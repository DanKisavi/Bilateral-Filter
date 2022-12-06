# bilateral-filter

Bilateral filter implemented in Python 2.7.18, using the pypng library

## Installation Steps
1) Install Python 2.7.18
2) Add SCRIPTS and Python PATHS to your environments variable on Windows
3) ```cd to bilateral-filter folder```

Run commands

4) ```pip2 install -r requirements.txt```


The Python file `main.py` can process an image as specified on the command line
e.g.

    $ py -2 main.py path_to_image.png 3 5 500 path_to_write_filtered_image_to.png

Sample

```py -2  main.py images/testC.png 5 5 250 bilateral.png```

## HOW IT WORKS    

- the first number (3) is the size of the filter to be applied (in this case 3x3)
- the second number (5) is the standard deviation for the distance Gaussian function
- the third number (500) is the standard deviation for the intensity difference Gaussian function

## Show your support

Give a ⭐️ if this project works!