NICAR 2014: Saturday
====================

## Threat modelling

Threat modeling: Security for your story
Event: 2014 CAR Conference
Speaker: Jonathan Stray
Date/Time: Saturday, March 1 at 9 a.m.
Location: Grand Ballroom East
Audio file: No audio file available.

A framework for thinking about 

Example disasters:

AP explosions at White House Tweet crashed market. Was result of phishing attack on Twitter account

Doc filmkakers' laptop in Syrian gov hands; sources told to flee

Hacked twitter accounts.

Sources exposed:
* Vice McAfee location
* AP phone records subpoena
* filmaker's laptop siezed in 

What are we protecting?

* commitment to sources
* Physical safety
* legal concerns
* ability to operate
* reputation

There is no central repository of jounralistic organisations being 

Important:

* Journalists are a high-risk profession
* Target even if not on a sensitive story, because you are an attack vector to work on a story
* For sensitive stories, you ned a plan


What EVERYONE in the newsroom needs to know:

* Passwords. Use good passwords
* Use two-factor authetnticaion is essential, esp on email master account. Only marginally inconvenient.

* consider password managemnet tools

** Phishing **

Most journalistic security failures are due to phishing.
Phishing is getting much more sophisticated. Comes from an apparently trusting source, like a colleague. Only says click on  link, which also looks like trusting source. Cut and paste links to avoid that problem? ** Don't click on links in mobile web browsers. **

[question: phishing site may be on a trusted domain due to W]

If you have clicked a URL, check the URL you are on. Easy to mimic a site, but much harder to fake the domain.

** Spear phishing **

Learn everything about you from public sources or other hacked email to create an email targeting you which is contextually accurate with personalised messages.

** Defening against phishing **

* Develop spidy-sense that something is wrong.
* Read the URL before you click
Always read the URL because typingin a password
Report suspicious links to IT security
If you don't have a security person -- it's you by virtue of being in this talk.


** Threat modelling for your story **


If there is a keylogger on your laptop, it doesn't matter what encryption you're using.

Can't guarantee you won't be hit by a car, but you can make it far less likely.


** Series of questions: **

* What do I want to keep private/protect?
* Who am I protecting from
* What can they do? What is expensive for them? What capabilites to they have
* What is the actual risk?  You will have to make choices  including that that you can't do the story at all.

What are you protecting?
* Emails and comms
* Photos, footage, notes
* your addressbook, travel itineraries, etc
* metadata

Privacy vs anonymity
* Harder to keep identity secret is much harder than keeping what you are saying to them. Eg letters: post office workers can see the address, but not the contents. Much harder to communicate without revealing information

Even more difficult: Not being able to know that you are communicating at all. 

** Scenario 1: Syria **
Photojorunalist with digital camera in Syria. WIll publish the pictures eventually. Limited internet access available in a cafe. Shot on camera and laptop. How do you get it back to home office?

Option 1: If carrying out encrypted, might not be able to know the password.

We are allowed to make choices about risks to ourselves. We are not allowed to make choices for our sources.

Option2: Electronic transmission
Use of VPN is good, but may reveal that you are in-country and working for a news organisation.

File metadata: remember photo and PDF files have GPS location, as in Vice case. You will need to scrup the metadata. **AP has a policy of disabling the GPS on any cameras going to conflict zones.**

** Q2: Who wants to know? **

Am I really up against the NSA? Because the answer is almost always no. Which is a big relief. Much more commmonly teh adversary is the subject of your story.

Insider trading scenario. People passing your documents. How to do it: Not digitally is ideal.

Are you more worried about someone breaking in and stealing your notebook, or hacking your notebook. There is no such thing as "more secure"", there's only "more secure against a particular threat".

Protect sources from the institution. Must assume someone in IT is logging that. No  legal or technical protection from that. So best to avoid the bank's IT infrasturcture 

Encrypting email to work address in this scenario is probably even worse, because it flags it. 

** Q3: What is adversary likely to do? **

Sexy to think about being hacked. But walking into the office under false pretenses and sitting down at your computer is probably easier in many places.

* Technical: hacking, intercpeted comms, code-breaking
* Legal: Suits, subpoenas, detention
* Social: Phishing etc
* Operational: The one time you didn't use secure channel, the one person you shouldn't have told
* Physical: Theft of hardware, malware installation, network taps, torture ([rubber hose cyptoanalysis](https://en.wikipedia.org/wiki/Rubber-hose_cryptanalysis))

Opsec is specialist. First rule is "don't tell people".

What is the adversary's capability? What are they likely to do? Where does it coincide with my 

eg, take your laptop out of your room when you go for dinner in China.

** Q3: Local police misconduct. Talked to sources including officers and victims. Would prefer crooked police chief

Legal threats: lawsuits to slow you down, enjoin you. Obtain records to identify sources with subpoena. [seize and impound equipment](http://www.washingtontimes.com/news/2013/oct/25/armed-agents-seize-records-reporter-washington-tim/?page=all)
Physical: Threaten violence
Technical: 

** Last question **

What's the risk? WHat happens if thye win? How much security do I need, and what does it cost? Securty is never free. 

* Blown story
* Arrested source
* Dead source

Tradeoff between ability to operate and what I'm risking.

Sould we do the story at all, especially if the source cannot make informed consent abotu the risk to themeslves.

** Scenario 4 **

Technical threat. Working in Europe assisting a chines human rights activists. Chinese Gov does not know he's an activist. How to talk to inside chine?

What to use? Gmail? Gmail is an american company that collaborates with many countries. But will it hand over my comms to my adversary. Google probably better at securing it than you. If you adversary is the US gov, this would not work. Gmail is not a bad choice for working in China.

Jurisdictional arbitrage. What can your adversary do? Can issue a subpoena in the jurisdiction where you r data is held? If not, this is good.

** Tools **
This is not where security talks shuold end, not start. You need to understand the threat before you 

Data at rest vs data in motion. Email while in flight vs on your compueter. Need to secrure both storage and communication.

1. Storage. Easty to see reporing notes need to be secure. But less obvious that metadata of comms need to be secure. 
2. Comms in motion: encryption. This iss where most security talks start. Will my source be able to use the tools reliably? If source is unsophisticated

OTR messaging. Protocol that many programms speak. Gives privacy but not anonymity. Not same as GChat OTR.
Crypto.cat: easy OTR.

Not for someone's life depending on it. Easy to use, though.

Man in the middle. If someone has control over the channel, eg the telco's physical connection. Then need to use fingerprints to make sure both people are seeing the same things.

Encryption vs anonyminty. Tor is best option for anonymity. Best way is to downloed the browser bundle

SecureDrop: To accespt anonymous sybmissions via Tor. You get no record of who dropped it. Innovation of Wikileaks inially was that they didn't know who their source was.

MOBILE SECURITY
phones are a security disaster.
They are a tracking device that phone company has this.
Can they be your adversary.

The Guardian Proejct: Tor on phone

Silent Circle. Commercia service. Have solved problem of secure comms with non-technical sources.

Where do you store your data. Should be your own premises, not in the cloud.




