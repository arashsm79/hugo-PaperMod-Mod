# hugo-PaperMod-Mod
> A bunch of stylesheets that modify the look of Hugo PaperMod theme. Includes thumbnails and sidebar table of contents.

* [Thumbnails](#thumbnails)
* [Sidebar ToC](#sidebar-table-of-contents)
* [Others](#other-qol-changes)
* [Installation](#installation)


## Thumbnails
<p align="center"><img src="https://user-images.githubusercontent.com/57039957/210163094-3c6c6320-5767-4461-83b3-6c79c2d002e5.png" width="400"></p>

The [thumbnail.css](https://github.com/arashsm79/hugo-PaperMod-Mod/blob/main/assets/css/extended/thumbnail.css) file, uses [CSS Grid layout](https://www.w3.org/TR/css-grid-1/) to change the position of cover images in post entries. It is adaptive and changes the layout if the width of the page is not sufficient as outlined in the video below.

https://user-images.githubusercontent.com/57039957/210163208-14abc20a-8001-4876-a163-9d35cbba3045.mp4

## Sidebar Table of Contents
<p align="center"><img src="https://user-images.githubusercontent.com/57039957/210163280-5a72ee65-b459-4a89-9d15-98e6fa2dc3aa.png" width="400"></p>

The [sidetoc.css](https://github.com/arashsm79/hugo-PaperMod-Mod/blob/main/assets/css/extended/sidetoc.css) file, uses [CSS Grid layout](https://www.w3.org/TR/css-grid-1/) to change the position of ToC to the side in single posts. It sets the [position](https://developer.mozilla.org/en-US/docs/Web/CSS/position) to `sticky` so that the ToC stays on the page while scrolling.

https://user-images.githubusercontent.com/57039957/210163274-178feb2e-1da1-4b8c-9aa8-ad26d88f1d50.mp4

## Other QOL changes
The rest of the files change things such as the default width of the page or the alignment of cover images in single posts.

## Installation
Simply copy the CSS files that you want from this repository to the `assets/css/extended` folder of your Hugo project.
