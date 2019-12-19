  Simple program in Python 3 to take an audio file and transcribe it to unformatted text
  File for transcription will be expected in ~/transcription/audio
  Output transcription will be stored in ~/transcription/output
  Default output will be .docx, with .txt and .odt as alternatives

  required libraries:
      python-docx        (pip3 install python-docx)
      SpeechRecognition  (pip3 install SpeechRecognition)
      pydub              (pip3 install pydub)
      sys                (default library)
      os                 (default library)


syntax:  transcribe.py <filename>

At this point, simply pass the filename to the script and it will return a doc file full of words.  The best words.  
Lots of words.  the audio file must be a .wav, .aiff, or .flac, and must be located in ~/transcription/audio.
The output is only able to do docx at the moment, and will be in ~/transcription/output as <filename>.docx
  
  
 
 TODO:
    convert non supported file types (mp3 to start) to wav
    add options for plain text or odt format.
    decide if I actually need the os library.
    email output to specified email address
    More robust file identification (using python-magic, maybe?)
    possibly add rudimentary formatting capability? (distant future)
    
