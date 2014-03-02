NICAR 2014: Saturday
====================

##  Presentation as a storytelling 

http://ire.org/events-and-training/event/973/1188/

You won't believe what static site generators can do for news apps
Event: 2014 CAR Conference
Speakers: David Eads, Tyler Fisher, Brian Boyer
Date/Time: Saturday, March 1 at 3 p.m.
Location: Chesapeake
Audio file: No audio file available.
This session will cover two static site generators that have been developed particularly for news: the Chicago Tribune's Tarbell and NPR Visuals' app template. We'll go over how to bootstrap a project on each and the benefits that each generator provides.

This session is good for: People who want to build static news apps that never go down and are unafraid of the command line.

===

[NPR's app template](github.com/nprapps/app-template). Two very similar projects.

an opinionated project template for client side apps. Everything we do starts with this, everything is static.

Purpose is that decisions are 90 pc of the things you need to decide every time. Template is customisable.

No backend database.. 

Flask app. Lots of local python. =Sinatra for Ruby
Fabric. allows to run commands from command line

Once touch deployment handled through Fabric. Jinja2. Are like handlebars or Django. 

Everything is on S3.
Everything uses Bootstrap. All colours etc we need is there.

Peewee - Whatever else we need. Little python ORM.

clone the repo. 

Generates tickets in Github, for routtine process tasks

[Example repo from generator](https://github.com/TylerFisher/nicar-rulez)


===

** Chicago Tribune's [Tarbell](http://tarbell.tribapps.com/) **

Had been WP and Drupal dev. Lots of CMS work.
CMS that uses Google Sheets and bakes out static files.
First Tarbell project was [Playing with Fire](http://media.apps.chicagotribune.com/flames/index.html).

Similar to NPR app. Run a command and integrate with google sheets.

When happy, dei

During election was updated live by making a flat file every 
Good because lots of people in the same docuemnt at teh same time.

Photo desk reporter and intern built the [Chicago Under the Gun](http://graphics.chicagotribune.com/under-the-gun/) site. There was a developer time at the end. Biggest success in terms of user engagement.

We are putting Microcopy, not data into the spreadsheet.

**Q:** On spreadsheet managment: WE ask editors to put their names in the column they have edited.

When you redesign the paper, you don't go back trhough the archive.


