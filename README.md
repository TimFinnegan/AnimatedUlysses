# AnimatedUlysses
*HTML5 animations of Joyce's Ulysses*

This project is an unexpected spinoff of a collection of platform-ideas for simulating Ulysses: http://simulatingulysses.blogspot.com/2016/04/sidescroller.html

HTML5 has some commands that allow animated figures to move around background graphics, so it seems pretty simple to animate the basic paths of the main figures in Ulysses. Without using any javascript code, we should be able to evolve shared and/or customised animated illustrations.

I've created very rough firstdrafts of all pages, with individual lists of challenges to be handled. Volunteers are welcome, especially if you want to learn animation. (Because it's nonverbal, pages are needed to map transitions between chapters, with speculative routes)

The maps are mostly modern Google, and need to be traced and restyled more like Donkey Kong. I don't want any words visible.  Mentioned landmarks should be substituted with emoji. (Good contemporary photos of places may be collaged in?) http://gadgets.gunaxin.com/alternate-donkey-kong-worlds/149408

Today's priorities: how many pixels equal six feet at each scale? stick in a simple bloom going straight from start to end of his path on each map. replace 'shelter.gif's. stickfigures for stephen et al

- The backgrounds are mostly maps, but for interiors they'll try to offer accurate proportions, hopefully all about 600px wide. (Is this too narrow?) map heights vary wildly and are sometimes awkward to scroll for tracking characters.

- Characters and objects believed to be within the background can be included, even if the text hasn't mentioned them yet.

- Character-animation should eventually be via 'sprite sheets'. (Bloom looks a lot like Mario, conveniently.) Early drafts may cheat and slide around still figures. There's a way to reverse direction within a single spritesheet that I have partly figured out.

- Figure one html page per 'scene': transitions between indoors and outdoors require moving to a new page. Each page needs 'play/pause?/start-over' buttons that start the (non-interactive) 'movie'. Add pages for chapter transitions.

- I'm expecting to figure out how to assign multiple characters multiple overlapping starting and finishing places and times. (If there are technical limits, we'll have to retreat to next-best workarounds.) 'Animation-delay' sets a starting time and 'animation-duration' calculates an ending time...? But every spritesheet has to be treated as completely separate/independent? And kept invisible before and after its bit?

- we can use percents to break paths into subsegments-- very delicate and expressive!

- (The 'alternate' modifier is useless because whenever our characters reverse direction they have to switch to a different spritesheet... or do we?)

- So each scene has to be broken down into a set of 'independent' subpaths for each character, which then run 'simultaneously'??

- Emojis may supplement character-animations, eg in the super-complex ch10.

- Boring chapters like ch3 and ch9 will need creative tricks. I'm thinking of embedding characters' thoughts as emoji pre-fixed to the background maps near where they'll be thought.

- Maybe speeches and thoughts can be 'summarised' in emoji? (requiring lots of new animations) we needn't try to make them full translations, just suggestive hits wherever possible


*chapters and scenes:*

1: tower cross section and cliff path

transition

2: school cross-section

transition

3: strand path? sidescroller???

transition?

4: eccles cutaway plus walk to butcher

transition

5: map-path plus church, swenys??

transition

6: very tall map-path w/tiny carriage, cemetery choreography??

transition

7: newspaper cutaway cross section

8: map-path, byrne's, map-path

9: inactive library, comings and goings

transition

10: giant simultaneous map?

11: ormond interior

transition

12: kiernan's interior

transition

13: girls on beach

transition

14: hospital cutaway

transition

15: map-path then bella's

16: map-path then shelter

17: map-path then eccles again

18: molly's day???

the jamesjoyce.slack is available for discussions





