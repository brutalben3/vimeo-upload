```
 _    ___                    
| |  / (_)___ ___  ___  ____                                       
| | / / / __ `__ \/ _ \/ __ \   ┌───────────────────────────────────────┐
| |/ / / / / / / /  __/ /_/ /   | ▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒  %75     |
|___/_/_/ /_/ /_/\___/\____/    └───────────────────────────────────────┘
                     Upload                   

```
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/websemantics/vimeo-upload/master/LICENSE) [![GitHub forks](https://img.shields.io/github/forks/websemantics/vimeo-upload.svg)](https://github.com/websemantics/vimeo-upload/network) [![GitHub stars](https://img.shields.io/github/stars/websemantics/vimeo-upload.svg)](https://github.com/websemantics/vimeo-upload/stargazers)
[![Percentage of issues still open](http://isitmaintained.com/badge/open/websemantics/vimeo-upload.svg)](http://isitmaintained.com/project/websemantics/vimeo-upload "Percentage of issues still open") [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

> Upload videos to your Vimeo account directly from a browser or a Node.js app.

Try it [LIVE](http://websemantics.github.io/vimeo-upload/)


## Install

Using Bower
```
Bower install vimeo-upload
```

Or npm

```
npm install vimeo-upload
```

## Usage

Include `vimeo-upload.js` in your index.html.

```
<script src="/path/to/vimeo-upload.js"></script>
```

Create a new `VimeoUpload` initialized with a Blob or File and Vimeo Access Token then call `upload()` to start the upload process.

```javascript
var uploader = new VimeoUpload({
  file: file,
  token: accessToken,
});

uploader.upload();
```

Your access token need to be authorized by Vimeo. Create new Vimeo access token [here](https://developer.vimeo.com/apps).

Check `index.html` for details and additional parameters you can include when initializing `VimeoUpload`.

## Credits

Sample code for uploading files directly with XHR/CORS: [cors-upload-sample](https://github.com/googledrive/cors-upload-sample)
