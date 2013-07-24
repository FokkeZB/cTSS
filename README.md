# cTSS [ARCHIVED]
This simple set of scripts and UI is a dirty draft for converting [CSS](http://www.w3schools.com/css/) to the [Titanium Alloy TSS](http://docs.appcelerator.com/titanium/latest/#!/guide/Alloy_Styles_and_Themes) format. It's far from perfect but it's a nice starting point.

Having something like this in place would allow you to copy-paste styling from a HTML/CSS UI-builder or [Sketch](http://www.bohemiancoding.com/sketch/)'s CSS export into your Titanium Alloy project.

Please do fork ;)

## Screenshot
![Screenshot](https://raw.github.com/FokkeZB/cTSS/master/screenshot.png)

## Dependecies
This script relies on:

* [JSCSSP](http://www.glazman.org/JSCSSP/)
* [Underscore.js](http://underscorejs.org)
* [Slick.Parser](https://github.com/mootools/slick)

## Resources
Scripts I considered and learned from:

* [Sheet.js](https://github.com/subtleGradient/Sheet.js)
* [CSSOM](https://github.com/NV/CSSOM)

## Roadmap
* Provide more decent UI and verbose logging
* Support and validate more properties (background image..)
* Support and validate more units and values (url, gradient..)
* Real-time parsing while typing CSS

## License

<pre>
Copyright 2013 Fokke Zandbergen

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</pre>
