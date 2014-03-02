NICAR 2014: Friday
====================

## DataViz for everyone: A practical guide to going responsive
Event: 2014 CAR Conference
Speakers: Lena Groeger, Chris Amico, Ryan Pitts
Date/Time: Friday, Feb. 28 at 3 p.m.
Location: Grand Ballroom West
Audio file: No audio file available.
http://ire.org/events-and-training/event/973/1134/

** Chris Amico **

Assume:

* you're building for the web (not web app)
* HTML, CSS

4 basic approaches;

*HTML
Anything boxy can be HTML, eg [Missouri](http://www.lobbyingmissouri.org/)

*SVG
Good for complex shapes. Zooms nicely. Works with interaction, but can slow as it increases in complexity.

*Canvas
(Couldn't find good eg of resp graphic using it.) 

*Flat images
Eg Quartz chartbuilder. No intereactiveity but doesn't really need it. Probably a right way to do it.

Problem children (will discuss further):
* lables
* legends
* hover
* intereative
* tables
* wide graphics (eg histograms)

** Lena Groeger **

How PP deals with mobile. Four strategies

1. Complete rebuild. Most time, most effort. Completely differnent format. eg [Congress stands on Guns](https://projects.propublica.org/guns/) Made entirely new layout for mobile version on Washington POst. Phone detection and shift to m.* version. PP version used CSS

2. Simplify and adjust. Takes less time, with slightly diffent way. [State-by-state waiting times](https://projects.propublica.org/emergency/). Took most important stuff and stacked up for mobile version. Flow diagram: Keep most important info. Take out the pathways part for mobile, but provide the most important version. [Temp Worker Regulatio](https://projects.propublica.org/graphics/temps-around-the-world) Bar chart flipped from horizontal to vertical. 

3. Hide the problematic elements. [Weibo](https://projects.propublica.org/weibo/) Phone version simply takes out the problematic nav bar. Simply hidden with CSS.

4. Don't have a mobile view. Just use the regular viz much smaller. This doesn't mean it's broke, but barely functional. Eg [Connected China](http://connectedchina.reuters.com/) Simpply doesn't work on phone. At least provide taste of what you would see. No heroics but it's got to work!

** Ryan Pitts **

Responsive charts at [Census Reporter](http://censusreporter.org/). Tables pulled from ACS. Goal: Make easy to use for journalists.

[Profiles pages](http://censusreporter.org/profiles/04000US51-virginia/) have maps, stats, charts, lots of viz. However, still useful in a mobile context.

Charts become less readable as width changes.
Use D3/JS/jQ/CSS/Undersocre/media queries to adjust

Want to delay the decion for as long as possible before chart. Use Python to shape the data into JSON. containers get id and data atribut4es that define chart parameters.

Charts then know how much room they have to work with. 
Change layouts at narrow width, inc bar charts to horizontal orientation.

Hover boxes: Catch touch device interactision 

**Q**: Responive maps. eg US map very naturaly horizontal. [D3 mapping example](http://eyeseast.github.io/visible-data/2013/08/26/responsive-d3/). Could switch to slippy map on mobile.

Mobile scatterplot. Add voronoi layer to create bigger tap targets.

Phone numbers on mobile might be designed as tap-to-dial button. Responding not just to browser size but to user need and device functionality.

** Problem Children **

Problem children (will discuss further):
* lables
* legends
* hover
* intereative
* tables
* wide graphics (eg histograms)



