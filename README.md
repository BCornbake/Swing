# Swing
An open source interactive platform for template based OCR recognition

## Things to develop
### Backend 
- [x] Template matching module - v1.0
- [x] Integrate Tesseract as OCR engine 
- [ ] Image quality assessing module
- [ ] Image Preprocessing module 
### Frontend 

## Installation 
Install <a href="https://github.com/tesseract-ocr/tesseract">Google Tesseract OCR</a> (additional info how to install the engine on Linux, Mac OSX and Windows). You must be able to invoke the tesseract command as tesseract. If this isn't the case, for example because tesseract isn't in your PATH, you will have to change the "tesseract_cmd" variable```pytesseract.pytesseract.tesseract_cmd```. Under Debian/Ubuntu you can use the package tesseract-ocr. For Mac OS users. please install homebrew package tesseract.

<i>Note</i>: Make sure that you also have installed ```tessconfigs``` and ```configs``` from <a href="https://github.com/tesseract-ocr/tessconfigs">tesseract-ocr/tessconfigs</a> or via the OS package manager.
