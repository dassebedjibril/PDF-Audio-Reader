# PDF-Audio-Reader

We will build an application through which we are going to convert Pdf to audio. The task is going to be divided into two steps. The first step will be to extract text from a pdf file, and the next step will be to convert that text to a speech and finally, we are going to integrate the above two things in the GUI tkinter window.
The modules required for creating the pdf audio reader are:

#### PyPDF2
is a very powerful library that do some pretty interesting things with PDF documents. The PyPDF2 package is a pure Python PDF library that we can use for a splitting, merging, cropping and transforming pages in a PDF. We can also use it to add data, viewing options and password to the pdf to finally we can use PyPDF2 to extract text and metadata from your PDF.


![image](https://user-images.githubusercontent.com/56389559/164466180-e6638461-8281-4153-a82c-fde337dd8004.png)


#### pyttsx3

is a text to speech conversion library in Python. Unlike alternative libraries, it works offline and it is compatible with both Python 2 and Python 3 and very easy to use. We can sue it to change the voice gender, can change the language, change the volume, change the rate of speeh and change the age of the voice.

![image](https://user-images.githubusercontent.com/56389559/164466095-3fa48c50-2c52-43ac-9f92-d90b4c8f7184.png)

After writing the `Appliaction`, the `main` part is created. After that, write three functions, `Stop_speaking` (tell the engine to start speaking), `speak_text` (tell the engine to start speaking), and finally the `extract_text` (to extract the text from the pdf file). The final entire GUI window will look like this

![image](https://user-images.githubusercontent.com/56389559/164468678-ebc84158-ebf8-4a4a-8aeb-7872aa6d56e9.png)
