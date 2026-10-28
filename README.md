# PBU Newsletter film player

A one-page video player for the Stellantis Pacific BU quarterly newsletter.

The newsletter is sent as an `.html` email attachment, and YouTube refuses to play inside a page opened from a file
("Error 153"). The newsletter shows this page in its film pop-up instead, as `index.html?v=<YouTube video ID>`; because
this page has a web address, YouTube's player works inside it.

- Contains no newsletter content and no videos; it only loads YouTube's own player.
- Published with GitHub Pages at https://mailxabhi-cloud.github.io/pbu-newsletter-player/
