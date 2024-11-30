# ae-textanimation
After Effects Expression to animate directly between a set of words/phrases.

Similar to the "decode" text effect.

This is a modified version of the script by *aespyrcranberry* posted on reddit : https://www.reddit.com/r/AfterEffects/comments/cz653u/comment/eywc9ny/

[DEMO VIDEO](https://www.reddit.com/r/AfterEffects/comments/1h2oa1z/100_expression_based_textanimation_needed_to/)

# Usage
- Copy the script from the 'ae-textanimation-aecran' file in this repository
- The expression needs to be added to the "Source Text" of the desired layer (via "Edit Expression" in the right-click menu).
- Variables at the top of the script can be adjusted

# Features of the original script
- Totally contained within a single expression
- Animates from one word to another
- Choose your "random characters" set (eg. all caps, all lowercase, with/without numbers, etc)
- Adjustments for per-character animation time, as well as delay for beginning the animation for each sequential character

# Features added to this script
- Animate between multiple words (via an array in the code)
- Set "hold time" adjustment for each word individually within the array 
- Loop back to the first word when the script reaches the end in the array (good for looping video)
- When going from short -> longer word, add to the right end of the word, and for vice versa add to the left end

# BUGS / Please help...
- When the loop reaches the end of the array, it seems to repeat the last 2 words?
- Longer text seems to crash my AE. Not sure if that's just AE being AE, or because there's something wrong with the script
- - This is a very amateur effort by me, so I'm sure there's more!
