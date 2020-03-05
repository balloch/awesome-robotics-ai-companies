# Contribution Guidelines

These are the guidelines for pull requests to fix issues and add/remove companies.

**A NOTE ABOUT ARTIFICIAL INTELLIGENT AGENTS:** 
A lot of companies are saying that they have "artificial intelligence" at this point, including many on this list. However, _this_ list is restricted to those companies that work on "artificially intelligent agency" or "agent intelligence;" that is, the products they produce and services the sell use artificial intelligence or machine learning to enable autonomous agents that _make their own decisions_. I make no claim that there is one correct use of the term "AI," but this is not to be confused with the umbrella term "AI" being used by businesses to include generic machine learning, data analysis, and data visionalization services that enable _human_ decision makers (to say nothing of the services that involve none of the above).  _Occasionally_ this list will include companies focused on technology that supports or directly applies to artificially intelligent agents (for example those working on dialogue, 3D mapping, or computer vision), but I generally try to discourage this.

### Guidelines
Please ensure your pull request adheres to the following guidelines:
1. If you are adding a company, make sure first that it isn't already on the list, and if it is in an open issue, check it off. 
1. Using your discretion, please adhere to the definition of "robotics and AI companies" provided in the note at the top of this page and the [README](https://github.com/balloch/awesome-robotics-ai-companies).
1. Make an individual pull request for each suggestion.
1. Format should be added alphabetically with one of the schema below. Please try to stick to the "Primary work areas" previously used.
1. Locations should be the "primary engineering locations", should have the city and [3-letter country code](https://www.iban.com/country-codes), and should be separated by semi-colons.
   1.  A "primary engineering location" is a location with a substantial enough percent of the workforce that if it were fully layed off and shut down it would signal a massive negative turn for the company.
1. This may be obvious but we cannot add companies that are defunct or in backrupcy proceedings. I am happy to apply a "Formerly" tag if the operations of one company are fully acquired by another (like Amazon and Kiva systems)

For other questions see the F.A.Q.

### Format
For a "large" company with more than one primary working group:
```
 * [Linked Company Name](company link) 
   * Working Group 1 (Locations)
     * Primary work area 1
     * Primary work area 2
     * ...
   * Working Group 2 (Locations)
     * Primary work area 1
     * Primary work area 2
     * ...
```

For a "large" company with one primary working group:
```
 * [Linked Company Name](company link) ("Locations": Locations)
   * Primary work area 1
   * Primary work area 2
   * ...
   * [IF APPLICABLE] "Parent company": Parent company 
```

For a "stable startup" company add this to the *correct locale*:
```
 * [Linked Company Name](company link) 
   * Primary work area 1
   * Primary work area 2
   * ...
   * [IF APPLICABLE] "Parent company": Parent company 
   * [IF APPLICABLE] "Alt locations": alt location 1 ; alt location 2 
```

### FAQ
#### What if one of the prior entries is incorrect given the guidelines?
If you notice this, I beg that you PR. These are important inconsistencies I would like avoid, and unfortunately also the hardest errors to catch.
#### What differentiates a large company from a startup with a lot of people and capital?
This can be a nebulus difference, especially for some of the self-driving companies, but the easy-to-agree-on metrics we use are:
1. Is it profitable at scale or does it have enough self-sustaining revenue + long term debt + raised capital that their "runway" is indeterminite?
1. Does it have more than 200 full-time employees?
1. Does it have more than one "primary engineering location" (see above for that definition)?
If the answer to any of these questions is "yes", its probably a "large" company. If the answer to _more_ than one of these is "yes", then it is certainly a "large" company. Otherwise it is a startup. 
#### What constitutes a stable startup?
This is a hard one to answer, but from the past decade watching the industry grow and evolve, a startup can depended on sticking around for at least a few years and making a good effort towards self-sufficiency when it has *at least 4 of these 5 criteria*:
1. Most recent funding is either a Series A (or higher) in the last 12 months, seed funding at the scale of a Series A (>$5MM), or are profitable and do not need to sacrifice that profitability for healthy growth (e.g. Modular Robotics)
1. Employing >10 full-time employees.
1. A marketable product or service (that is, they are beyond only having prototypes) with an active revenue stream active in the last 6 months (12 months max). 
1. Is hiring or was hiring within the last 6 months.
1. Has been active for more than 2 years. 
#### What about contributing to this page?
There are no meta rules, you've entered the Matrix! If you think you have a way to improve it, pull request and see what happens! It is likely I will approve all minor changes and few major changes.
#### You didn't include my company! What gives??
My intention is to never be biased against anyone, I'm simply one guy trying to make a list in a crazy changing world. You follow the guidelines, and I will always do my best to provide a clear reason for rejection. If it is because your startup doesn't meet enough of the "stability" criteria, don't worry! You're awesome for working on robotics, and I have the utmost confidence that your idea and company will continue to grow. When it does and you start to grow, you can tell me "I told you so!" and will be promptly added to the list. I know the line is arbitrary, and that may seem unfair and personal, but it is not; I simply realized that many roboticists care about the difference between working with a "startup" vs. a "large company" and I had to draw the lines somewhere.
