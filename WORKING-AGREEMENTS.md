## Working Agreements
These are our team working agreements. We're a distributed team, so some of these agreements are to help us communicate better when everyone's not in the same room.

### Don't deploy late in the day without prior agreement from the team.
Particularly Fridays at 6pm :). At Waffle we continuously deploy our code to production; a merged PR will be seen by customers in less than 5 minutes. When you merge a PR, it's your responsibility, with help from the team, to monitor for any unforseen customer performance or usability impacts. That's hard to do when we hit merge and walk out the door.

### Clear Acceptance Criteria and Sizing before a card is moved into "Current Iteration"
As our team grows, it's important to make sure the work we do is clearly defined before we do it. The AC and the Size are determined by the team, usually during a weekly planning meeting. This working agreement helps us all stay on the same page with what we're committing to during an iteration.

### Use the `expedite` label for any work that's pulled into "In Progress" and supercedes current work.
For example, a customer reported bug might need to be expedited. Put the `expedited` label on it, so the whole team knows that we're blocking other work to jump on it.

### Talk about any work that's moved to "In Progress" or "Current Iteration" outside of a planning meeting, either in the team chat tool or during Standup.
We plan in one week increments (called Iterations). It's common for interrupt work to be added to the current iteration based on customer support needs. For any interrupt work, make sure we talk about it to keep the team in sync.

### PRs for all code changes
Since Waffle is continuously deployed via [Codeship](https://codeship.com) when anything is committed to master, it's important for us to use Pull Requests to review code and make sure automated tests pass. Committing directly to master is only acceptable for emergencies, and should still be reviewed by a peer.

### All PRs should be code reviewed and functionally reviewed before merging
Ideally PRs should also be deployed to our staging environment, if possible.

Wait until someone gives you a :+1: before merging.

PR's should contain [comprehensible commit
messages](https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message)

### Review PRs after standup, if not sooner
As a distributed team, it's sometimes easy to miss reviewing a peer's PR. We don't want to stop the flow of work to have PRs reviewed immediately, but they should be looked at right after our morning Standup if they're still un-reviewed. The Waffle "Needs Review" column is the best place to see if there are open PRs that need someone's attention.

### Work that can be public should be public
Our Waffle board is publicly available at waffle.io/waffleio/waffle.io. Any work that can be made public should be made public for everyone to see what we're working on (and why!).

### How do we modify our working agreements?
Any teammate can suggest we modify, remove, or add a working agreement. Any change needs to be accepted by the whole team, using a fist of five vote:
- 5: This change to our working agreements makes me the most excited I've ever been to work together as a team
- 4: This change is great, 100% on board
- 3: I'm not that passionate about it, but I'll agree to it and not complain about it.
- 2: I have some reservations. I can't agree to this until we work through them.
- 1: I can't agree to this.

