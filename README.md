# ae-textanimation
Expression to animate directly between a set of words/phrases in After Effects

This is a modified version of the script by aespyrcranberry posted on reddit : https://www.reddit.com/r/AfterEffects/comments/cz653u/comment/eywc9ny/

# Usage
- The expression needs to be added to the "Source Text" of the desired layer.
- Variables at the top of the script can be adjusted


# The original script
- Totally contained within a single expression
- Animates from one word to another

# Modifications made
- Animate between multiple words (via an array in the code)
- Set "hold time" adjustment for each word in the array individually
- Loop back to the first word in the array at the end
- - When going from short -> longer word, add to the right end of the word, and for vice versa add to the left end
