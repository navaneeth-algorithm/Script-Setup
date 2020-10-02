## Setup Steps

### 1. Install Python
### 2. Create virtual environment using command line 
```shell
		python -m venv scripts
```
### 3. Activate Virtual environment
```shell
		source scripts/bin/activate
```
### 4. Change directory + Create scripts directory + move into script directory
```shell
		cd scripts && mkdir scripts & cd scripts
```
### 5. Move Given scripts,requirement.txt,files to this directory
### 6.Upgrade pip
```shell
		pip install --upgrade pip
```
### 7. Install wheel 
```shell
		pip install wheel
```

### 8. Install using requirements.txt
```shell
		pip install -r requirement.txt -v
```
### 9. Install tesseract-ocr
	Install guide for teseract OCR
	[Tesseract](https://www.pyimagesearch.com/2017/07/03/installing-tesseract-for-ocr/)

### 10. Download tesseract trained data
```shell
		wget https://github.com/tesseract-ocr/tessdata/raw/master/eng.traineddata
```
