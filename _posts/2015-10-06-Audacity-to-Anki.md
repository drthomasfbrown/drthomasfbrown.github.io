---
published: false
---

Making audio sentence flashcards for Anki using Audacity, the free audio editing software.

**Setting up Audacity**

Install [Audacity](http://audacityteam.org/). Install the [LAME and FFmpeg](http://lame.buanzo.org/) libraries after installing Audacity. LAME enables mp3 encoding. FFmpeg enables importing the audio tracks of video files.

**Making sentence mp3s**

- Open the audio (or video) file in Audacity. Listen to it while observing the waveforms. It is usually very easy to see where a sentence stops and starts.

- Select your sentence by clicking and dragging inside the track.

- Choose "Export selected audio" from the File menu to save your selection as an mp3.

- A alternate, shortcut for exporting multiple mp3s from a single audio track is to use labels. Highlight the portion you want to export, then press Ctrl+B. Type the label you want for that sentence. Then select the next sentence and label it. Repeat until every sentence you want is selected and labeled. Finally, go to the File menu and choose "Export Multiple Files" (Ctrl+Shift+L), and  "Divide files by label". Each selected sentence will be exported  as a separate mp3, using your label as the filename.

- An alternate method is to never export mp3s at all. Instead, you record the sentence directly into Anki. Press the "record" button in Anki, then the "play" button in Audacity. When the sentence ends, press the "stop recording" button in Anki.

**Adding fields to Anki**

- I copy and paste the mp3s into Anki on the front of the card. I also put a picture of some sort.

- On the back of the card, I added two new fields (fields are places to put stuff on an Anki flashcard). Go to Tools/Manage note types, then "Fields" and "Add". I called my two new fields "Target" and "Base". To have them show on the card, go to Tools/Manage note types, then "Cards". Then put the new field names (which are case-sensitive) enclosed in double curly braces onto the back of the card. Like this:

{{Target}}

{{Base}}

- I wanted the Target language to stand out, so that I would not be distracted by the English translation. So I added some css to distinguish the two:

<font size="6">{{Target}}

<br>

<font size="3"><i>{{Base}}</i>

This makes the Target language twice as large. The translation is smaller and italicized. This way I only read it if I really need it. It's like having an immersion card (no English), but with the cheat sheet if one is needed.

