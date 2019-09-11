# Digital Day 2019: NPR DailyGraphics Next

_Sean McMinn_

smcminn@npr.org

During the session, access this page at www.yellkey.com/center

- [dailygraphics-next](https://github.com/nprapps/dailygraphics-next)
- Shortcomings with WYSIWYGs (chartbuilder, datawrapper, tableau etc)
	- customization
	- image/html
	- responsiveness
- Templatized, responsive graphic making
- Improvements in dg-Next: Don't need to work with code to bulid/deploy graphics
- Can work without coding knowledge, BUT for customization you will need html/css/js (mostly d3.js)
- Demo
	- Launch annotated line chart
	- Show initial view
	- Replace data
	- Add Katrina label (offset y 36)
	- Hed/chatter
	- Show files created, add .tickFormat(d => d + "M") to yaxis
	- Add HTML to source with link `(https://new.uno.edu/research/centers-and-institutes/dber/metro-reports)`
	- Deploy
- Resources to set up: twilburn@npr.org, ahurt@npr.org, smcminn@npr.org 

### Examples of dg-next potential
	
- [Child Poverty](https://apps.npr.org/dailygraphics/graphics/child-poverty-demos-20190227/preview.html#desktop) 
- [Fire Losses](https://apps.npr.org/dailygraphics/graphics/cal-fire-insurance-20190417/preview.html#desktop)
- [Heat/Income](https://apps.npr.org/dailygraphics/graphics/heat-poverty-interactive-20190822/preview.html#desktop)


### APPRX NEW ORLEANS TOURISM DATA [(UNO)](https://new.uno.edu/research/centers-and-institutes/dber/metro-reports):

```
date	Amount
1/1/2004	10
1/1/2005	4
1/1/2006	7.1
1/1/2007	7.7
1/1/2008	7.6
1/1/2009	7.6
1/1/2010	8.2
1/1/2011	8.4
1/1/2012	9
1/1/2013	9.2
1/1/2014	9.7
1/1/2015	9.8
1/1/2016	10.4
```