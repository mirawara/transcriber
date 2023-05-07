<h1 align="center" id="title">Transcriber</h1>

<p align="center"><img src="https://img.shields.io/badge/Python-3.10-3776AB.svg?style=flat&amp;logo=python&amp;logoColor=white)](https://www.python.org" alt="project-image"></p>

<p id="description">Transcriber is a python program that allows you to transcribe any large audio and video into any language using the SpeechRecognition library and the Google API. It splits the file into chunks during silent moments because the library doesn't accept files that exceed a certain size.</p>

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Noise reduction
*   Volume increase

<h2>🛠️ Installation Steps:</h2>

<p>Install the requirements:</p>

```
pip -r requirements.txt
```

<h2>🖥️ Usage: </h2>
<p>Manual:</p>


```
transcriber.py [-h] -f FILE [-nr NOISE] -o OUT [-iv IV] [-l LANG]

options:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  Path to audio file
  -nr NOISE, --noise-reduction NOISE
                        Noise reduction: there are two levels: level 1 - Basic noise reduction (recommended) level 2 - Massive noise reduction
  -o OUT, --output OUT  Path to output file
  -iv IV, --increase-volume IV
                        Increase volume: you have to provide a float from 0 to 3 in the form int.dec
  -l LANG, --language LANG
                        Language (Default: en-EN)
 ```
 
 <p>Example: </p>
 
 ```
 python3 transcriber.py -f audio_example/Subconscious_Learning.mp3  -o result.txt -nr 1
 ```

<h2>😉 Tips: </h2>

1. Use ChatGPT to write the transcript better, punctuation included. It can also be useful for summaries and maps.
2. If the transcription fails even after trying the various levels of noise reduction and volume increase, try changing the parameters of the 'split_on_silence' function to better suit your requirements.

<h2>💖Like my work?</h2>

Contact me if you have any corrections or additional features to offer me.
