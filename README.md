
# Moodify Engine

Moodify Engine is a powerful emotion detection system that uses machine learning to identify emotions from images. It uses a trained model to predict the emotion of a face in an image, and it can be used as a standalone API or through a user-friendly web interface.

## Features

- Emotion detection from images
- API endpoint for integration with other services
- User-friendly web interface for uploading and analyzing images
- Android app for mobile use

## Installation

To install the Moodify Engine, you will need to have Python installed on your system. You will also need to install the required Python packages, which are listed in the `requirements.txt` file.

You can install these packages using pip:

```
pip install -r requirements.txt
```

## Usage

### API

To use the Moodify Engine API, start the Flask server by running the Python script:

```
python moodify_engine.py
```

Then, you can send a POST request to the `/predict` endpoint with an image file. The API will return a JSON response with the predicted emotion.

### Web Interface

To use the Moodify Engine web interface, start the Streamlit app by running the Python script:

```
streamlit run moodify_engine.py
```

Then, open a web browser and navigate to the URL displayed in the console. You can upload an image using the file uploader, and the web interface will display the predicted emotion.

### Android App

To use the Moodify Engine Android app, install the APK file on your Android device. You can then use the app to take a photo or choose an image from your device, and the app will display the predicted emotion.

## Contributing

Contributions are welcome! Please read the contributing guidelines before submitting a pull request.

## License

This project is licensed under the terms of the [Apache License 2.0](https://github.com/dhruv1972/mooodify/LICENSE).

---
