# &middot; [Koroka Solutions Test](https://github.com/VladislavDesu/koroka-solutions-test) &middot; Test task from Koroka Solutions

# Installation

* Install this repository to your device.
* Open it in any Text Editor and run **`npm i`** in your console (for download all packages). You can find a list of all packages in the [package.json](https://github.com/VladislavDesu/koroka-solutions-test/blob/master/package.json) file.
* You can build project by running **`npm run build`** code.
* You can also run **`npm run start`** code, then project will also build, but also start a local server ([Browsersync](https://browsersync.io/)), for comfortable project review or development.

# Technoligies

* Native **`HTML5`**
* Sematic layout
* Adaptive and Responsive layout
* Methodology **`BEM`**
* CSS preprocessor **`SCSS`**
* Native **`JavaScript`**
* Task runner **`Gulp`**

# Structure & Navigation

## Folders

The project consists of two main folders [src](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/src) and [build](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/build).

1. Folder **`src`** contains all source files:

* Folder [styles](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/src/styles)
* Folder [images](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/src/images)
* Folder [scripts](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/src/scripts)
* Folder [icons](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/src/icons)
* Folder [fonts](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/src/fonts)
* File [index.html](https://github.com/VladislavDesu/koroka-solutions-test/blob/master/src/index.html)
* File [registration.html](https://github.com/VladislavDesu/koroka-solutions-test/blob/master/src/registration.html)


2. Folder **`build`** contains all build files:

* Folder [css](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/build/css)
* Folder [images](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/build/images)
* Folder [scripts](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/build/scripts)
* Folder [icons](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/build/icons)
* Folder [fonts](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/build/fonts)
* File [index.html](https://github.com/VladislavDesu/koroka-solutions-test/blob/master/build/index.html)
* File [registration.html](https://github.com/VladislavDesu/koroka-solutions-test/blob/master/build/registration.html)

## Gulpfile.js

I used [Gulp](https://gulpjs.com/) to Develop and Build this project. All gulp's tasks you can find in the [gulpfile.js](https://github.com/VladislavDesu/koroka-solutions-test/blob/master/gulpfile.js) file.

All styles were created by **`SCSS`** code, you can find all source styles in [src/styles](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/src/styles) folder, **`Gulp`** converted all **`SCSS`** files into one build and minify **`CSS`** file ([build/css](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/build/css)).

All images and icons minify by **`Gulp`** task, you can find all images and icons in [src](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/src) folder, **`Gulp`** minify all images and icons and created images with webp format ([build](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/build)).

All fonts you can find in [src/fonts](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/src/fonts) , **`Gulp`** converted all fonts from ttf format to woff2 & woff formats ([build/fonts](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/build/fonts)).

All other files **`Gulp`** copy form [src](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/src) folder to [build](https://github.com/VladislavDesu/koroka-solutions-test/tree/master/build) folder.

## Package.json

This file contains of information about project and list of all packages [package.json](https://github.com/VladislavDesu/koroka-solutions-test/blob/master/package.json).
