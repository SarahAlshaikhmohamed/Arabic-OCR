# Arabic-OCR

This project provides an Optical Character Recognition (OCR) notebooks for extracting Arabic text from images and screenshots. It also supports 3D OCR for recognizing text in images with depth or distortions.

## Features

- Converts any Arabic text to video.
- Outputs the video as an `.mp4` video file.
- Uses the `diffusers` library.
- 
- Extract Arabic text from screenshots.
- 3D OCR support for images with depth or distortions.
- Uses the `Arabic-reshaper`, `Python-bidi`, and `EasyOCR` libraries.

## Installation

To use this project, you need to have Python installed along with the `Arabic-reshaper`, `Python-bidi`, and `EasyOCR` packages. You can install the package using the following command:

```bash
pip install arabic-reshaper Python-bidi EasyOCR
```

## How to Use

1. Clone or download this repository.
2. Edit the `image_path` variable in the code to contain the image you want to detect the text for.
3. Run the script, and the output will be saved as `.png` file.

## Example

#### Screenshot OCR Example

Below is an example of extracting text from a screenshot:

![Screenshot Example](/Examples/screenshot.jpg)

Result: 
```
Text: شيئًا, Probability: 0.5019029768637894
Text: واضحًا أدعوك, Probability: 0.958512987115686
Text: ربي لم أجد, Probability: 0.9704067232793966
Text: به، ولكن, Probability: 0.41226640428606914
Text: مايرام, Probability: 0.9996924139993221
Text: ليست, Probability: 0.9795006226467152
Text: على, Probability: 0.9174404740333557
Text: الأمور, Probability: 0.996460876349188
Text: إني أؤمن بالعوض منك  وأشعر, Probability: 0.6964535627476878
Text: بعنايتك بي رغم كل تقصيري, Probability: 0.9067852836778731
```

#### 3D OCR Example

Below is an example of extracting text from a 3D image:

![3D Example](/Output/OCR3.png)

## License

This project is open-source and available under the MIT License.




