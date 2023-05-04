#### Images

1. **Scale Factors:** Different iOS devices have varying pixel densities. Provide high-resolution images by using scale factors (@1x, @2x, @3x) and ensure appropriate pixel dimensions for each device.

2. **Image Formats:** Use de-interlaced PNG files for bitmap or raster work, optimized JPEG or HEIC files for photos, and PDF or SVG files for flat icons and interface artwork.

3. **High-Resolution Images:** Supply high-resolution images for all artwork in your app for every supported device. Multiply the number of pixels by the specific scale factor and include the scale factor in the image filename.

4. **Color Profiles:** Include a color profile with each image to ensure accurate color representation on different displays.

5. **Testing on Actual Devices:** Always test your images on a range of actual devices to ensure they appear as intended and aren't pixelated or distorted.

##### For tvOS:

6. **Layered Images:** Layered images are crucial for the Apple TV user experience. They create depth and realism through transparency, scaling, and motion.

7. **Parallax Effect:** Parallax is a subtle visual effect that conveys depth and dynamism when an element is in focus. Layered images are required to support the parallax effect.

8. **Layering Guidelines:** Use logical foreground, middle, and background layers in your images. Keep text in the foreground for clarity, and ensure the background layer is opaque.

9. **Safe Zone:** Leave a safe zone around your content to account for cropping and scaling during parallax effects. Avoid placing important content too close to the edges.

##### For watchOS:

10. **Image Guidelines:** Avoid transparency to keep image files small, except for complication images, menu icons, and other interface icons. Use autoscaling PDFs to provide a single asset for all screen sizes.

##### Remember, this summary highlights the essential points from the Apple HIG regarding images. For detailed guidelines and additional considerations, it's recommended to refer to the complete HIG documentation.

https://developer.apple.com/design/human-interface-guidelines/images
