# Skin Disease Detector

A mobile application that analyzes a photo of a skin lesion and predicts which supported skin condition it may resemble.

Users can choose an image from their gallery or take a photo with their device. The app uses a convolutional neural network (CNN) based on MobileNetV2, adapted through transfer learning to classify the image.

## Features

- **Disease detection:** Analyzes an uploaded or newly captured image.
- **Disease details:** Shows general information about the predicted condition.
- **Medication information:** Displays information associated with the predicted condition.
- **Contact a doctor:** Lets users email or text their doctor. Doctor details—including name, email address, and phone number—can be entered in advance.
- **About:** Provides an overview of the application.
- **Supported diseases:** Lists the conditions the application can classify.

## Model and evaluation

The model was trained on a relatively small dataset. The project reports an accuracy of approximately **96%** on its evaluation data. This result should be interpreted in the context of that dataset and does not guarantee the same performance on new images or in clinical use.

## Important note

This application is an informational project and is not a substitute for professional medical advice, diagnosis, or treatment. Its predictions may be incorrect. Consult a qualified healthcare professional about any skin concern, and do not use the app’s medication information to choose or start treatment.
