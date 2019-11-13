# Keynote is pretty funny - some harvard guy

Blockchain enthusiasts are the purest form of mainsplaining.
"Twitter is a cesspool"

Opening a twitter account today is like starting smoking at 43.

Developers suffer from a lack of moral imagination. People who suffer form hate speech are underrepresented in the tech community.
Hate speech would be shutdown tomorrow if it was aimed at fullstack devs.
Have some moral backbone: if you're improving deepfakes just stop now.

This talk was good

# Karthik - the good the bad and the ugly of k8s
Foundations of oracle cloud is: functions; k8s engine,
Oracle container engine for k8s. One of the most popular offerings.
Used lots internally tomorrow

Learnings form building the platform:
* Started with fullstack team
* Everyone should be able to build everything
* Hard to keep up to date with everything

Split into teams:
* control plane
* platform

They tried a collect first analyse later. This was hard to understand and figure out whether it was correct. Don't just randomly collect metrics.

Burnout - difficulty in firefighting vs building or fixing the actual issue

This guy jumps over a million different topics and it's hard to keep up.

Rotating the feature team through the on call cycle.

This talk was pretty pointless apart from the moment about metrics.

# Chrstine - The importance of observability
Ops and devs speak different languages. Velocity vs reliability
Everyone is trying to figure out what the customer is thinking.
Everyone has their own tools for asking the customer and tracking that: e.g. logs/monitoring/help desks/CRMs etc...
Why is this bad?
As a dev living in dev land - thought of production as a scary place
Ops persons thinks  of code as dangerous

# CircleCI lady - building good distributed teams
I need to meet my team once in a while to remember they are actual People

Introduction document for social connections.
Special interest channels on mattermost
Mentoring pairs? Proactive offers of teaching?
Trying to figure out at a bigger scale what problems are we trying to solve?
Key of staying humble; making space for others. How much space am I taking up right now?
Building relationships; stengthening trust; with pair programming

Hero culture: reducing pressure on individuals. It can be really bad becuase it sets up the hero for failure. We don't want one person to become the only person who can solve problems.
Hero culture is toxic both for the teams and for individiuals.
Try to document things that we learn.


Documentation is difficult. We should try and avoid social and cultural references.
Be short and succinct.
Is the message and expectation clear
Can I anticipate any responses?

Documentation is an investment in future success.

Continuity: building a team is never done. It's an investment we make every day.

# Last one ever
This is the last Velocity. Some pretty nice talks about it.
It will now be an infrastructure and Ops conferences. Trying to move away from tools and towards.

# Security and DevOps
Security must marry DevOps or it won't survive. We need shared concerns about security.

How to control chaos.

Chaos engineering for security.

Expect security controls to fail and prepare accordingly. We should also assume users will fail. Don't avoid all security incidents. Focus on resillience to them instead.

Games days: like planned fire drills. What gamedays should we priorotise.

We should see if we have our monitoring, and alterting in place.

Worry mostly about the least cost path to security exploits.

Distributed
Immutable - stuff isn't custom so we can just roll back and kill stuff
Ephemeral - e.g. rooktiting a resource that disppears in seconds is pointless

With infosec start with dumb testing before moving to fancy.
Chaos test retrograde libraries.

Cloud billing becomes a security signal.

We should try to make infosec, fun, interesitng and something we all feel responsible for.