# Hybrid images
In this study, we are implementing ideas described by Oliva, Torralba, and Schyns in their 2006 SIGGRAPH paper on Hybrid Images (http://cvcl.mit.edu/publications/OlivaTorralb_Hybrid_Siggraph06.pdf). The paper argues that high frequency image content (texture, detail and edges) tends to dominate human visual perception at closer distances. In contrast, at farther distances, only low frequency (smooth) image content is perceived. By blending high and low frequency content, it is possible to create a hybrid image that is perceived differently at different distances/scales.


What are Hybrid Images?
A hybrid image is the weighted superposition (blending) of a blurry (low-pass filtered) version of a first image and a high-pass filtered version of a second image. A blurred representation of the first image is obtained by applying a Gaussian filter The high-pass version of the second image is obtained by subtracting a blurred representation of the image 
