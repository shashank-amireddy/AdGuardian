
AdGuardian
==========

**AdGuardian** is a Chrome extension that fast-forwards and skips ads, providing an uninterrupted viewing experience on various websites.

Features
--------

*   **Ad Skipping**: Automatically skips ads, letting you enjoy content without interruptions.
*   **Fast Forward**: Speeds up ad playback, reducing wait times.

Installation
------------

1.  **Clone or download this repository.**
    
2.  **Open Chrome and go to** `chrome://extensions/`.
    
3.  **Enable Developer mode** by clicking the toggle switch at the top right of the page.
    
4.  **Click the "Load unpacked" button** and select the directory where you cloned or downloaded this repository.
    

Usage
-----

*   Activate the extension on websites with ads.
*   Ads will be automatically fast-forwarded and skipped.

Development
-----------

### Files

*   `manifest.json`: Defines the extension's configuration and permissions.
*   `background.js`: Contains the service worker that handles ad detection and skipping.
*   `content.js`: Contains the logic for fast-forwarding and skipping ads.
*   `popup.html`: Displays information about the extension when the extension icon is clicked.
*   `icon.png`: The extension's icon.
*   `popup.js`: Calculates the number of ads skipped.

Contributing
------------

Feel free to fork this repository and make improvements. Pull requests are welcome!

Author
------

[Shashank Reddy](https://github.com/shashank-amireddy)