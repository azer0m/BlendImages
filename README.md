# BlendImages
Python program for blending/morphing images together.

See the markdown cells in BlendImages.ipynb for further details on the code.

### Running the code
To run the code, place two images you are interested in morphing together within the **images/** folder. Name the first image _src.jpg_, and the second image _dst.jpg_. The first image is the source image (or starting image), and the second image is the destination image (or ending image).

If you are adding new images, you will need to define correspondence points when running the code. See the section within the jupyter notebook labeled **FIRST PASS**. If you're using images already in the code **images/** folder or ones where you've already defined correspondence points, see **SECOND PASS**.

Two sets of images already exist within the **images/** folder, and they already have correspondence points saved in the **saved_points/** folder.

When running the code out-of-the-box, you will hit the **SECOND PASS** case and will be prompted to enter the .txt files for the correspondence points you would like to load from **saved_points/**.

When running the code with **SECOND PASS** commented out but **FIRST PASS** uncommented, you will manually select correspondence points and be asked what name to save the resultant .txt file.
