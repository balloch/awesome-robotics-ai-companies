# Contribution Guidelines

These are the guidelines for pull requests to fix issues and add/remove companies.

A NOTE ABOUT ARTIFICIAL INTELLIGENCE VS. AGENT INTELLIGENCE: 
A lot of companies are saying that they have "artificial intelligence" at this point, which includes many on this list. However, the companies on this list are restricted to what could be called "AI agency" or as I refer to it "agent intelligence;" that is, specifically, produces and services using artificial intelligence or machine learning to enable autonomous agents that make their own decisions. This is not to be confused with the umbrella term "AI" being used by business to include generic machine learning, data analysis, and data visionalization to enable _human_ decision makers.  _Occasionally_ this list will include companies focused on highly intelligent agent and robotics transferable technology like companies working on dialogue or computer vision. However we are, for the moment, excluding companies that make the non-intelligence technologies that support robotics and intelligent agents (like the companies that make LIDAR for autonomous cars) unless they _also_ deliver the packages that deploy intelligent decision making. This scope is indeed arbitrary, but a line needs to be drawn somewhere.

### Guidelines
Please ensure your pull request adheres to the following guidelines:
1. If you are adding a company, make sure first that it isn't already on the list, and if it is in an open issue, check it off. 
2. Make an individual pull request for each suggestion.
3. Format should be added alphabetically with one of the schema below. Please try to stick to the "Primary work areas" previously used.
4. Locations should be the "primary engineering locations", should have the city and [3-letter country code](https://www.iban.com/country-codes), and should be separated by semi-colons.
4.1  A "primary engineering location" is a location with a substantial enough percent of the workforce that if it were fully layed off and shut down it would signal a massive negative turn for the company.

For other questions see the FAQ

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
#### What differentiates a large company from a startup with a lot of people and capital?
This can be a nebulus difference, especially for some of the self-driving companies, but the easy-to-agree-on metrics we use are:
1. Is it profitable at scale or does it have enough self-sustaining revenue + long term debt + raised capital that their "runway" is indeterminite?
2. Does it have more than 200 full-time employees?
3. Does it have more than one "primary engineering location" (see above for that definition)?
If the answer to any of these questions is "yes", its probably a "large" company. If the answer to _more_ than one of these is "yes", then it is certainly a "large" company. Otherwise it is a startup. 

#### What constitutes a stable startup?
This is a hard one to answer, but from the past decade watching the industry grow and evolve, a startup can depended on sticking around for at least a few years and making a good effort towards self-sufficiency when it has *at least 4 of these 5 criteria*:
1. Most recent funding is either a Series A (or higher) in the last 12 months, seed funding at the scale of a Series A (>$5MM), or are profitable and do not need to sacrifice that profitability for healthy growth (e.g. Modular Robotics)
2. >10 full-time employees.
3. A marketable product or service (that is, they are beyond only having prototypes) with an active revenue stream active in the last 6 months (12 months max). 
4. Is hiring or was hiring within the last 6 months.
5. Has been active for more than 2 years. 

### What about contributing to this page?
There are no rules. You have entered the Matrix. Just pull request and see what happens! In all likelihood, though, unless its a typo fix or something serious I will not get to it, sorry!
