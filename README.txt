NFC HIDDEN GIFT WEBSITE — MOBILE VERSION

FILES TO UPLOAD TO GITHUB
--------------------------
index.html
surprise.html
video.mp4

VIDEO
-----
Recommended:
- Resolution: 1080 x 1080
- Format: MP4
- Video codec: H.264
- Audio codec: AAC
- Frame rate: 30 fps

IMPORTANT:
Name your video exactly:

video.mp4

Then you do NOT need to edit the HTML.

If your video has another filename, open surprise.html and change:

<source src="video.mp4" type="video/mp4" />

Example:

<source src="my-gift-video.mp4" type="video/mp4" />


GITHUB PAGES
------------
1. Create/open your public GitHub repository.

2. Upload:
   index.html
   surprise.html
   video.mp4

3. Go to:
   Settings > Pages

4. Under Build and deployment:
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)

5. Save.

6. Open the GitHub Pages URL on your phone.

7. Test:
   NFC URL -> index.html -> Open the surprise -> video plays

8. Write the main GitHub Pages URL to your NFC tag.


MOBILE SUPPORT
--------------
The video page is optimized for a 1080 x 1080 square video.

It:
- Automatically fits the phone width.
- Preserves the 1:1 aspect ratio.
- Does not crop the video.
- Supports inline playback on iPhone.
- Supports phone safe areas / notches.
