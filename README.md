# eai6020

## Prerequisites

Ensure that Tesseract is installed on your system. For installation instructions for Tesseract please see: https://github.com/tesseract-ocr/tessdoc/blob/master/Installation.md

## Virtual Environment

Virtual Environments help keep isolated python installations aand separated sets of dependencies. If you are working on many python projects on one computer it is highly recommended to use a Virtual Environment. Please follow the instructions on https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/ to install virtualenv and creating your first virtual environment.

Activate the virtual environment. Its typically:

```
source env/bin/activate
```

If its activated, your terminal should preceded with the name of the environment in parantheses.

## Installing Dependencies

Dependencies are installed using `pip`. If you cloned this repo, go to the root directory and run.

```
pip install -r requirements.txt
```

This will install:

- keras
- boto3 (AWS python library)
- pandas
- opencv-python
- matplotlib
- PIL

All of the code is separated into Python notebooks. The primary python notebook showing all work with tesseract is eai6020-tesseract.ipynb. For notebooks showing the use of the different cloud services please find the corresponding notebook with its name. A separate file will be sent with authentication details for the cloud services.