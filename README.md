# deluxe-youtube-downloader
Deluxe YouTube Downloader
================================================================================
  YouTube Downloader
================================================================================

A self-contained desktop application for searching, previewing, and downloading
YouTube videos and audio.


FEATURES
--------
  - Search YouTube directly from the app or paste a link to jump straight to a
    video.  Supported link formats:
      * Standard YouTube   https://www.youtube.com/watch?v=...
      * Short links        https://youtu.be/...
      * YouTube Music      https://music.youtube.com/watch?v=...
      * pie.yt share links https://pie.yt/?v=https://youtu.be/...&pieshare=1

  - Preview any video before downloading using the built-in ffplay player
    (opens in a separate window with full audio and video).

  - Download video in multiple resolutions and container formats:
      Resolutions : 1080p, 720p, 480p
      Containers  : MP4, MKV, WebM, MOV, AVI

  - Download audio only:
      Formats : MP3 (192 kbps), FLAC (lossless)

  - Live download progress bar showing percentage, speed, ETA, and file size.


GETTING STARTED
---------------
  1. Double-click  YouTube-Downloader.exe  to launch.

  2. Type a search term (e.g. "lofi hip hop") into the search bar and press
     Enter, or paste a YouTube / pie.yt link directly.

  3. Click a result on the left to select it.  A thumbnail and video details
     will appear on the right panel.

  4. Choose your format:
       - Click "Video" to pick a resolution (1080p / 720p / 480p) and a
         container (MP4 / MKV / WebM / MOV / AVI).
       - Click "Audio" to pick MP3 or FLAC.

  5. Click "Download" and choose a save folder.  The progress bar at the bottom
     of the window shows live download status.

  6. (Optional) Click the "Play Preview" button to watch the video in a pop-up
     ffplay window before downloading.


REQUIREMENTS
------------
  - Windows 10 or later (64-bit).
  - An internet connection.
  - No installation needed.  The EXE is fully self-contained and includes
    FFmpeg, ffplay, and ffprobe.


NOTES
-----
  - The first launch may take a few seconds while Windows extracts the bundled
    files to a temporary folder.  Subsequent launches are faster.
  - Antivirus software may flag self-extracting EXEs.  This is a false
    positive caused by the PyInstaller packaging method.  You can add an
    exception or verify the source code yourself.
  - ffplay.exe must be present inside the bundle for the Preview button to
    work.  It is already included in this build.





LICENSE
-------
  This application uses the following open-source libraries:
    yt-dlp           https://github.com/yt-dlp/yt-dlp
    customtkinter    https://github.com/TomSchimansky/CustomTkinter
    Pillow           https://python-pillow.org
    FFmpeg           https://ffmpeg.org

  Please respect YouTube's Terms of Service when using this tool.
================================================================================
