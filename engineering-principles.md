# Engineering & Leadership Principles

*These principles are a mixture of lessons learned from years of practice, and insights of people smarter than me, notably my mentors [Sandy Anuras](https://www.linkedin.com/in/sandyanuras/) and [Andrew Coldham](https://www.linkedin.com/in/andrewcoldham/). Elsewhere, I've tried to give credit where it's due.*

---

## Table of Contents

1. [Engineering Principles](#engineering-principles)
2. [Things to Remember](#things-to-remember)
3. [Leadership Philosophy](#leadership-philosophy)
4. [What I Expect from My Team](#what-i-expect-from-my-team)
5. [What My Team Can Expect from Me](#what-my-team-can-expect-from-me)
6. [Recommended Reading](#recommended-reading)

---

## Engineering Principles

### 1. Make decisions with an eye for quality

> *"If you don't have time to do it right, when will you have time to do it over?"*
> — [John Wooden](https://en.wikipedia.org/wiki/John_Wooden)

Don't sacrifice long-term value for short-term results. Technical shortcuts compound interest. *Note: there are some rare exceptions for this.

---

### 2. Pick tools based on sound reasoning, not fads

Knowing *how* to evaluate tools is more important than which tools you end up choosing. Stay current with the tools you have selected. This includes working knowledge, best practices, and actual versions.

---

### 3. Eliminate undifferentiated heavy lifting

> *"There is nothing quite so useless as doing with great efficiency something which should not be done at all."*
> — [Peter Drucker](https://en.wikipedia.org/wiki/Peter_Drucker)

Before optimizing *how* you do something, ask whether it needs to be done at all.  Corollary: effort invested in building an in-house solution to a previously solved problem almost always means your efforts are not being spent in the most differentiating / impactful way possible.  

---

### 4. Avoid speculative generality and premature optimization

- Simplicity is preferable to generality.
- Building something that solves the problem at hand is preferable to building something reusable that doesn't actually solve the problem at hand.
- Always look for opportunities to simplify existing systems and designs.
- Add complexity *only* when the solution demands it.

---

### 5. Improve your ability to do the work

- Eliminate the unnecessary.
- Streamline and document what is necessary.
- Automate where it is possible and genuinely valuable.
- High leverage investments in DevEx and AgentEx rarely go unrewarded in the medium-to-long term. 

---

### 6. Solve the right problem

- Building the right thing is more important than building the best thing.
- Challenge requirements and propose alternatives. Is the ROI there? Is there a cheaper way to test the hypothesis and iterate toward a solution?
- If a requirement doesn't sound right, it's worth pushing to discuss alternatives.
- [Start with the customer and work backwards.](https://www.amazon.jobs/content/en/our-workplace/leadership-principles) *(Adapted from Amazon Leadership Principles)*

---

### 7. Fix it twice

Fix the problem at hand. Then fix the upstream problem that caused the first problem. Treating symptoms repeatedly is not maintenance. You will eventually fall victim to entropy.

---

### 8. Build self-service codebases

Teams should be comfortable creating PRs on each other's repos. Good documentation and consistent build tooling should support this workflow. Every repository should includes `README.md` and `AGENTS.md` explaining how to get up and running.

Documentation should focus on *why* things are the way they are. The *what* and *how* should be self-evident from the code itself. This is what enables individuals to make good decisions in context, without requiring a synchronous conversation.

---

### 9. Bias towards action and speed

- Give individuals and teams enough context to make meaningful decisions.
- Push decision-making into the teams and the individuals as much as is reasonable.
- Enable the fastest possible iteration: fast builds, fast tests, fast deployments.
- When presented with two or more well-researched options, it is often better to pick one and try it than to engage in additional research with diminishing returns, or worse, decision paralysis.

---

### 10. Make change easy

- Record *why* you made key technical decisions. [Architecture Decision Records (ADRs)](https://adr.github.io/) are a lightweight way to do this.
- Many decisions and actions are reversible. Treat them that way.
- Revisiting technical decisions should not be frowned upon.
- If you are unsure about a decision, put systems in place to roll it back if you learn there was a better choice.

---

## Things to Remember

**Shipping is the first feature.**
Our efforts amount to little if we fail to deliver a solution to customers be they internal or external. Delivering consistently builds trust and earns autonomy. Corollary: a successful business is preferable to an optimal technology solution. If you build something perfect and no one buys it, you still lose.

---

**People are more valuable than code.**
The things we build are generally short-lived. Projects are terminated, products shelved, code deprecated. The greater value is in what we learn in the process. If you attempt something and don't succeed but learn from it, you have not strictly failed. If you don't succeed *and* didn't learn anything that is a problem.

---

**[Gall's Law](https://en.wikipedia.org/wiki/John_Gall_(author)#Gall%27s_law)**
> *A complex system that works can invariably be found to have evolved from a simple system that worked.*

Corollary: complex systems that fail started out as complex systems.

---

**Tech debt and substandard code are not the same thing.**
Bad code and design should not be excused away under the false label of "tech debt." Tech debt accrues from time and entropy, but also when we build systems with an *incomplete understanding of the actual problem being solved*. Sloppy code is just sloppy code.

---

**"I don't know" is an acceptable answer. "I'll find out" is a better one.**

---

**Urgent vs. Important**
When determining priorities, ask whether something is a priority because it's *urgent* or because it's *important*. These are not the same thing. See the [Eisenhower Matrix](https://en.wikipedia.org/wiki/Time_management#The_Eisenhower_Method).

---

> *"Only cost centers brag about cost savings."*
> — [Laura Tacho](https://www.linkedin.com/in/lauratacho/)

Engineers and technical staff can be value generators or cost centres. You want to be a value generator (i.e. your impact makes the company money).    
  
---

**Correlation is not causation.** Make decisions based on data, not emotions or gut feeling.

---


**Organizational hygiene:**
- A mislabeled item or location is worse than an unlabeled one.
- If there is an existing standard, use it.
- Don't keep what you can't use.

---

**4S Approach to Problem Solving** *(Adapted from structured consulting frameworks)*

1. **State** the problem: core question, context, problem owner, stakeholders.
2. **Structure** the problem: around candidate solutions to test, or by splitting the core question into sub-issues to investigate systematically.
3. **Solve** the problem. *(This is typically not the hardest step in the process.)*
4. **Sell** the solution to the problem owner.

---

**On Availability**

Availability (being reachable, present, engaged, and following through) is one of the most underrated leadership traits. It’s not about being in every meeting or responding to every message. It’s about:
1. Making Good: Following through on commitments and closing loops.
2. Making Time: Prioritizing access for crucial people and decisions.
3. Making Space: Being fully present and attentive during interactions.
4. Making Calls: Deciding and operationalizing in a timely fasion.

---

## Leadership Philosophy

*Parts of this section draw from Jocko Willink's work on Extreme Ownership and the broader literature on servant leadership.*

**Leadership is a choice, not a rank. No one has a monopoly on what is right.**

- Leadership and authority are not the same thing.
- Leaders are accountable. They own the mistakes and shortcomings of their teams, not just the wins.
- Leaders respectfully challenge decisions when they disagree, even when doing so is uncomfortable or exhausting. They do not compromise for the sake of social cohesion. Once a decision is made, they commit wholly. *(See also: [Disagree and Commit](https://www.amazon.jobs/content/en/our-workplace/leadership-principles))*
- The team should be engaged in defining their own mission. Everyone on the team must believe in the mission.
- Work with other teams to achieve mutually beneficial outcomes.
- Keep plans simple, clear, and concise.
- Check your ego.
- Figure out your priorities, then act on them one at a time.
- Clarify your plan and communicate it clearly.
- Listen attentively, speak candidly, treat others respectfully.
- Engage with your leadership; keep them in the loop *especially* when they frustrate you.
- Act decisively, even when things are chaotic. Biasing towards two-way doors helps a lot here.
- Leaders operate at all levels. No task is beneath them. If circumstances demand it, a leader will never say "not my job".
- Seek diverse perspectives and actively work to disconfirm your own beliefs.
- Leaders simultaneously raise the bar for everyone *and* seek to raise everyone up.
