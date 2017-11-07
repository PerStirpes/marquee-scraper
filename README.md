# marquee-scraper

## Animate the D3 General Update Pattern

The D3 General Update Pattern describes what happens when a data join is followed by operations on the enter, update, and exit selections. When a visualizations data changes over time and each update can both create new elements and destroy existing ones, the General Update pattern helps convey meaning to users. 

---

This projects takes tweets scraped from a Washington Post article and applies the general update pattern on the tweets. As tweet streams across the screen and after a designated time period a new randonly selected tweet will enter. The catch is that letters in the existing tweet will be used in the incoming tweet and only the letters not in the existing tweet will be brought in to create the new tweet. 

I used the obsolete marquee tag to allow the tweet to scroll across the screen from right to left. The marquee tags names to the title ofthe projects name.

- [d3.transition()](https://github.com/d3/d3-transition#transition)
- [selection.transition()](https://github.com/d3/d3-transition#selection_transition)
- [transition.duration()](https://github.com/d3/d3-transition#transition_duration)
- [transition.delay()](https://github.com/d3/d3-transition#transition_delay)
- [transition.style()](https://github.com/d3/d3-transition#transition_style)
- [transition.attr()](https://github.com/d3/d3-transition#transition_attr)

more to come latter A project

[ ] - add a gif of project in action
