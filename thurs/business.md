NICAR 2014: Thursday
====================

## Business
Speaker: Rob Barry, WSJ rob_barry

Accurist/LexisNexis: powerful public records databases

Example of use at Alan Stanford story: Look up employees at the company that just collapsed -- and call them all.

Includes people who are not high ranking and have nothing to lose

** S&P Capital IQ **

Similar to Bloomberg term. 

* bankruptcies
* corporate buybacks
* directors at distressed cos
* cos with lots of cash
* recently delisted companies
* Corporate timelines
* Annotated tickers
* Analysts covering companies (eg what did the market think about x in 2008. Can find analysts who were covering something at the time.)

** PACER **
Heavily used. Outragous that it charges as much as it can. 

* Bankruptcy cases
* cicil suits
* local jurisdictions also work

** other **

* local licencing records
* guidestar -- good for nonprofits
* LionShares by FactSet -- info on corporate holdings
* Property tax records
* campaign finance/lobbying (state and local)
*
Think of it as forensice; piece togetehr information. Eg finding common addresses that tie together documents

** SEC **

For publicly traded cos
You cand download everything in Edgar in one shot, and write tools to anlayse.
Two ways to get data:
* Search for filings (what most people do)
* FTP users directory -- 
* Using SEC bulk data. What events drove company stock prices. Find material news filesing (8Ks). Download in bulk. you want the files called master
* Will give you every singled filing in the database. pipe-seperated data structure.

** now forcing companies to file in a standard format called XBRL. **

http://en.wikipedia.org/wiki/XBRL

This data shows you in a standard form, the information in a filing.

analysed 4m records of insider trades


** Second speaker ** 

Phil Matera (ph) Good Jobs First/ Corp research project

http://www.goodjobsfirst.org/

SubsidyTracker website. New version out today.

state and local govs put subsidy data on web, but not in a search-friendly form. Obscure reports, etc on hard to use sites.
Collected all info into unified database.
variety of forms: credits, abatements, cash grants etc.
Attempted to id parent company of the company getting the subsidy. Often an obscure subsidiary. Want to be able to aggreate the subsidies going to larger companies.

Tagged each company to its ultimate parent in a "painstaking" process 965 different companies with summary pages

http://www.goodjobsfirst.org/subsidy-tracker

== mego ==
http://dirtdiggersdigest.org/

Goal is to get as close to 100 pc of publically available subsdiies.

Limited by staff size.



Questions. SEC data
used c# to import it into a MS SQL database, but could into any other. It's only on the order of a couple of million records.
If you want analysis of text of earnings reports y0u are getting into a much larger prblem

State procurement contracts -- would be great to have them in central database. openRFP project
