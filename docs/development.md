## Investigate
- [ ] Are members of "encoding" freely named?
- [ ] Divvy up a few examples https://vega.github.io/vega-lite/examples/ and recreate them
	- [ ] Josh: Heat Map Correlation
	- [ ] Rich: Multiple series lines
	- [ ] Rich: facets / multiplot
- [ ] DrawMultiple Operator? https://www.sharpplot.com/SharpPlot-DrawMultiple.htm
	- Could be inferred from data?

## Requirements
### API
- [ ] Specification passed to functions as namespace
	- defaults from each API function (chart type)
	- users can override members
	- includes HTMLRenderer instance
	- can override with JSON namespace or string
### Chart Types
- [ ] Line Chart
- [ ] Box Plot
- [ ] Scatter Plot
	- [ ] ScatterPlotMatrix? https://www.sharpplot.com/SharpPlot-DrawMultiple.htm
- [ ] Heat Map 
### Data Formats
- Single vector?
	- what does SharpPlot do?
- Nested matrix
	- Separate header?
- Inverted tables
	- text matrix and/or VoV
- What other formats do we need?
### Types
- [ ] quantitative
- [ ] temporal
- [ ] nominal
- [ ] ordinal
- [ ] geojson
### Output
- SVG text
### Display / development experience
- HTMLRenderer popup
- Gallery view?
- Headless / no-popup
### Performance
## User stories

- Generate 50 plots, of around 10 series each of around 150 data points each (line graphs). These plots should then be visible 
- How to translate a Vega/Lite example from their website into a new API function
- Embed in a graphical application
- Check Nick's wine example 
- Obtain data from a web service - ⎕JSON table that
## Documentation
- MkDocs?
- How best to share development plan? Google doc? Is there a shared Markdown thing?
## Getting data in
### From Workspace

### From file