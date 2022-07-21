# ImageStiching
For image stitching, we have the following major steps to follow:

1.Compute the sift-keypoints and descriptors for both the images.
2.Compute distances between every descriptor in one image and every descriptor in the other image.
3.Select the top ‘m’ matches for each descriptor of an image.
4.Run RANSAC to estimate homography
5.Warp to align for stitching
6.Now stitch them together
