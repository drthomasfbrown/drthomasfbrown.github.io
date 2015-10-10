---
published: false
---


Using Youtube to automatically turn a video (or audio) transcript into a synced sub-title file

Say I have a video or audio recording, and a transcript, but no time code information. To make audio sentence cards for Anki, I would normally have to break out each sentence in Audacity, and then cut-and-paste everything into Anki by hand. This is *very* time-consuming (but can result in some excellent Anki cards). But I can use a Youtube-to-Keepsubs workflow to automatically generate a time-coded subtitle file. Then I can use subs2srs to automatically create audio sentence cards from my original source.

The beautiful thing is that Youtube is smart enough to take your transcript and automatically align it with the audio track in your video. This saves you a *lot* of time.

Keep in mind that this workflow could be used to automatically turn an entire audiobook into Anki audio sentence flashcards in a very short time (assuming that you have a transcription of the audiobook).

1) Upload a video to Youtube. If you begin with an audio-only file, such as an mp3, you first need to convert it to a format that Youtube will accept. [zamzar.com](zamzar.com) is a free online service that will convert an mp3 to mp4.

2) Once your video file is uploaded, in Youtube:

- In Video Manager, click the dropdown next to your video.

- Select "Create new subtitles or CC". This takes you to a page entitled "Manage subtitles and closed captions". In the dropdown named "new subtitles or CC", choose the language matching your video's audio track.

- Choose "Upload a file" and upload your transcript. I saved my transcript in .txt format and Youtube had no trouble with it.

- Click "Set timings". Youtube will now automatically sync your transcript with your video's audio track (but only if they are in the same language).

- Setting the timings can take Youtube a few minutes to accomplish. Once it's ready, your transcription will automatically be published on your video.

3) In Youtube, navigate to your video and turn on the CCs. Use [keepsubs.com](keepsubs.com) to download the Youtube CC as a .srt file.

- Note that your Youtube video has to be published to the world in order for keepsubs to extract the subtitles. If you have uploaded a copyrighted video, remember to delete it from Youtube -- or at least set it to private -- after keepsubs has finished its work.

4) Now that you have a video that is time-synced with a .srt subtitle file, you can generate Anki cards with subs2srs as normal.

Unfortunately, Youtube will not sync a translated transcript. Both transcript and audio have to be in the same language. You can, however, use Subtitle Edit to automatically generate a translated .srt file using Google Translate.