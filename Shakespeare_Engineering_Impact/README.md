## Shakespeare engineering impact

As it turns out you aren't going to make much of an impact writing the [shakespeare language](http://shakespearelang.sourceforge.net/report/shakespeare/shakespeare.html).


## How do I run this thing?

The shakespeare language is translated from SPL to C. You can download the translator from [here](http://shakespearelang.sourceforge.net).
I had a touch of trouble getting the makefile to run. I had to install flex via brew and give an explict path to link to flex.
Here's a gist of my updated [makefile](https://gist.github.com/mjhenkes/57c2f2ee793714a4f02c#file-makefile-L45-L46).


## What does this amazing fusion of Elizabethan art and "modern" computer science do?

Not much. Orignally I was going print out "Engineering Impact" but as it turns out it's going to be tough to do that in 32 lines.
Shakespeare is a bit verbose. To print out characters you need to ask the "actor" to speak when they are the ascii value of the character you need.
The actors are assigned values based on sentances with adjectives multiplying the noun by 2.....

I'm going to stop trying to explain this nonsense...

I settled on printing out '12481632' in the spirit of 2^5th and I managed to get that down to 32 lines.
I could optimize further and make the program smaller, but I wanted to have 3 actors(variables) and a dialog between them.

You're welcome world. :)
