
## Project Title: CAPTCHA and Sensitive Information Data Generator for OCR Algorithms

### Description
This repository contains the source code for generating synthetic datasets specifically designed for training and testing Optical Character Recognition (OCR) algorithms. The dataset includes two main types of images:

1. **CAPTCHA Images:** These are automatically generated images containing sequences of characters and numbers with added noise and distortion to simulate CAPTCHA systems. The primary use is to help OCR systems improve in recognizing text within complex backgrounds and under various distortions.

2. **Sensitive Information Images:** These images are designed to contain synthetic sensitive information (e.g., names, addresses, ID numbers) in various formats and backgrounds. The aim is to train OCR systems to accurately extract such information from documents while ensuring the protection of privacy and compliance with data handling regulations.

### Features

- **CAPTCHA Generator:** Customizable module for generating CAPTCHA images with varying levels of complexity, including different fonts, noise types, and distortion effects.

- **Sensitive Information Image Generator:** Tool for creating images that simulate documents containing sensitive information, with the ability to customize the type of information, document format, and background noise.

- **Dataset Annotation:** Each image is accompanied by a corresponding annotation file containing the ground truth text, enabling straightforward integration into OCR training pipelines.

- **Privacy Compliance:** Guidelines and tools for ensuring that the generated sensitive information is compliant with data protection standards, preventing the use of real personal data.

### Installation

```bash
git clone https://github.com/yourusername/captcha-sensitive-info-generator.git
cd captcha-sensitive-info-generator
```

### Usage

#### Generating CAPTCHA Images

```python
python gen_captcha.py
```

#### Generating Sensitive Information Images

```python
python gen_text.py
```

### Contributing

### License

### Acknowledgments
