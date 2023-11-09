## Information
Written by: Brandon Welsh

Start date: 11/5/2023 9:00am

Due date: 11/9/2023 11:59pm

## Program Goals
To create an ordering system for a food truck menu.

The system should have a dictionary containing all menu items and prices.
User is able to select from a menu, select the item they want, select the amount they wish to buy, and repeat the process until they are satisfied and ready to check out. Then, the program displays all the items in their "cart" in a properly formatted recipt-style table and calculates the total cost of all the items.

I also took some creative liberties with the formatting (specifically the print(dashes) trick) just to make my program nice and pretty.

## Resources Utilized
This section is dedicated to keep track of what I used to help complete this program (because I certainly am NOT at the skill level to be able to pull all this out of my butt yet.)

50% class notes

30% AI powered by OpenAI's GPT 3.5

10% Google (which mostly led me to stackoverflow, which I found to be remarkably unhelpful)

10% asking my classmates questions in Slack

My thought process for completing this project was a mixture of looking at the code that was already given in menu.py and following the online challenge instructions and the comments to try and fill in the rest step by step. If there was something I didn't know how to do (for instance, storing the dictionary items as variables, I was overcomplicating it way too much when the solution was quite obvious), I first checked class notes to see if there were any instances where we already did a similar example in-class (this was often the case). If I was still having trouble, I then turned to an AI (Discord's Clyde) and queried it until it gave me a code that was close to what I wanted, and then I copied it into my program and made changes until it worked. Rarely would I check stackoverflow because I find stackoverflow a mess full of really high level complex codes that's nowhere near my level. And on one occasion, I asked a community question to my class and Ajay Kumar answered with a line of code that was close enough to what I needed that I was able to figure it out.

Oh I also used a fair bit of caffeine but that's pretty normal for me.

## Bugs
There is one bug with the program that I can't figure out despite a few attempts that were getting far more complex than I would've liked. If the user orders an item that costs more than $9.99, it causes a very slight graphical glitch in the recipt. I couldn't use len() like I did with the ordered item because the item was a string and this is a float and python was freaking out. There's only like two items on the whole menu where this could happen so I really don't care that much. Other than that, everything works as expected.

## Update Log
11/5/2023: Began initial work on project, which included creating github repository. Order system is complete and functional. Order Recipt is yet to be attempted, but I can't imagine it will take very long (my desk is made of wood and I am knocking)

11/6/2023: Went a little ham with the print(dashes) thing just to make it all nice and pretty. Made some progress on order recipt.

11/7/2023: Order recipt is done. The program is done as far as I can tell. May do some stress testing tomorrow to try to break it, and if all goes well, I can submit this as-is for full points.

11/8/2023: Did some formatting updates, proofread my comments, updated the README, and got the project ready to submit.

