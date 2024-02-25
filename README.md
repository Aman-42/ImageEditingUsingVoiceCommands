# ezEdit: Hands-Free Photo Editing with Voice Commands

## Introduction

ezEdit is an innovative tool that empowers users to edit photos using voice commands, eliminating the need for manual input. This hands-free approach streamlines the editing process, making it more accessible and efficient for individuals.

## Features

- **Voice-Based Editing**: Perform all editing tasks using voice commands.
- **Flexible Image Loading**: Load images from any folder on your computer.
- **Adjust Brightness**: Modify the brightness of your images.
- **Adjust Saturation**: Change the saturation levels of your images.
- **Rotate Images**: Rotate images to desired angles.
- **Adjust Contrast**: Enhance or reduce the contrast of your images.
- **Sharpen Images**: Improve the sharpness of your images.
- **Blur Images**: Apply blur effects to your images.
- **Save Edited Images**: Save your edited images with ease.

## Local Installation

1. **Clone the Repository**: Begin by cloning the ezEdit repository to your local machine.

2. **Update File Paths**: In the `ezEdit.py` file, update all file paths to match the absolute paths on your computer.

3. **Install Dependencies**: Install the necessary dependencies using the following command:

   ```
   pip install tk flask pygame Pillow SpeechRecognition pocketsphinx pynput pyaudio pyttsx3 nltk keyboard tkfontchooser
   ```

4. **Make a Registry Entry**: Create a registry entry to enable the "Edit With ezEdit" option in the context menu for images. Follow these steps:

   i) Press `Windows key + R` and type `regedit`, then click OK.
   
   ii) Navigate to `HKEY_CLASSES_ROOT\*\shell` and create a new key named "Edit With ezEdit".
   
   iii) Inside the "Edit With ezEdit" key, create another key named "command".
   
   iv) Set the value of the "command" key to the following command, replacing `C:\Path\To\Your\Python\python.exe` and `C:\Path\To\Your\Script\ezEdit.py` with your Python executable and script path:
   
   ```
   "C:\Path\To\Your\Python\python.exe" "C:\Path\To\Your\Script\ezEdit.py"
   ```

5. **Edit Images**: Right-click on any image and select "Edit With ezEdit" to launch the program.

6. **Start Editing**: The ezEdit program will be ready for use, allowing you to edit images using voice commands.

## Contributors

- Aman Verma
- Dev Sarode
- Gourav Kothari

## Conclusion

ezEdit is a user-friendly tool that simplifies photo editing through voice commands, making it accessible to a wider audience. Its intuitive interface and powerful features make it a valuable addition to any photo editing toolkit.
