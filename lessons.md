I'm still figuring out HTML5 animation, but here's what I wish I'd seen explained:

- each character is just an empty div: <div class="bloom"></div>

- its path is a series of top-left pairs, each representing a change of direction, with the timing expressed as percentages from 0 to 100 (these are percentages of a duration in seconds declared elsewhere)

- the browser calculates the appearance between these changepoints ('tweening' between 'keyframes')

- multiple characters can be following their own paths simultaneously (like wandering rocks)

- every type of browser requires its own acknowledgment for some reason, so each list of direction-changes must be repeated identically for each browser-type

- (maybe this is already fixed???)

- characters are animated using sprite-sheets that are very frustrating but magical when they finally get working

- spritesheet-animation-timings are unintuitive (so far)

