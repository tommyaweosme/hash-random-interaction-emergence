# hash-random-interaction-emergence
hash-random-emergence but cells can interact. Full of fun cellular automata-type rules!

When searching for seeds, try not to use letters. If you find a seed with an offensive string, it becomes practically unshareable.

The notation for rules is t|e where t is the number of states and e is the seed.

Using 32-bit hash is reccomended, all our discoveries work there.
## Cool things to search for
- A state that is a spacefiller but a second state that conquers it.
- Eaters that can take spaceships and destroy them, while going back to their original position and condition after a bit.
- Reflectors or converters that can take spaceships and reflect or convert them.
If you find a rule with eaters and reflectors/converters, you may end up with a turing-complete rule!
## 1-state rules
### 1|1
1|1 is a very simple rule featuring falling sand pixels and replicators.
### 1|2
1|2 is like sand blowing cells northwest with a capability of groups of cells going against the wind and to the southeast, there may be complex structures like puffers in this rule.
### 1|3
1|3 is a rule where every cell goes southeast.
### 1|4
1|4 is a rule where it generates a fractal-like tree-like structure downward and occasionally releases replicators upwards.
### 1|5
1|5 is a boring rule where cells turn into 2x2 groups.
### 1|6, 1|8
These are rules where cells constantly stack on to each other, causing immense lag.
### 1|7
1|7 is a rule where the wind blows east, and a 1|5-like mechanic can be used to temporarily evade the wind as the 2x2 groups decay.
### 1|9
1|9 is an extremely strange and interesting rule where spaceships move north but the same spaceships can be going south, against the windm and have interesting collisions with the other spaceships. This rule very well may be turing-complete.
### 1|10
1|10 is a rule where the wind blows southeast, but a very specific and common structure moves northwest.
## 2-state rules
### 2|1
2|1 is a rule where red goes south, green goes southeast, and the interaction of red and green is very chaotic.
### 2|2
2|2 is 1|2 but green goes against the wind instead, causing chaos as it goes.
### 2|3
2|3 is 2|2 but red is way weaker.
