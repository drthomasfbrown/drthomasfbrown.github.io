---
published: false
---


Using Youtube to automate the subs2srs workflow

Say I have a video or audio recording, and a transcript, but no time code information. To make audio sentence cards for Anki, I would normally have to break out each sentence in Audacity, and then cut-and-paste everything into Anki by hand. This is *very* time-consuming (but can result in some excellent Anki cards). But I can use a Youtube-to-Keepsubs workflow to automatically generate a time-coded subtitle file. Then I can use subs2srs to automatically create audio sentence cards from my original source.

Keep in mind that this workflow could be used to automatically turn an entire audiobook into Anki audio sentence flashcards in a very short time. 

1) Upload a video to Youtube. If you begin with an audio-only file, such as an mp3, you first need to convert it to a format that Youtube will accept. [zamzar.com](zamzar.com) is a free online service that will convert an mp3 to mp4.

2) Once your video file is uploaded, in Youtube:

- Select Create new subtitles or CC. We want to make CCs here.

- Underneath the video, click Transcribe and set timings.

- Paste your transcript into the text field. 

- Click Set timings to sync your transcript with the video.

- Setting the timings can take Youtube a few minutes to accomplish. While you wait, you'll be brought back to the video tracklist. Once it's ready, your transcription will automatically be published on your video.

3) In Youtube, navigate to your video and turn on the CCs. Use [keepsubs.com](keepsubs.com) to download the Youtube CC as a .srt file.

4) Now that you have synced video and .srt files, you can generate Anki cards with subs2srs as normal.
