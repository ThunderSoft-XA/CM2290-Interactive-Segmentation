# Interactive Segmentation Android Demo

### Overview

This sample will accept text entered into a field and classify it as a detected language with a provided confidence score.

These instructions walk you through building and running the demo on an Android
device.

The model file is downloaded via Gradle scripts when you build and run the
app. You don't need to do any steps to download TFLite models into the project
explicitly.


![Language Detector Demo](interactive_segmentation.png?raw=true "Interactive Segmentation Demo")

## Build the demo using Android Studio

### Prerequisites

* The **[Android Studio](https://developer.android.com/studio/index.html)** IDE.
  This sample has been tested on Android Studio Chipmunk.

* A physical or emulated Android device with a minimum OS version of SDK 21
  (Android 5.0) with developer mode enabled. The process of enabling
  developer mode may vary by device.


### Models used

Downloading, extraction, and placing the models into the assets folder is
managed automatically by the download_model.gradle file.