colorbrewer-colormaps-4-abaqus
===================

An easy way to use the beautiful color schemes at [ColorBrewer](http://colorbrewer2.org/) in Abaqus to plot contour.

All ColorBrewer color schemes that include at least 8 colors are included. Each color scheme provides more than 8 discrete color palette.


Sequential Color Schemes
-------------------------

Sequential color schemes are good for emphasizing one extreme of ordered data: data collected at different time points, maps of population densities, etc. These color schemes are in the <code>sequential</code> directory. Specifically, there are 6 single hue schemes (Greys, Purples, Blues, Greens, Oranges, Reds) and 12 multihue schemes (BuGn, BuPu, GnBu, OrRd, PuBu, BuGn, PuRd, RdPu, YlGn, YlGnBu, YlOrBr, YlOrRd). Note that color #1 is very difficult to see on a white background.

![Image](sequential.png)

Diverging Color Schemes
-------------------------

Diverging color schemes are good for emphasizing both extremes of ordered data: attributes of those with positive/neutral/negative opinions on an issue, maps of temperature deviation from a mean, etc. These color schemes are in the <code>diverging</code> directory. Specifically, there are 6 schemes centered about white (BrBG, PiYG, PuGn, PuOr, RdGy, RdBu) and 3 centered about yellow (RdYlGn, RdYlBu, Spectral), and the reversed schemes are also included. Note that Spectral is the most rainbow-like of the ColorBrewer schemes, although the central yellows are deemphasized compared to other rainbow or jet color schemes.

![Image](diverging.png)

Usage
-----

Choose your desired color scheme by perusing [ColorBrewer](http://colorbrewer2.org/).
To use any color scheme, just run the python script in Abaqus/CAE. Then in `contour plot option` the new imported scheme could be found.


Credits
------

colorbrewer-colormaps-4-abaqus is forked from [gnuplot-colorbrewer](https://github.com/aschn/gnuplot-colorbrewer), which is written and maintained by [Anna Schneider](https://github.com/aschn). All the scripts are rewritten with python by [Xiaojun GU](https://github.com/x-g).

ColorBrewer is a project of Cynthia Brewer, Mark Harrower, and The Pennsylvania State University.

License
-------

colorbrewer-colormaps-4-abaqus is released under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0), as is ColorBrewer.


   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
