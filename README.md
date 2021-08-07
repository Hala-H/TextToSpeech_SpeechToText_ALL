<h1> Text to Speech and Speech to Text </h1>
<p> Smart Methods Task 4 - STT and TTS using Python and IBM Watson </p>

<h3> Task 1 - TTS and STT using Python and IBM Watson Services </h3>
<ul>
  <li> Use python language in IBM Watson to convert speech to text & text to speech  </li>
  <li> Save the output text from (speech to text) as .txt file - <a href="output.txt">output.txt</a> </li>
  <li> Save the output speech from (text to speech) as .mp3 file - <a href="poemAR.mp3">poemAR.mp3</a> and <a href="Elizabeth1Story.mp3">Elizabeth1Story.mp3</a> </li>
</ul>

<p> This jupyter notebook has the speech to text steps <a href="Speech to Text.ipynb">Speech to Text.ipynb</a></p>
<p> This jupyter notebook has the text to speech steps <a href="Text to Speech-checkpoint">Text to Speech-checkpoint.ipynb</a></p> <br>

<p> The steps I followed for the live speech to text: <br>
  
  - Setting up Watson Speech to Text (save the apikey and the region) <br>
  - Accessing the Streaming Speech to Text code from GitHub (cloning the repo <a href= watson-streaming-stt> watson-streaming-stt </a> from github) <br>
  - Installing dependencies (pyaudio) <br>
  - Setting up Configuration (type the apikey and the region in the speech.cfg file) <br>
  - Running Live Speech to Text (run it by this command in the terminal: python transcribe.py -t 10) <br>
  
</p>

<p> The steps I followed for the text to speech: <br>
  
  - Setting up Watson Text to Speech (save the apikey and the region) <br>
  - Authenticating  <br>
  - Converting a file from txt to mp3 <br>
  - Using a new language <br>
  
</p>

<h3> Task 2 - Merge STT, TTS and IBM Watson Assistant </h3>

<p> Allowing the chatbot to respond (check <a href="transcribe.py">transcribe.py</a> for details) </p>

<h3> Task 3 - Reduce delay times between previous services </h3>



