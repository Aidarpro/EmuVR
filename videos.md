To play videos;

1. Create a folder called "Videos" in the EmuVR Games folder ("EmuVR\Games\Videos")
2. *NOT NEEDED ON 1.0.1* Create a file within that folder, and name it "emuvr_core.txt". Enter the following as the contents;

```
core = "video"
media = "Video"
```

3. Place video files within that folder.
4. Run the game scanner, add a new directory (the video directory) and leave the type and core blank.
   * ![](/images/videos_game_scanner.png)
5. *NOT NEEDED ON 1.0.1* Edit EmuVR\Game Scanner\user_custom_playlist.txt with 3-line blocks as shown below (no empty lines in the file);

```
Games\Videos\video_file_name.mp4
My Video Title
anything|anything
```
6. Rescan
   * Note: Scanning, in this case, will not find new video files. We use this button as an automated way to append the custom playlist to the main playlist. The main playlist is always rewritten during a scan, which is why we use the custom playlist file.
   * Note: The scan isn't appending the file properly right now, this is a known issue. Copy the contents of the custom file into the main playlist for now.
7. Start EmuVR
8. Add a "Video" console and insert one of the "Video" carts. Start the console as normal.

The instructions for setting up a Music folder is identical, except replace "Videos" with "Music"


# Controls

Videos also have controls- for now the keyboard commands are listed, Vive/Touch will be added once they're confirmed.

Fast-Forward - Spacebar
Seek (60 sec) - Up/Down
Seek (10 sec) - Left/Right
Pause - P
Subtitles(If applicable) - W
