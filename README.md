Video Frame Uploader
====================
[![license](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)

Drop a video and upload frames of your choosing and/or automatically parse
and upload frames from the video to easily tell a story.


Click the image to watch a quick demo  
[![demo video](http://img.youtube.com/vi/hHBhP03JHIQ/0.jpg)](http://www.youtube.com/watch?v=hHBhP03JHIQ)


## Features
- Drag and drop a video to render it as playable in the browser.
- Preview & upload any number of frames by manually navigating to them in the video.
- Have Video Frame Uploader turn your video into an story (collection of equally spaced frames).
- Upload all selected frames.
- Include a description for each frame (to be sent to the server).
- Each frame includes a name that represents the video name and the location in the video.
- Each frame show may be renamed.
- Uploaded frames may be deleted.
- Each frame includes a small preview image.
- Each frame includes a large preview image that can be displayed by clicking the small preview.
- All selected previews may be viewed in a gallery/slide-show format.
- The current time of each frame and the duration of the video will be sent to the server with each frame.
- Compile frame shots from multiple videos.

## Browser Support
- Chrome
- Internet Explorer 10+
- Firefox
- Safari
- Opera 15+


## Questions or Feature Suggestions?
See the [issue tracker](https://github.com/FineUploader/video-frame-uploader/issues).


## Installation
1. Clone this repo: `git clone https://github.com/FineUploader/video-frame-uploader.git`.  Switch to the newly created directory.
2. Load all dependencies, including Fine Uploader: `npm install`.
3. Start the server: `npm start`.
4. Navigate to `http://localhost:8000` in your browser to use Video Frame Uploader.

## Notes
- You may customize server.js, index.html, custom.css, or client.js to suit your specific needs.
- Files are uploaded into an "uploaderFiles" directory under the "assets" subdirectory.
