# PicClickAuto
This is a small demonstration using `webcam.js`.The app clicks images through the webcam at an interval of 3 secs and calls a python API to fetch the properties of the image.The properties can been seen on the developer console window of the browser.The python API is in flask and frontend in Javascript.This could be used to collect random images using the camera for data analysis and the properties can be extracted using the endpoint.

## Prerequisites

- [Flask](https://palletsprojects.com/p/flask/)
- Some knowledge on [Webcam.js](https://pixlcore.com/read/WebcamJS)

## Installation
- Create a virtual environment
    ```bash
     virtualenv -p python3 foldername
    ```
- Activate the virtual environment
    ```bash
    source bin/activate
    ```
- Run the flask server
    ```bash
    python imageAutomate.py
    ```
- Hit the url `http://localhost:80/image_info`

If you open the dev tools in browser, you would be able to see the properties of the image clicked in the console log.
