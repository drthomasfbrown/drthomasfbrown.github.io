---
published: false
---


Using Youtube to automate the subs2srs workflow

Say I have a video or audio recording, and a transcript, but no time code information. To make audio sentence cards, I would normally have to cut and paste everything into Anki by hand. This is time-consuming. But I can use a Youtube-to-Keepsubs workflow to automatically generate a time-coded subtitle file. The I can use subs2srs to automatically create audio sentence cards from my original source.

1) I upload my video or audio to Youtube. An audio-only file may first need to be converted to a format that Youtube will accept.

2) In Youtube:

- Select Create new subtitles or CC. We want to make CCs here.

- Underneath the video, click Transcribe and set timings.

- Paste your transcript into the text field. 

- Click Set timings to sync your transcript with the video.

- Setting the timings can take a few minutes. While you wait, you'll be brought back to the video tracklist. Once it's ready, your transcription will automatically be published on your video.

3) In Youtube, navigate to your video and turn on the CCs. Use [keepsubs.com](keepsubs.com) to download the Youtube CC as a .srt file.

4) Now that you have synced video and .srt files, you can generate Anki cards with subs2srs as normal.
