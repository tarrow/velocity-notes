# Velocity Notes

## Meta
These thoughts are my own and quotes may well be mistyped or missremembered.

## Overall Impression
This was a nice conference to attend. While I only attended the last two days which was delivered in a purely lecture style the early workshop days also looked valuable.

Earlier this year I attended VueJS Amsterdamn I returned with strong criticism of the mechanics of the thing. I found this conference to be pleasantly the opposite.

Good stuff:
* Professionally organised and felt professional
* Had plenty of tracks ( 5-7 )
* Food was good
* Venue had sufficient space
* Enough breaks to leave you feeling human

Criticisms of the organisation:
* Lack of power sockets - I came unprepared and had a flat battery by the end of the keynotes on the first day
* The obsesssion with "badge scanning" of the vendors felt a little intrusive as a way to gather email addresses for later spamming
* Huge amounts of waste for coffee, drinks etc..
* I didn't find it all that "friendly"; felt pretty corporate
* Vendor area wasn't great but probably wasn't aimed at me

## Key-Notes (geddit?)
The two days opened with keynotes aimed at all attendees. These were generally less technical and specific in nature.
I would reccommend the very first opening keynote which was principally about making good moral decisions as an engineer.
Given by Harvard prof. Key quotes were "Twitter is a cesspool"; if hate speech on tiwtter focussed on full-stack developers the platform would be moderated te very next day; and, if you're a researcher working on improving deepfakes rather than reducing childhood or pre-natal mortality then you should just leave accademia now.

Talks by google and oracle employees were not particularly enlightning but I liked this quote about metrics: "we tried collect first; analyse later" don't do that. Don't just randomly collect metrics without a plan.

A talk about "the language of observability was good". It was given by someone who saw themselves traditionally as a "Developer" and their collaboration with someone traditionally defined as "Ops". Nice quote was "As a developer production is scary; as an ops person code is scary". The key takeaway for me was that by overlapping our "observability" e.g. metrics, logging, traces that we start to speak the same language and we're able to focus on which of the users needs we are each trying to represent. For example, if developers are looking more carefully at actual page load times then we have more of an apprecation of what "performance driven" ops are trying to do to help users.

Also: "first wave of DevOps was operations people automating stuff with code" "The second way will be developers actually owning their code in production"

Of particular interest to me was a talk by CircleCI who was talking about building good teams and with focus on remote teams. Some things she said:
* good documentation is very important
* be careful of cultural references that might be misunderstood
* be concise
* redraft
* anticipate questions in advance

Suggestions she had for making more distrubuted teams more tightly knit and therefore more trusting of one another:
* Things happen less organically with remote teams; you need to make an effort
* When starting a new small team have a document where people stick social stuff
* Run special interest channels on innernal chat apps (e.g. cooking or lego building)

The last keynote was about security and devops. This one hit home to me because it showed how by following the now fairly standard DevOps paradigms you often get good security by design for free. It's sad the we aren't able to do this yet in most ways.

## Some thoughts on talks in detail
### Talk by JFrog on how to update code in production
We need to update software:
* Users want features
* Security exploits are the new oil spill

Reccommends reading the State of DevOps report.

Sometimes now we have too much data and systems are too complicated to build realistic test environments. That means that we might now need to be able to quickly update and rollback in production.

He gave a funny story about AliExpress (the online retailer) testing their system in production with real users and real packages. Reports of people literally getting random free items out of the blue as parts of testing their stack.

### Talk by Fastly engineer on writing code by voice
For medical reasons this developer found herself unable to type at short notice. Super awesome talk on using a package called talon to write python code for basically creating voice driven macros. She did a live demo of writing a patch and pushing it to git (and did her whole presentation) without touching the keyboard. I am convinced that she is as productive without a keyboard as with.

### TTD of infrastructure
Basically writing unit and integration tests for tools like terraform mostly by parsing the stdout from it. Reccomended as a good way to learn about infrastructure and onboard people. Deliberately avoiding pointless assertions given most people paradigms as decarative infrastructure.

### The state of development of k8s tools
Nice break down. Links to follow. Very basic and therefore ideal for me.
