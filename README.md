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

plate0: 10 results\
- BX41P2     confidence: 87.8295\
- BX412      confidence: 84.8967\
- BX41PZ     confidence: 83.8802\
- BX4DP2     confidence: 83.4717
- BX4P2      confidence: 82.9226
- BX4IP2     confidence: 81.994
- BX4OP2     confidence: 81.0967
- BX41Z      confidence: 80.9474
- BX4QP2     confidence: 80.7907
- BX40P2     confidence: 80.6151
