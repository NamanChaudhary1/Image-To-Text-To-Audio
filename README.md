# Image-To-Text-To-Audio-Converter
This is a Python project that utilizes the power of Google Colab to convert an image containing text into an audio file. It leverages the capabilities of Optical Character Recognition (OCR) to extract text from the image, and then uses text-to-speech synthesis to convert the extracted text into an audio file.


![download](https://github.com/NamanChaudhary1/Image-To-Text-To-Audio/assets/91721649/ba047dba-25b1-4224-a03c-930113a142ff)



Features
Image to Text Conversion: The project uses an OCR library to extract text from the provided image file.
Text to Audio Conversion: The extracted text is converted into an audio file using a text-to-speech synthesis library.
How to Use
To use this project, follow the steps below:

Open the project in Google Colab.
Upload the image file containing the text that you want to convert.
Update the image_path variable in the code with the path to your uploaded image.
Run the code cells in the provided order.
Once the code execution is complete, the audio file will be generated.

You can also download the audio file and use it as needed.
Please note that the project requires an active internet connection for the OCR and text-to-speech synthesis processes to work properly.

Dependencies
The project relies on the following Python libraries:

PIL (Python Imaging Library) for image handling.
pytesseract for optical character recognition.
gtts (Google Text-to-Speech) for text-to-speech synthesis.
IPython for audio playback in the notebook.
