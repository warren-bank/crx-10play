### [10play](https://github.com/warren-bank/crx-10play/tree/webmonkey-userscript/es5)

[Userscript](https://github.com/warren-bank/crx-10play/raw/webmonkey-userscript/es5/webmonkey-userscript/10play.user.js) to run in:
* the [WebMonkey](https://github.com/warren-bank/Android-WebMonkey) application
  - for Android
* the [Tampermonkey](https://www.tampermonkey.net/) web browser extension
  - for [Firefox/Fenix](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
  - for [Chrome/Chromium](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
* the [Violentmonkey](https://violentmonkey.github.io/) web browser extension
  - for [Firefox/Fenix](https://addons.mozilla.org/firefox/addon/violentmonkey/)
  - for [Chrome/Chromium](https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag)

Its purpose is to:
* redirect embedded videos from [10play.com.au](https://10play.com.au/) to an external player

#### Notes:

* the data API endoint can be accessed from anywhere to obtain the URL for video streams
  - login is _not_ required
* the URL for video streams can only be accessed from within Australia
  - a VPN is required to watch the stream from elsewhere
  - login is _not_ required
  - _Referer_ request header is _not_ required

#### Credits:

* [yt-dlp extractor](https://github.com/yt-dlp/yt-dlp/blob/master/yt_dlp/extractor/tenplay.py)
  - provided a roadmap for the needed methodology

#### Legal:

* copyright: [Warren Bank](https://github.com/warren-bank)
* license: [GPL-2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)
