NICAR 2014: Thursday
====================

## Fracking
Speaker: Tom McGinty (WSJ)
http://topics.wsj.com/person/M/tom-mcginty/1434
tom.mcginty@wsj.com

* How many people live near wells that have been drilled.
* Databased from drillingInfo. Got it for 11 states where fracking is going on.
* 1.8m wells. Coordincates, dates drilling and produciton cmmencenced
* Census blocks for those states.

Data into SQLserver. In arcmap you can connect to any data source

How many people live within a mile of well.
Once well points plotted, created 1-mile buffers. This creates a new shapefile of the buffers -- ie circles around points.
Then add census blocks and climp to work out block area/ total block area.
Allows estimate of affected population assuming uniform distribution of population in the census block.

In SQLserver 2008, you can save shapes within the database.

Instead of Arc, can do this all directly within the database.
(took screenshot of slide with query structure)

Shape2SQL (free tool for moving shapefiles to databases)

Wells' head may be at a certain lat/long coordinate, but they extend hoizontally underground, so who is really within a mile is unclear.

pres will be at ire tipsheets.


**Speaker 2**
Mike Soraghan (EnergyWire)

Am not a data reporter. Am fracking beat reporter.
Oil and gas drilling is my beat.
wrote series called Overflow
http://www.eenews.net/special_reports/overflow

How many spills in all of these oil and gas wells.
found there were 6000. If you add up the spilled fluid, it was more than the exxon valdiz in 1989.

Not a lot of honest brokers in oil and gas drilling. There are  few academics, but most have a bias.

If you ask for this data, you will be the first person who asked for this.

States oversee drilling. The federal goernment does not. The main regulation of drilling is at the state level. For data, that's bad. The feds fill out everything in triplicate. The states range from dilligent to Bubba in a Pickup truck checking wells.

Have to go state by state to relevant agency. All have some sort of spill data. 

includes blowouts, leaks, lightening hitting tanks etc.
"frack hits"

All call a spill something different, from "undesirable events" in one state "report of loss" in Texas.

--- lots of US state-specific stuff ---

FracFocus
Private non-profit even though they have public data.
Started as a nice voluntary disclosure thing.
States are starting to disclose to FracFocus.
But the data only comes out as PDFs
Could try to scrape it. They will actively fight back.
Enviornemental group called skytruth tried to do this, but they are being blocked.
Any state that disclosure through FracFocus, so relevant to FOIable. Colorado and Pennsylvania were getting 1/5 of each report late.

https://www.dropbox.com/s/wanunt2rsjkkq7w/NICAR%20Tipsheet2.docx