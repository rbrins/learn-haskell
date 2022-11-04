# Starting out with Learn You a Haskell for Great Good
I'm using learnyouahaskell.com as my primary kickoff source of knowledge. 

Going through the tutorial and book put out there feels very much like any time I learn a new language (or at least get familiar with one). 

Some confusing ramblings coming from imperative languages:
* for loops are non-existent 
* since data is immutable `a = 1` and `let a = 1` seem to be the same thing as far as definitions go and I'm not sure when you would want to use one over the other
* using some basic recursion I was able to get to the `' '` character and return something, but then adding this returned something up and continuing to go through the line did not happen in the first few hours of going through the tutorial.

This was fun and an interesting puzzle to get my mind around. I kept trying to get the word counter working at a basic line level. This was met with head pounding around not understanding the recursion. This was where one of my blocks were in the word counter. I was only recursing to the delimiting character, in this case a blank space `' '`. This would only yield one word and I got compile errors for looking for the null value `''`. 

Fortunately, I was enlightened by a video explaining the impure `Maybe` values versus `Just` values (and I might be saying this wrong). I think this is going to be a day 4 implementation, but I'll set the `Char` in the function to a `Maybe Char` and then can recurse until the end of the string (and then later the end of the file).
