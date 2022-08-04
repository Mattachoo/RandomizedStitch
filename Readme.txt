To select different images, update the paths for img_ and img

Update line 129 with the desired subarea to be selected for the algorithm
*Note: Selecting alpha = 1 will result in a standard image stitch

The program will produce images which contain keypoints, mathcing keypoints for both the standard sized image, and the subset image. The resulting stitched image is "output_randomized.jpg"

4 image files are included in this project. 

Selecting images_0001.jpg and image_0003.jpg will produce the best stitch, as they have the most overlap. As images move further than 1, the stitch quality suffers,
which can be seen by selecing image_0001.jpg and image_0007.jpg. 

Utilmately, the stitch fails for both the randomized approach and the standard approach with image_0001.jpg and image_0013.jpg