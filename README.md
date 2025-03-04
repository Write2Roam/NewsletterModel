# An interactive dashboard to do annual revenue planning for a newsletter business.

## Thoughts on functionality

- Want to be able to input a target revenue amount, and have it work backwards to calculate things like free subscribers needed, paid subscribers, events hosted, etc.
- Assumptions: Advertising should be 25% of overall revenue.
- I'd like to be able to change the proportions of revenue from different sources, and see how that affects things. For example, if we want to make $250k, and 25% of that is ads, it should basically answer two questions: What should the audience look like in order to make that much on ads, and what are options for the remainder of the pie?

## I should be able to input:

- Target revenue
- Proportion of revenue from ads, paid subs, events.
- My advertising CPM, and number of weekly sends (to help calculate total ad revenue)

## From that data, it should calculate

- Total target revenue from ads, paid subs, and events
- Number of subscribers needed to reach target ad revenue (equals target revenue divided by ((audience * CPM)/1000))
- A table of options for premium content revenue (different prices on the top row ranging from $10 to $250 per month, and audience sizes on the vertical. Boxes should be equal to vertical times horizontal, and anything that is equal to or greater than my target revenue from paid subscriptions should highlight green.)
- A table of options for events hosted (different ticket prices on the top row ranging from $100 to $2500, and audience sizes on the vertical. Boxes should be equal to vertical times horizontal, and anything that is equal to or greater than my target revenue from events should highlight green.)
- It would also be cool if there was a way to incorporate even sponsor revenue. So an event might be free to attend, but have $2500 in sponsor revenue. This section (event revenue) will basically have two types of revenue: Sponsors and ticket sales. And the tool needs a good way to show both.