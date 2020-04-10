The tool is designed to help computed tomography users reduce file size by automatically finding sample/sample holder edges and cropping everything outside. The tool finds the sample/sample holder in every image of the stack, computing the location of the edges. From the whole stack, the widest points are used to crop all the images in the stack, keeping features to scale. The cropped images are then saved to a new folder with the same file name + "_cropped" with the resolution unaltered. You can see how the cropping tool did by looking at the sample output images. If you don't like how the tool performed, you can reselect the sensitivity parameters and run it again. The new output will overwrite the previous output.


For the cropping tool to work, open the jupyter notebook in the same directory as your image folders. The code will automatically index the directory. Just enter the folder name that you want the cropping function to operate on and it will go to work.
Assuming you have python and anaconda installed on your computer, all you need to do is  clone the git repository cropping_abuds. I just download a zip file of the repository. Then open the zip file and unpackage the almond_bud_cropping.yml  conda environment with: conda env create -f almond_bud_cropping.yml. You will then need to activate the environment with the command: conda activate almond_bud_cropping. Now move the Semi-autonomous Stack Cropping Tool.ipynb  to a folder that contains folders of  sequential images that you want to crop. If you have folders with image stacks where the sample size is smaller than the field of view, give it a try.
