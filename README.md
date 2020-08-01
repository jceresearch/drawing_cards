# xls_drawing_cards
Drawing cards game for 5 year old children.
The idea is that you take turns to draw and the other guesses (or you could do in pairs or with a judge... i.e. Mom).
You can add rules such as number of clues/retries. 
The grown up should draw the advanced word, for normal point. 
If the child draws the advanced word then he/she gets extra points.
Some ideas:
- Make the child keep the tally of point to make him/her summ and track who is winning
- You can get fonts from the internet to be more alligned to what they learn at school
- As it was a bit difficult to read sometimes, I switched to upper case. But I reckon I should stick to sentence case...
- You can ask the child to write the word he/she guesses for extra points.
- You can use whiteboard or one of these show-me pads when on the road


How the sheet works:
Each word has a random number generated every time.
The columns to the right selects words from the main list of words based on its points (1-4) using the new FILTER() function. 
(I could have moved these columns to a separate sheet, but it is useful to go to and fro quickly to check difficulty)
Then orders by a random number using the SORT() function
The deck sheet will pick the first rows onwards, keep copying down to get more rows.
Needs Excel O365 for the FILTER() function to work

Some future ideas
At the moment it picks fully randomly from the big set of words, but there is no reason why you couldnt do thematic.
So some cards could be for outdoors, house, things, animals etc.

