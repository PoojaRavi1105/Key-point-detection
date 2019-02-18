# Key-point-detection<br/>

Implementation of keypoint detection using SIFT and without using any predefined library functions.<br/>

The keypoint detection is also the first three steps of Scale-Invariant Feature Transform (SIFT).<br/>

1. Generate four octaves. Each octave is composed of five images blurred using Gaussian kernels. For each octave, the bandwidth parameters σ (five different scales) of the Gaussian kernels are changed.<br/>
2. Compute Difference of Gaussian (DoG) for all four octaves.<br/>
3. Detect keypoints which are located at the maxima or minima of the DoG images. <br/>

Skills: Python, OpenCV
