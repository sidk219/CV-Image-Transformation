# Image Transformation App

This is a simple web application built with Streamlit that allows users to upload an image and apply various image transformations, including rotation, scaling, translation, shearing, and custom affine transformations.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)

## Features

- **Image Upload**: Users can upload an image from their local system.

- **Image Transformations**: Users can apply the following image transformations:
  - Rotation: Rotate the image by a specified angle.
  - Scaling: Change the image size by adjusting the scale factors.
  - Translation: Shift the image horizontally and vertically.
  - Shearing: Apply shearing to the image.
  - Custom Affine Transformation: Define a custom 2x3 affine transformation matrix for advanced transformations.

- **User-Friendly Interface**: The web app provides a user-friendly interface with sliders and buttons for applying transformations.

- **Background Customization**: The background color of the app can be customized for aesthetics.

## Requirements

To run this project, you need the following:

- Python (3.6 or higher)
- Streamlit
- Pillow (PIL)

You can install the required Python libraries using pip:

```bash
pip install streamlit pillow
```

## Usage

1. **Upload an Image**:

   - Start by clicking the "Upload an image" button. This will allow you to select and upload an image file from your local system. Supported formats include JPG, PNG, and JPEG.

2. **Select a Transformation Type**:

   - Choose the type of transformation you want to apply from the dropdown menu. Available options include:
     - None
     - Rotation
     - Scaling
     - Translation
     - Shearing
     - Custom Affine

3. **Adjust Transformation Parameters**:

   - Depending on the selected transformation type, you will see relevant sliders and input fields. Use these to fine-tune the parameters of the transformation.

4. **Apply the Transformation**:

   - Click the "Apply" button that corresponds to the transformation parameters you've adjusted. The app will process the image with the selected transformation, and the transformed image will be displayed in the app interface.

5. **Custom Affine Transformations**:

   - If you choose the "Custom Affine" option, you can input a custom 2x3 affine transformation matrix with values for scale, shear, and translation. After inputting the matrix, click "Apply Affine Transformation" to apply the custom transformation.

Enjoy experimenting with different image transformations using the Image Transformation App!
