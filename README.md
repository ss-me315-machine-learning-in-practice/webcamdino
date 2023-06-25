# Webcamdinov2: Video inferencing with Webcam using Dinov2

Using the Dinov2 environment,  this code builds on the inference pipeline to extract images in real-time and process videos in almost real-time. We use mpeg-4 codec to clip the feature extracted video sequence and the original sequence side-by-side. Find the code here: https://github.com/1ssb/webcamdino.

This code should support not using the xFormers library, ideally. The Dinov2 backbone is used, you may change the backbone if necessary. The inference pipeline has been borrowed from Meta and the transformation code from @Esbenthorius. Ideally try to make an image of the dinov2 env in conda, because there are problems integrating with the opencv library. Unfortunately, the documentation in the Dinov2 is not very clear on how to tackle these issues.

This system is not real-time yet but almost there. Well, that is because the inferencing is time heavy so possibly the lag will be permanent, i.e. it will be very difficult to have one even in the future, maybe by acceleration.

Kindly report any systemic issues to Subhransu.Bhattacharjee@anu.edu.au

References: https://github.com/facebookresearch/dinov2, https://github.com/facebookresearch/dinov2/issues/2
 
If you find it useful, you may cite it as: 

S. S. Bhattacharjee (2023) "Webcamdinov2: Video inferencing with Webcam using Dinov2", Retrieved from github.com

