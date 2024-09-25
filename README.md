## YOLO Object Detection

### Table of Contents
1. [Introduction of OpenCV](#introduction-of-opencv)
2. [Image Operations](#image-operations)
3. [License](#license)

---

### Introduction of OpenCV (Open Source Computer Vision Library)
It is a powerful open-source computer vision and machine learning software library. It contains more than 2500 optimized algorithms for a wide range of tasks such as object detection, face recognition, and image processing.
Some of the Important Concepts:

1. **RGB**:

- RGB stands for Red, Green & Blue.
- It is a color model in which colors are created by combining these three primary colors in different intensities.
- In an image: Each pixel is represented by three values, corresponding to the intensities of red, green, and blue.
- The value of each channel ranges from 0 to 255.
- For instance,
  - (255, 0, 0) represents red,
  - (0, 255, 0) represents green,
  - (0, 0, 255) represents blue.


2. **BGR**:

- BGR is another color model, similar to RGB, but with the order of colors reversed. This is the default color space in OpenCV.
- Each pixel is represented by three values, but the order is
  - Blue
  - Green
  - Red
- The BGR format is used in many image file formats and computer vision applications because it aligns with how certain hardware and software handle color.


3. **Gray**:

- Gray (Grayscale) images contain only intensity information, not color.
- In a grayscale image: Each pixel is represented by a single value that indicates the intensity of light at that point ranging from
  - 0 (black) to
  - 255 (white).
- Grayscale images are often used in image processing tasks because they reduce the complexity of the data.


4. **Color**:

- Color images are those that contain color information and are typically represented in RGB or BGR formats. These images:
- Include multiple channels (typically three for RGB/BGR) that combine to produce a full range of colors. Are used in tasks where color information is important, such as object recognition and tracking.


5. **How 0 to 255 is Implemented**:

- The range from 0 to 255 is used to represent the intensity of each color channel or pixel value. This range comes from the 8-bit depth commonly used in digital imaging:
- An 8-bit number can represent 256 different values (from 0 to 255).
- This allows for 256 levels of intensity for each channel in an RGB or BGR image, which is sufficient for most visual applications to create a wide range of colors and grayscale intensities.
- For example, a pixel value of (0, 0, 0) in RGB/BGR represents black, while (255, 255, 255) represents white. Intermediate values represent varying shades and colors.


### License

This project is licensed under the [MIT License](LICENSE).
