---
published: false
---


This is how I made more than 500 audio sentence cards for Anki from a Youtube video for my Spanish study--in only about two hours. Each flashcard features a snapshot from the video on the front, and an audio recording of a sentence. On the back of the card is a transcription of the target sentence in Spanish, with the line before and the line after given for context. Below are the same three lines translated into English.

This method only works with Youtube videos that have a "CC" button to turn the subtitles on and off. WHile this means that not every video can be used with this method, there is no shortage of excellent study material that does feature CC subtitles.

1. I used [Download Youtube Videos as MP4](https://addons.mozilla.org/en-us/firefox/addon/download-youtube/) to download a [documentary of Latin America](http://www.rtve.es/alacarta/videos/historia-de-america-latina/historia-america-latina-poblamiento-america-latina/1780890/) in Spanish from Youtube.

2. Pasting the video's URL into http://keepsubs.com/ results in a downloadable subtitle file in .srt format.

3. That .srt subtitle file can be opened in [Subtitle Edit](http://www.nikse.dk/subtitleedit/). This program will also generate an automatic translation of the Spanish subtitles, using the Google Translate engine. I saved the Spanish and English .srt files separately.

4. I used Handbrake to convert the downloaded video into MKV format.

5. I used subs2srs to create Anki cards out of the MKV video and the two .srt subtitle files.

Not all of the Anki cards thus generated were usable. Some were basically noise. Others had terrible translations that weren't worth fixing. Many are simply too difficult for me right now. At this stage in my progress I'm looking for cards that I can decipher with the help of dictionaries and Google Translate. But setting aside those problem cards, this 52-minute video still resulted in well over 500 useful audio sentence Anki cards.

The documentary features some rather poetic narration, in beautifully-written Spanish. It also features some more academic and analytical language, mostly in the interviews with academics. And the narrator speaks clearly and relatively slowly -- good for a Spanish beginner to decipher.

In summary, this is a very good way to generate i+1 comprehensible input. With two hours of work, I have over 500 cards to study.

Automate audio-with-transcript to Anki audio sentence cards.

Plan:
Obtain audio podcast and transript from veintemundo (news stories, great

from: https://support.google.com/youtube/answer/2734796?hl=en
You can transcribe your video and automatically line up your text with the speech in the video. A transcript contains the text of what is said in a video, but no time code information, so you need to set the timing to sync with your video.

Note: Since the transcript text is automatically synchronized to your video, the transcript must be in a language supported by our speech recognition technology and in the same language that's spoken in the video. Transcripts are not recommended for videos that are over an hour long or have poor audio quality.

Select Create new subtitles or CC.
Underneath the video, click Transcribe and set timings.
Type all of the spoken audio in the text field. If you're creating closed captions, make sure to incorporate sound cues like [music] or [applause] to identify background sounds.
Click Set timings to sync your transcript with the video.
Setting the timings can take a few minutes. While you wait, you'll be brought back to the video tracklist. Once it's ready, your transcription will automatically be published on your video.

---

Hacking a bit 'you can also create a deck with YouTube videos, but we need to extract the subtitles and the video. I tried different solutions to find the process as easy as possible. To extract subtitles I used a program called [Google2srt](http://google2srt.sourceforge.net/en/) , very simple to use, for the videos I looked for a plugin that works.
Just the interface of YouTube has changed and most of the plugins are not working. I found Firefox works purely [Download Youtube Videos as MP4](https://addons.mozilla.org/en-us/firefox/addon/download-youtube/)
