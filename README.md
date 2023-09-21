# Text-to-Speech-
Text to Speech 
###Explanation:
This script uses the `gtts` library to convert text to speech and the `playsound` library to play the audio file. The `duplicate_voice()` function takes two arguments: the text to be converted to speech and the filename of the audio file to be created. The function first uses the `gTTS()` function to convert the text to speech and save the audio file to the specified filename. Then, the function uses the `playsound()` function to play the audio file. Finally, the function uses the `os.remove()` function to delete the audio file.
The `if __name__ == "__main__"` block is used to ensure that the script is only run when it is the main module being executed. This is useful when importing the script into another module.
To use the script, simply run it from the command line and provide the text you want to duplicate as an argument. For example:

python duplicate_voice.py "Hello, world!"
​

The script will then convert the text to speech and play the audio file. 
