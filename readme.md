# Star_counter: Capturing the Cosmos with Your Phone and Python

## Objective

This project blends the joy of astrophotography with the power of image analysis. You'll learn to take stunning night sky pictures using your cell phone, then develop Python code to preprocess, identify, count, and analyze the characteristics of stars within your images.

## Project Breakdown

### Stargazing Photography

- **Equipment:** Your trusty cell phone will be your telescope!
- **Techniques:** Learn the basics of long exposure photography with your phone. Research any manual camera settings available.
- **Stabilization:** Consider a simple tripod or a way to stabilize your phone for clear shots.
- **Targets:** Start with brighter star clusters or constellations for easier analysis.

### Image Preprocessing with Python

- **Libraries:** Get familiar with libraries like Pillow (PIL), OpenCV, or scikit-image.
Noise Reduction: Experiment with techniques to reduce noise in your images.
- **Contrast Enhancement:** Improve star visibility by adjusting contrast and brightness.
Background Adjustment: Explore how to even out the background to isolate stars.

### Star Segmentation

- **Thresholding:** Experiment with basic thresholding to separate stars from the background.
- **Advanced Techniques (optional):** Research object detection or blob detection algorithms for more refined segmentation.

### Star Counting and Analysis

- **Counting:** Implement a function to count the segmented stars in your images.
- **Pixel Area:** Calculate the area of each star in pixels. Analyze the distribution of these areas.
- **RGB Analysis:** Investigate the intensity of red, green, and blue components of each star's pixels. Do certain star types show patterns in these colors?

### Tips

- **Control Settings:** If possible, shoot in RAW format for greater flexibility in post-processing.
- **Reference Images:** Find example high-quality starfield images online to compare your results against.
- **Calibrations:** Consider how to account for possible lens distortions of your phone camera.

### Project Extensions
- **Time-lapse:** Capture a series of images and analyze star movement over time.
- **Star Classification:** Explore if RGB analysis can help you roughly classify star types (red giants, blue dwarfs, etc.).
- **Overlay Constellations:** Try to match segmented stars against known constellations in your image.

## Project Goals
1. Take stunning night sky pictures using your cell phone.
2. Develop Python code to preprocess, identify, count, and analyze the characteristics of stars within your images.
3. Compare your results to reference images.
4. Share your findings and techniques with the community.