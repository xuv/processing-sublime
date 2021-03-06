# Processing Bundle for Sublime Text 2 (>=Processing 2.0b4)
A [Processing](http://processing.org/) bundle for [Sublime Text 2](http://www.sublimetext.com/2). Check the [demo video](https://vimeo.com/45573600) on vimeo!
Please note: you must have at least (>=Processing 2.0b4), otherwise the buildsystem of the this bundle won't work. The video is a bit outdated, you don't have to run any longer the Processing.app in parallel to run sketches. If you have to stick for some reason to an old Processing verion e.g. 1.5.1 you can use the [old version](https://github.com/b-g/processing-sublime/tags) of this bundle.

###Mac OSX
[<img src="https://github.com/b-g/processing-sublime/raw/master/_Mac/overview.png">](https://vimeo.com/45573600)

Fully supported: snippets + buildsystem.

###Linux
Only works for now with processing-2.0b4
(there seems to be a bug with processing-java in processing-2.0b5 [issue 1334](http://code.google.com/p/processing/issues/detail?id=1334) )

You will need to set your PATH to where your processing application is located. Example:
`export PATH=$PATH:/opt/processing/processing-2.0b4`

Fully supported: snippets + buildsystem.

###Windows
Only partly supported: snippets, but no buildsystem.

## Installation
There are 3 easy ways to install the Processing Bundle:

### Using Sublime Package Control
If you are using [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install the Processing Bundle via the `Sublime Text 2 -> Preferences -> Package Control: Install Package` menu item.

### Using Git
Alternatively you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text 2 application settings area.

Go to your Sublime Text 2 `Packages` directory and clone the theme repository using the command below:
`git clone https://github.com/b-g/processing-sublime/ "Processing"`

### Download Manually
- Download the files using the GitHub .zip download option
- Unzip the files and rename the folder to `Processing`
- Copy the folder to your Sublime Text 2 `Packages` directory e.g. OS X: `~/Library/Application Support/Sublime Text 2/Packages/Processing`

## Usage
- Make sure to run after you have installed the Processing.app `Tools -> Install "processing-java"`, this step is just needed under OSX.

![Use external editor preference](https://github.com/b-g/processing-sublime/raw/master/_Mac/processing_preferences.gif "Use external editor preference")

- Select in Sublime Text the Processing buildsystem: `Tools -> Build system -> Processing`

- Run the sketch: `cmd+b`

## Getting Start With Sublime Text
If you are new to Sublime I recommend the excellent and free video tutorial by nettuts: [Perfect Workflow in Sublime Text](http://net.tutsplus.com/articles/news/perfect-workflow-in-sublime-text-free-course/). If you are short of time, then make sure to watch at least the lession [Multiple Cursors and Incremental Search]( https://tutsplus.com/lesson/multiple-cursors-and-incremental-search/) (~6min), highly recommended!

## Acknowledgements
- This bundle is very much based on [Processing TextMate Bundle by Leon Hong](http://www.onebitwonder.com/projects/processing/), thanks for all the good work!
- I used the [textmate-to-sublime-converter](https://github.com/srbs/textmate-to-sublime-converter) to convert the snippets from the original Processing TextMate Bundle to Sublime Text speak.
- My contribution is only the buildsystem and that finally someone did it :)