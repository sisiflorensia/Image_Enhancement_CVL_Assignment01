# Image_Enhancement_CVL_Assignment01
Comparison of Methods to Improve Noisy Image Quality by Filtering using Median, Gaussian and Average Filters with Various Kernel Size

### Step 1: Select an Image with Noise to be improved

The following image with size 256 x 256 is selected from a google search result:
![selected_image_with_noise](selected_image.png)


# Step 2: Create Filtering Functions


### Step 3: Apply Filtering Functions using Various Kernel Size


### Conclusion

Based on the visual analysis of the filtered images, the Median filter with a 3x3 kernel size appears to be the most effective among the tested kernel sizes (3x3, 5x5, and 7x7) for reducing noise in the selected image while preserving image edges. As the kernel size increased (from 3x3 to 5x5 and 7x7), the image became progressively blurrier, leading to a loss of fine details and edge definition. Therefore, for this particular noisy image, a smaller kernel size like 3x3 provides a better balance between noise removal and edge preservation when using the Median filter.
