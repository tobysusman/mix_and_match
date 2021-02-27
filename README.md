# mix_and_match
This is inspired by an episode of Only Connect, the final round of each episode is the "Missing Vowels Round", this round is rather self explanatory as a word without vowels is displayed on the screen.  Often to make it more interesting, the categories for these may involve "portmanteau"-ing two different categories.  For instance, in the most recent episode, the category was "Singers and English Footballers" and one example was S H K R H M S T R L N G, Shakira & Raheem Stirling (ShakiRaheem Sterling).

This contains a Jupyter Notebook, you will want to create a subfolder in the folder containing the notebook called "Entry" and in this folder should be an Excel document called "Thing.xlsx", if you have this set up, then you can add sheets with the lists of all the data you are looking to import and use the names of those sheets as arguments in the function.  Two files will then be produced, one going each direction for looking for similar names.

When you run the mixed_up_stuff function, the digit refers to the maximum number of overlap to check for.  So Shakira and Raheem Sterling has an overlap of 2 (RA), but to stop the code from looping forever a maximum value is required.  Output will be in two Excel files which will have all the overlap.

If you have any good suggestions or ways to improve then let me know!
