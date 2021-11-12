# Last Data (short story / play)

Name is provisional

## Summary

A data scientist joins an online dating company offering both matchaking and Tindr-style in-your-area hookups.  She’s doing some digging into the data, when she discovers that one guy seems to be the last date for a lot of women who have dropped off the platform.  She tries to get in touch with the women by phone, email and social media to find out what went wrong, only to discover that they’re all missing and/or dead.  Shit just got real.

The guy apparently used a fake ID when joining the site, so tracking him down virtually is not bloody easy; it’s also a race against time since he’ll soon find another date or hookup to kill.  Unfortunately she made herself a bit too obvious at some point, and next thing she knows – whilst she’s working late at the office one night – her phone buzzes with an in-your-area connection request...

## What I'm doing here

I will sketch out how a data scientist might approach a new company and/or dataset to give my friend an appropriately cynical idea of how things might go down from a techie perspective.  Some or all of this will need to be skipped over in the actual story, but it’ll give her a library of anecdotes to draw from.

## A Data Scientist’s Diary

### At the job interview

"So we’ve got all this data, and we want to do cool stuff with it, but our database admin says it’s not his thing, and the web and app guys are too busy fiddling with the colour of the logo."

"Well, um, it certainly sounds like I can add some value.  Was there anything specific you were looking at investigating?"

"Not really, but if you could set up a few cool dashboards and visualisations then that would be great.  And the CEO really wants to have some fancy ‘AI’ stuff to brag about in the trade press."

"Fancy AI stuff like... logistic regression, maybe?"

"Yeah, that sounds amazing.  You can do that right?"

"Sure can.  Just to manage expectations: the fancy stuff is usually the tip of the pyramid – you have to spend some time building the foundations of a good data process first."

"Eh, just as long as we get some cute infographics out of it."

The above is very strongly paraphrasing – in reality it’d take an hour-long interview to get the potential employer relaxed enough to admit how clueless they are.  The reference to logistic regression is from an in-joke: "in your marketing literature you call it Artificial Intelligence; in your job ad you call it Machine Learning; in your technical docs it’s Logistic Regression".  LR is pretty much the most basic technique that could conceivably be considered AI if you squint hard.

### Starting the job

"We’re still setting up your network account, so just read this marketing literature until we can get you wired up."

"We’ve got you a network account and email address now, but the person who controls access to the database is off til next Tuesday.  Until then, let's get your work environment up to speed."

"You want... let's see... 'a statistical programming language, a database query console, a data visualisation suite, a local database package, an intranet-accessible web server for routine reporting, a source control repository, a bug tracker, and access to cloud compute resources for big jobs'.  So... we can't just give you a spreadsheet program and call it a day then?"

"Some of your software packages want to download *more* packages?  What is this dark sorcery?!"

***

I've over-focused on the IT application side here; could use some more general stuff like "here are the 57 mandatory online compliance training courses you need to complete before you can breathe near our data".  Also, I suspect my friend will need translations: for example, "compliance" = "stuff we have to do so the regulators, judiciary and/or politicians don't tear us a new one".

### Initial meetings and organisational pathologies

"So that guy over there with the funky bow tie is Bob, who is our company's technical guru.  He's been writing software since back when we all used machine code, haha!"

"Oh really?  What do you write software in now?"

"Machine code."

"..."

"Look, some people have thirty years of experience, some people have the same year thirty times.  Don't rock the boat, OK?"

***

"So this is Sarah and Andy, who handle product management: making sure that all the developers and database admins know what to prioritise, y'know?  And this is Chris and Padma, who handle project management: making sure that we meet all our deadlines in a forward-looking, go-getting fashion.  And this is Kathy and Hiroshi, they keep track of reporting back to senior management and the Board.  And this is Edwin, he runs a pilot project on data implications of gamifying our user experience.  And this is Fatima, she's in charge of data protection regulatory compliance - very important job."

"So who does the actual database administration?"

"Oh yeah, I almost forgot: this is Alvaro, our new graduate.  He just joined us three months ago."

"...Well, hello Alvaro.  How are you finding the job?"

"Please kill me."

***

### Exploratory data analysis

"So... I can't help but some of the dates in this field are in 'dd/mm/yy' format and some are in 'mm/dd/yy'."

"Oh yeah, we took over a small start-up about a year back.  There's still some oddities like that floating around.  But don't worry, it's very easy to figure out: you just check if the customer's unique identifier starts with a P, or ends with a B, R or T.  Or a W, but that almost never happens."

"Almost never?"

"Almost never."

"Okayyyy... I don't suppose this is written down anywhere?"

"Oh no, we've been too busy with the start-up we took over three months ago."

"And I suppose the data from that one is all perfectly integrated?"

"...Only if the unique identifier ends with a W."

***

"Wait, why does splitting the data by sex get me *six* different numbers?  Let's see... 'male', 'female', 'non-binary', 'don't want to say', null, and... 'yes please'.  Yeah, there's my problem right there."

*** 

"So I've linked up our hook-up event data to a database of mobile phone tower locations.  We can now see roughly where people are when they click!  And the most common geolocation is... the middle of the North Sea.  Wow, those oil rig workers are *keen*."

***

Insert more here.  I have *lots* of material to draw on :-/

### Lapse analysis

This is the bit that will put the protagonist on the trail to 

### Random acts of management

Insert here - scope changes, dodgy scheduling ("assume the happy path"), clueless board members, etc etc.