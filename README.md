# Text_Recognition
Text recognition with OCR (Optical Character Recognition). Using OpenALPR, an open source Automatic License Plate Recognition, written in C++ and with bindings in Nodejs, Java and Python.

### Installation and Application of OpenALPR:

-Download the repo from, https://github.com/Flex-Group/Text_Recognition.

-Make a directory named OpenAlpr and extract the both folders to this directory(OpenAlpr), as follows, C:\Users\user\Downloads\OpenAlpr

-Inside the directory OpenAlpr navigate to the python binding folder as follows, C:\Users\user\Downloads\OpenAlpr\openalpr-master\src\bindings\python. 

-Then open the terminal or console inside this directory (C:\Users\user\Downloads\OpenAlpr\openalpr-master\src\bindings\python) and run the following command, 

$ python setup.py install

-After the installation, for application navigate to the directory, C:\Users\user\Downloads\OpenAlpr\openalpr_64 . Then run the following command,

$ alpr .\samples\au-1.JPG
