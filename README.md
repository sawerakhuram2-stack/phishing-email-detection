# AI Phishing Email Classifier

![Project Logo](AI%20Phishing%20Email%20Detector.png)

## Features
- Analyze text pasted by the user
- Display the predicted class and scores for all classes
- Check multiple emails in one run

## Requirements
- Python 3.10 or newer recommended
- Internet connection on first run to download the model

## Setup and run
1. Install Python.
2. Open a terminal in this folder.
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the program:

   ```bash
   python phishing_detection.py
   ```

5. Paste email text. Type `EXIT` to quit.

## Model
`cybersectony/phishing-email-detection-distilbert_v2.4.1` from Hugging Face.

## Important limitation
The model currently returns generic class names such as `LABEL_0` and `LABEL_1`. This project does not claim that a particular label definitely means phishing or safe because that mapping has not been verified. Model scores can be wrong, so do not rely on this demo alone to decide whether an email is safe. Avoid pasting private emails into demos.

## Ideas for future improvements
- Add a graphical user interface
- Verify and document the model label mapping
- Add tests and a small sample dataset

## License
No license is included yet. Choose an open-source license if you want others to reuse the code.
