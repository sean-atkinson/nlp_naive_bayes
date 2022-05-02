# NLP, Naive Bayes, Cambridge Analytica, and Facebook

![Cambridge Analytica logo on a phone in the foreground, with Facebook's logo in the background](https://imgur.com/mNXuoXU.jpg)
*Getty Images*

Many organizations have a substantial interest in classifying users of their product into groups. 

With that in mind, let's place ourselves in the shoes of a Facebook engineer.

Many of us are familiar with the whole Cambridge Analytica and how it tarnished Facebook's reputation since they were able to use Facebook's data in a bid to sway electoral outcomes.

Cambridge Analytica, an organization staffed with lots of Ph.D. researchers, used the Big5 personality groupings (also called OCEAN) to group people into one of 32 different groups.
- The five qualities measured by this personality assessment are:
    - **O**penness
    - **C**onscientiousness
    - **E**xtroversion
    - **A**greeableness
    - **N**euroticism
- Each person could be classified as "Yes" or "No" for each of the five qualities.
- This makes for 32 different potential combinations of qualities. ($2^5 = 32$)
- You can learn more on [Wikipedia](https://en.wikipedia.org/wiki/Big_Five_personality_traits) about the Big5 personality traits.
- There's also [a short (3-4 pages) academic paper describing part of this approach](./celli-al_wcpr13.pdf) if you're *really* interested.

Cambridge Analytica's methodology was, roughly, as follows:
- Gather a large amount of data from Facebook.
- Use this data to predict an individual's Big5 personality "grouping."
- Design political advertisements that would be particularly effective to that particular "grouping." (For example, are certain advertisements particularly effective toward people with specific personality traits?)

**The real-world problem**: "Is what Cambridge Analytica attempted to do actually possible, or is it junk science?"

**The related data science problem**: "Are one's Facebook statuses predictive of whether or not one is agreeable?"
> Note: If Facebook statuses aren't predictive of one being agreeable (one of the OCEAN qualities), then Cambridge Analytica's approach won't work very well!
