# SwashTV
SwashTV automated water surface tracing tool

All results from Michael Thompson's PhD thesis are in the 'thesis results' folder. Videos corresponding to the results are available in the following YouTube playlist (https://www.youtube.com/playlist?list=PLJSOHg6_zTjUsTAhVg0pjEFXeCKhVkLDO).

# What does the code do?
The 'swash_tv_unet_processor.ipynb' script takes a distortion corrected and rectified video (e.g. 7_10_swash_tv_07_07_2023_2_11940.0_slomo_1p9.mp4) and returns a beach slope rotated video with the swash water profile annotated. A csv file of the x,t,z,h data is saved as well as a depth timestack graph.

Swash TV deployment:
![Fig_5](https://github.com/mikeyt120/SwashTV/blob/main/Fig_5.jpg)

Distortion corrected and rectified video frame:
![Fig_6_flip](https://github.com/mikeyt120/SwashTV/blob/main/Fig_6_flip.png)

Annotated and rotated video frame:
![Fig_8](https://github.com/mikeyt120/SwashTV/blob/main/Fig_8.png)

Depth timestack graph:
![depth_timestack](https://github.com/mikeyt120/SwashTV/blob/main/thesis_results/7_10_swash_tv_07_07_2023_2_11940.0_slomo_1p9_graph.png)
