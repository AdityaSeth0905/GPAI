# GPAI
General Purpose AI for CIIE.

Future Goals For GPAI:
1. Add a login System.
2. Add a attendance taking system.
3. Add a feature to take the attendance and convert it into an Excel Sheet.
4. Make every response in Audio Format.
5. Make a feature to ask where is certain sensor in Room 211 and it will show you the graphical representation of it's location and presence.


Date: 12/05/2023
Currently I have added a speech recognition function that stores new words in new_words.json file and whenever it hears a certain words that exist in both new_words.py and responses.py
It returns the value from responses.json .
It also stores the Frequency of the  words added in the dictionary.
And can generate a Words Frequency bar chart using MatPLotLib.matplot package.
I faced so many challenges to make the chart appear and it finally did.

Date: 12/05/2023
The Problems I am facing are:
  1. Sometimes it doesn't record new words for no reason at all.
  2. Sometimes it does record new words but doesn't give response related to it.
  3. Code seems to be correct but idk why it's not working. I took help from ChatGPT and Google Bard but none of them could solve my problem.

Date: 13/05/2023 , Time: 9:00 PM
The Changes I have made:
1. Successfully added the chart for the word frequencies.
2. Divided the program into smaller modules/packages. Like chart_generator.py , word_storage.py , custom_speech_recognition.py , etc.
3. Added a audio response for "hello".

Further Progress Goals for Today:
1. Fixing the problem of audio responses not getting played.
2. Adding audio responses for all responses.
3. Making a Login System that have inbuilt my clear facial image and voice, And check my face and voice for inreal time if they match. Only then i can login to this software and it will only give 3 chances and shutdown if still can't get recognized.
 
 
