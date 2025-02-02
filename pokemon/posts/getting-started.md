--- 
title: "Getting Started"
author: "Vishesh Gupta"
tags: ["pokemon","intro"]
summary: "About some of the exploration that seems intersting in the world of pokemon!"
created: "2015-03-28 13:35:30"
--- 

## Getting Started {.post-title}

Pokemon might seem like a strange choice for a "dataset" - after all, this is a 
game meant to be played primarly by 7 year old boys, and the sum total of the 
strategy of that age group is just to level up their charizard until it's 
OP relative to whatever is being fought. 

However, if you consider what a Pokemon is, it's basically an abbreviated version
of, say, an employee of a company. Except your company is maxed at 6 people and 
instead of producing business, you battle. The cool thing is that the mechanics
of pokemon are all 100% defined by the game code, unlike in the real world, 
where human beings have lots and lots ... and lots of options of what they are 
doing in the context of a company.

Why is this interesting? There are two primary motivating questions here - as 
always, there's the issue of categorization. How do we determine whether 
two pokemon are similar? There's the inherent information of a pokemon - base stats,
typing, move pool; however, life is way more complicated than that, since a 
trainer can choose to customize their pokemon to their liking, completely changing
how effective it is. 

The second question is of course, what's the most effective type/pokemon/movepool/etc
with which to win a battle? 

And the third, and most interesting problem here data wise is to set up a 
linked-data problem - normally in data sets we have well-ordered axes (i.e, numbers).
But what happens when an attribute/feature is something like a type? (A good real world
example to consider is amino acids in proteins). There is some understanding of what 
it means for two types to be similar, but it's not well ordered; in fact, it takes 
17 dimensions to describe the relationship. We can, however, take the distance bewteen
two types in this 17-space and see where that leads us. Another question is whether
applying a fish eye lens effect through clustering and then using the cluster distances
rather than the raw distances leads to better final results, and if so, why?

