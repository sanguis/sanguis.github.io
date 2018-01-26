I was at work oneday and some of the Developers were complaing about sudden changes that would happen to the CICD pipeline. At the same time the operations PM was puttingtogahter the monthly newsletter but there isjust not room for all the little tests and changes that are comming up. Not gaiting critera, just options.

I asked how we got the word out and I was informed they have a lunch and learn to inform people of major changes. Then they proceed to make pull requests to the app developers on each apps jenkins files. This is an operations team of 8 people serving a pipleing for almost 150 apps. How many man hours does this take? How much money us spent on just saying sayng hey you can use Retire.js now?

Pulling devs in for a meeting is expensive, adding to a developers inbox with a sindication is going to get light reading at best. And all that time for PR's. oi 

This is one of the problems that as a DevOps archetect I needed to help solve. The solution came to me in a cup of yogart.

I was opening the first cup out of a new case of yogart I had purchased from the local warehose store. In the bottom of the lid was written a message about upcomming changes in in the companies logo and packagaging. I must have seen 50 cups of yogart that looked like this. Every time, I was about to have a snack I would be passivly reminded that soon, I would have to find the new logo when i went to buy it.

I dont subscribe to this yogart's newsletter. I have never been to their website. I don;t have a TV so if they had placed advertisments about the change I dont't know. As an esablished brand I can just add their product to my cart and move on with out even looking. Than the day came. I was shopping my brand was gone, there was some new brand in its place. But when I looked a second time the 50 lids of yogart came to me. This was my brand. I was getting my yogart!

This inspred me to make a change to the feed back that the CICD pipeline gives to its users. When one runs a Jenkins job it pings a simple messegeing service and outputs upcomming changes to the users. its mixed in with unit tests and securoty scans.

The CICD customer does not have to do anything more. We as a system provider are providing  _Continuos Communication_ insode of out Continuos Dilvery feedback.

Now when a developer fails a test becuase of some new gaiting crieria it will not be a shock. They will ahve been seeing that upcomming change every day for a month before it happens.
* I dont have to reley of an email that gets lost in an inbox.
* I dont have to call an expensive meeting to propagate infomration through team leaders or representive members.
* I have provided a path to self service as developers become mroe addpet to maintainerin thier own pipline process.

More technical details comming soon.
