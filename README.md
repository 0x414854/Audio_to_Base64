![Static Badge](https://img.shields.io/badge/python-%233776ab?logo=python&logoColor=white)

# Audio_to_Base64

## **Description**
This Python project converts an audio file (**MP3** or **WAV**) into a **Base64-encoded data URI string**.
<br>It allows copying this string to the clipboard and saving it to a text file for future use.


## **Features**
- **Base64 Conversion** : Converts MP3 or WAV audio files into Base64-encoded data URI strings.
- **Format Support** : Supports MP3 and WAV audio formats for conversion.
- **Automatic Copy** : Copies the Base64 data URI string to the clipboard for immediate use.
- **File Saving** : Saves the Base64 data URI string to a text file for future reference.
- **Error Handling** : Handles errors if the audio file format is not supported.

## **Prerequisites**
- **Python 3.x** installed on your machine
- **base64** and **pyperclip** libraries

## **Installation Instructions**

Make sure you have [Python](https://www.python.org/downloads/) installed on your system before running the install command.

1. Clone this repository to your machine.
   ```bash
   git clone https://github.com/0x414854/Audio_to_Base64.git

2. Run the following command to install the required dependencies:
   ```bash
   pip install -r requirements.txt
   
3. Once the installation is complete, you're ready to run the program!
   ```bash
   python3 audio_to_base64.py

## **Usage Examples**
- Run the Python script.
- Follow the prompts to specify the path to your audio file (MP3 or WAV).
- The Base64 data URI string will be **displayed** and **copied to your clipboard**.
- A text file containing the Base64 string will be saved in the specified directory.
- 
## Tree Directory

Audio_to_Base64/
<br>├── audio_to_base64.py
<br>├── Base64|Bad_Karma.mp3.txt (Example)
<br>└── requirements.txt


## **Example**
**MP3 File** : Bad_Karma.mp3

**Base64 Data** : [Base64|Bad_Karma.mp3.txt](Base64|Bad_Karma.mp3.txt)

I have used this code in my project [Star_Audio_Visualizer](https://github.com/X-Casper/Star_Audio_Visualizer) to convert the audio file 'Bad_Karma.mp3' into Base64 strings.

## **License**
This project is licensed under the **MIT License**.

## **Author**

[**0x414854**](https://github.com/0x414854)
