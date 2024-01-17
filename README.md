# grabcut_mask_and_segmentation

This Python program uses the GrabCut algorithm to perform image segmentation. The input image is read, and a rectangular window is defined to focus on a specific region of interest. The GrabCut algorithm then iteratively refines the segmentation based on foreground and background modeling.

Additional Information

The color spectrum values are flipped to ensure compatibility with the rest of the code.
The rect variable defines the rectangular window coordinates (x, y, height, width) for initial segmentation.
The script uses the GrabCut algorithm with cv.grabCut() and applies a mask to the image.
The final result is displayed with a color spectrum bar, showing the segmented region.
