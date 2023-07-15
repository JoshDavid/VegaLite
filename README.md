# VegaLite

VegaLite is a JavaScript library that provides a high level grammar for describing modern plots and graphs. 
This library is an attempt at programatically generating the VegaLite specification, and rendered HTML, for you by making inferences based on your dataset so you can quickly produce data visualizations from an APL array with minimal specification neccesary.

Current examples:

BoxPlot:

![image](https://github.com/JoshDavid/VegaLite/assets/31487826/ff195a45-1405-4b89-bcfa-a38c58dfbbfa)


ScatterPlot:

![image](https://github.com/JoshDavid/VegaLite/assets/31487826/71a0fa8c-6a25-4241-ba85-4dd94b1d1b45)


Major version 0 of this library is still very much an exploratory WIP, but it can already be used to produce useful graphics. 

Key features required for a major V1 release include:
  - Expanding the list of exposed functions in API
  - Allowing more advanced users to provide their own custom VegaLite specification
  - Allowing integration to hook into existing HTML Renderer objects or HTML sites
  - Providing an easy way to export the images as different file formats (.PNG, .SVG, etc.)
  - Looking into performance enhancements to work on large datasets (million+)
  - Allowing for different array input formats (Matrix w headers, vector of vectors, etc.)

