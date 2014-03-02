NICAR 2014: Friday
====================

## Proper Workflows
Proper workflows for data projects
Speakers: Brian Boyer, John Perry, Ben Welsh, Kevin Schaul **Moderated by Kevin Schaul, Star Tribune

Data manipulation is dangerous. In the new world of data-driven journalism, it's easier than ever to get it wrong. We'll explore best practices to ensure that your data projects adhere to the tenets of journalism — integrity and transparency. The panelists will walk through processes of data projects they have worked on, giving concrete (and, at times, quite technical) solutions to general pain points from the perspectives of reporters, nerds and editors. Bring your questions.


**BB**: Manipulating a dataset in Excel for long tmie, and then realise there was a problem in an early-stage step. So ask "stop doing stuff by hand". Or if you must do it by hand, figure out a way to automate it. As an editor I want to see a full pipeline to how it's the final data that you published, with the ability to see code that hshows how you changed the data every step of the way.

**BW**: Like journalists were hack novelists, now they are hack data nalysists. You need to become a hack dev and adopt some of the process routines so you can get to a shareable, repeatable. Things like version control are absolutely crucial and quickly essential.

**BB**: shows [a shell script](http://blog.apps.chicagotribune.com/2011/03/08/making-maps-2/) "This isn't even programming". It's a set of steps for making a map that could be done by hand, and then stored as a line of script. Essentially a log of steps taken.

**BW**: SQL diary upgraded [using version control](https://github.com/newsapps/making-maps-demo). Comments to make it intelligible are crucial.

**BB**: We keep these files in a known format so differnt team members can understand it.

**BW**: This allows for specialisation in the team, so that . "Please god, use version control" it's really a pain at first, but it wil make sense and quickly becomes a habit.

**KS**: What when you can't automate, like cleaning names

**BW**: You can build a human part of the pipeline into the process. Mid-application we have a private adminstration panel. A researcher's task was to manually clean and update the data brought in by the application. 

**JP**: Even if you can't automate the decision, but you can automate the process.

**BW**: HOw to involve non-programmers: Create inhouse admin panels. Have several differnt environments. So build into your web apps a development or preview enviornment so they can see it in their own enviornment before it is on the web.

**Q**: Data sets changing, where it is an intital manual exploration is crucial to the process. So how to build this into workflow

**BB**: Spot check stuff.

**BW**: At least have a way to get informative error messages.

**BB**: You don't pay attention to automated systems after a while, so they all send email updates giving summary of recent activity

**Q**: Handling data entry when creating sheet from scratch.

**BW**: Don't use a spreadsheet when there is more than one person. [Django](https://www.djangoproject.com/) framework - make database table and an [admin panel generated automatically](https://docs.djangoproject.com/en/1.6/intro/tutorial02/).

**BB**: Use spreadhseets every day for copy editing. All the words on [this site](http://www.lobbyingmissouri.org/) are coming from a Google Sheet. There will be a Tarbell etc. talk later

**Q**: How to deal with editors who don't understand what to look for.

**BW**: You will be the one who is responsible. Scare the shit out of them. Dummy up a wrong page. Show the most provocative view that is possible.

**BB**: OpenRefine is a better way of manipulating a sheet than Excel. But importantly also maintains a full chainge log.

**Q**: If lots of people, project management role?

**BW**: Adopt from software world, but I find that this treats the developer as an infant and not ultimately responsible for their work. But that deon'st mean there's a place for it. Everybody needs an editor. So keep it within your culture. Treat the developer as a reporter, not as disposable coding labour

**BB**: Disagree. Strong advocate of Agile practices. Now have 2 project managers. Usually have 2 small groups working concurrenly. The PM is a peer, not a boss. Just one person to make sure we get to launch. Difficult to wear PM/programmer/editor hats in a single job. Differnet incentives.

**Q**: Version control for databases

**JP**: Set up database so it includes all the variations remain in the database.

**BW**: You never lose the raw data, so you can go back to it, with a trail. [Pro Django](http://prodjango.com/) book. Fabric Python tool for automating steps.

**Q**: What if you can't use the pipeline all the way thorough, eg if there is a 12-hour process in your workflow? Or if the data changes a lot.

**BB**: Would probably keep the data in version control. 

**BW**: Schedule the computer to do the long process every day with a cron job. 

**Q**: What do you unit test, and what should you unit test

**Chris Goskopf**: You should test when you are making an assertion about the world. IF just presenting data that already exists, probably not necessary. But a statement based on derivative data should be tested

**BW**: Formal testing, we only do with our open source libraries. Not festidious enough to do this.`

**Q**: Review procedure?

**BW**: You are respondible fo rthe code that you write in the same way that a reporter is responsible for a quote included in copy. Important: Unfortunatly PM means you the developer do not feel resposiblity for the output. So we have no formal review process.

**BB**: Pair programming. Check each others' work, and we don't always do it, but we do do it when the problem is hard. Usually that is when programmers want to work alone, but that is precisely the wrong time to do it.

**Q**: Shell vs Python? H

**BB**: Use the tools you are comfortable with.