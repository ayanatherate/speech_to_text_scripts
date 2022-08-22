# speech_to_text_scripts
<h1 style="font: monospace">Speech Recognition- Transcribing text from an audio file using DeepSpeech, SpeechRecognition, Vosk and AssemblyAI API. </h1>

<h3> Performance accuracy, as observed by me, in order (for an audio with Indian-English accent): </h3>
<p1> Assembly AI API ***> Google's Speech Recognition lib** > DeepSpeech > Vosk </p1>

<p2> *** Best accuracy achieved. However Assembly AI API is a paid service. The free version can be used easily but has it's limitations. (5 hours of transcribing per month): <br> <a href="https://www.assemblyai.com/?utm_source=google&utm_medium=cpc&utm_campaign=brand&utm_source=google&utm_medium=cpc&utm_campaign=Brand&utm_term=assemblyai&gclid=Cj0KCQjwr4eYBhDrARIsANPywCizR8ffTN2GC0JYEYCL6U7a8zOZ3yEyMLkVq6Bc2Z2ruOg2lPY9-WgaAjCcEALw_wcB"> Assembly AI </a>
<br>
** Satisfactory accuracy for En-IN accent, have to play around and tweak offset (covered in my notebook) for the library to detect and transcribe a large audio file.
<br>


