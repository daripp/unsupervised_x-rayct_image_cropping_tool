# cropping_abuds
The cropping_almond_buds.yml environment and the semi-autonomous stack cropping tool are designed to help computed tomography users reduce file size by automatically finding sample/sample holder edges and cropping everything outside. The cropped images are then saved to a new folder with the same file name + "_cropped" with the resolution unaltered. You can see how the cropping tool did by looking at the sample output images. If you don't like how the tool performed, you can reselect the sensitivity parameters and run it again. The new output will overwrite the previous output.

For the cropping tool to work, open the jupyter notebook in the same directory as your image folders. The code will automatically index the directory. Just enter the folder name that you want the cropping function to operate on and it will go to work.

