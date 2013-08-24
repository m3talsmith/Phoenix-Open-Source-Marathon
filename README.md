Pull Request Share-A-Thon
============================
A collaborative endurance competition for coders in Phoenix.
---

Participants
===

@m3talsmith  - [Restful Model](https://github.com/thedeepwoodsbrigade/restful-model)

@RickCarlino - [FrozenJS](https://github.com/rickcarlino/frozen)

@bbyler      - Something about databases???
### What is it?
As open source developers, we love to code, but often complain about loosing focus or having a lack of collaboration. By creating this event, we hope to create a collaborative and focused event that allows open source developers to share ideas and work together on the projects of their choosing. We hope this event will help developers get ahead on their open source projects while fostering open source involvement.

### How do I register? How does this work?

Developers may request entry by submitting an issue to this Github repo or by contacting me, Rick Carlino, personally.

When submitting a request for participation, please provide basic information about yourself and a link to the Github repo you would like to enter in the marathon.

On **August 30rd**, participants will be placed into a random order and their respective repositories will be showcased.

On **September 2nd**, all participants will participate by providing 7 continuous days of pull requests to the respective participant's repository in the order that it was selected.

### How does it work?
Together as a team, we will spend 7 days working on one participant's project. This usually means submitting pull requests, fixing open issues and making their test suite pass.

When the 7 day period ends, we move to the next project which are in a random order (see code below)

### What are the rules?
All of these rules are up for discussion. Please submit a pull request if you would like to change the rules.
 * All projects must be under an open licenses such as GNU GPL, MIT, etc...
 * All projects must be hosted on github.
 * Participants must provide some form of guidance on how they would like their repository contributed to. This can be done in a number of ways, such as a todo list in the readme.md, a list of unclosed issues or a failing test suite.
 * If you previously entered a project into the marathon which is currently unstable or incomplete, you may not enter a new project during this iteration. Finish what you started, slacker.
 * Those who join after the first 7 repositories are entered may still do so, but will not be able to enter a repository of their own. This is in the name of time more than anything.
 * If a repo hits stable status before the 7 day mark, we will move to the next repo on the list. "Stable" means that all tests pass, all issues are closed and no new features are needed.
 * You are encouraged to watch this and all other related repos in the marathon so as to stay up-to-date on happenings.

### Is it possible to lose?
Oh yeah. Contestants who fail to submit pull requests on more than three occasions shall be disqualified.
 
### What happens if I lose?
 **PULL REQUESTS WELCOME FOR THIS SECTION.**

Losers who fail to keep up in the marathon must buy drinks at the end-of-marathon beer session. Also, shame tweets or appropriate photos may appear ... ;)

### Beer, aye?
We will go have drinks at the Mellow Mushroom in Deer Valley off of I-17. Date is yet to be announced.

### What do you mean 'picked at random'?
Like this:
```ruby
devs = ['a', 'bunch', 'of', 'names']
3.times{ devs.shuffle! }
puts 'We will work on entries in the following order: '
devs.each{|name| puts name}
```
Pretty scientific, eh?
