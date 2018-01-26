In my life one of the ways I view my job as a DevOps practitioner is to find areas of pain in the Value Stream and eliminate it.

I was at work one day and some of the Developers were sharing about the pain that comes with sudden changes that happen to the CICD pipeline. 

The same day the operations PM was putting together the monthly newsletter. I realized that there was  but there is not room for all the little tests and changes that are coming up. Not gating criteria. Just new options.

A little research and I learned the current process for socializing changes. It involves hosting lunch and learn 's or other meetings to inform people of major changes. 
Then the systems team proceeds to make pull requests to all the app developers on each apps Jenkins files'. This is an operations team of around eight people serving a pipeline for almost 150 apps. How many man hours does this take? How much does it cost to say “Hey you can use Retire.js now”?

Pulling developers in for a meeting is expensive. Adding to an inbox with a one more syndication is going to get light reading at best. And all that time spent making PR's. Oi.

This is one of the problems that as a DevOps architect I needed to help solve. The solution came to me in a cup of yogurt.

I was opening the first cup out of a new case of yogurt I had purchased from the local warehouse store. In the bottom of the lid was a message about upcoming changes in in the company’s logo and packaging. I must have seen this message  on 50 cups of yogurt that looked like this. Every time, I was about to have a snack it would remind me that soon, I would have to find the new logo when I went to buy it.

I don’t subscribe to this yogurt’s newsletter. I have never been to their website. I don’t have a TV so if they had placed advertisements about the change I don’t know. As an established brand I can add their product to my cart and move on without even looking. Finally, the day came. I was shopping my brand was gone, there was some new brand in its place. When I looked a second time the 50 lids of yogurt came to me. This was my brand. I was getting my yogurt! The new design was pretty.

This inspired me to make a change to the feedback that the CI/CD pipeline gives to its users.  When one interacts with it we can tell them how it will change soon.

Now when a Jenkins job runs, it pings a simple messaging service. This service adds news about upcoming changes to the pipeline. It feed back the the user along with with unit tests and security scans. Over and over they see this.

The CICD customer does not have to do anything more to learn about what is on the horizon. As a system provider are providing _Continuous Communication_, inside of the Continuous Delivery.

Now when a developer fails a test because of some new gating criteria it will not be a shock. They will have been seeing that upcoming change everyday for a month before it happens.

* I don’t have to rely of an email that gets lost in an inbox.
* I don’t have to call an expensive meeting to propagate information, through team leaders or representative members.
* I have provided a path to self-service as developers become more adept at maintaining their own pipeline processes.
More technical details coming soon.
