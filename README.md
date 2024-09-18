!pip install googletrans==4.0.0-rc1 gtts
Run the Tool:
After copying and pasting the above code into a code cell, execute the cell.
The program will ask for the source language, target language, and text to translate.
If you want to play the translated text as speech, the program will use gTTS to generate an MP3 file and play it using IPython.display.Audio.
Example Walkthrough
You start by typing "list" to see supported languages or enter the ISO codes for the source and target languages.
You input the text for translation, and the tool will display the translated result.
If you choose to enable text-to-speech (yes), the tool will generate a speech audio file and play it in Colab.
Notes:
You can choose any supported language for translation by entering the respective ISO language code.
The tool supports over 100 languages, which can be listed using the "list" command.
The translated audio will play directly in the notebook when using Google Colab.
This implementation provides a robust multi-language translation tool with text-to-speech functionality that is fully compatible with Google Colab!
