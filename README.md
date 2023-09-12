# SnapFilter-Face-Landmarks-detector

This project demonstrates real-time face mesh detection using TensorFlow.js and React. It captures webcam video, processes it using the FaceMesh model from TensorFlow.js, and displays the detected face landmarks on the video stream.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## Overview

This project leverages the capabilities of TensorFlow.js and the `react-webcam` library to perform real-time face mesh detection. The FaceMesh model from TensorFlow.js is loaded and used to estimate facial landmarks in the webcam video stream. The detected facial landmarks are then visualized on the video using canvas drawings.

## Prerequisites

Before getting started, ensure you have the following dependencies:

- Node.js and npm (or Yarn) installed
  
  ```npm install```
        or
  ```yarn install```
- Basic understanding of React and JavaScript

## Installation

1. Clone this repository to your local machine:

   ```sh
   git clone git@github.com:visha1Sagar/SnapFilter-Face-Landmarks-detector.git
   cd face-mesh-detection

## Usage
- Start the development server:
```npm start```
     or 
```yarn start```
- Open your web browser and navigate to ```http://localhost:3000``` (or the URL shown in the terminal).
- Grant permission to access your webcam if prompted by the browser.
- You will see the webcam video stream with detected facial landmarks drawn on the video.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request. Make sure to follow the project's code of conduct.
