# J124 Final Project: What do Netflix Weekly Top 10 Say About Us?

## The Story

What were people watching during the pandemic? How did it differ from what we watched before and what we're watching now?

What we watch on Netflix defines in many ways our culture. It provides a window into the state of our soecity, allows us to understand how the future generations are being shaped and maybe even holds up a mirror into our own desires. The world needs all three now more than ever. After a world-wide pandemic that radically changed all of our lives, and especially now that we’re starting to return to our old normal, understanding our viewing habits may provide us a window into how to heal. For instance, the data suggests we got significantly more attached to TV shows than movies, as popular titles stay on the Top 10 list for more than double the time that movies do. Did that come from a need for community? That seeing the same faces for an extended period of time made us feel less lonely in a time of isolation? Will this trend continue even when social interactions are permitted (and encouraged)? This data is a stepping stone into discovering the attitudes and trends of our current society.

## Sources

1. Ben Proctor, Director of Consumer Insights at Netflix. Contact info: https://www.linkedin.com/in/ben-proctor-5a89601b/ This team’s knowledge undoubtedly is more vast than what I was able to find for free online, and so I think interviewing him would grant some insight into what these trends could actually mean.
2. Pamela Liendo, Content Acquisition at Netflix. Contact info: pliendo@netflix.com. I’d be very interested in knowing more about what Netflix’s acquisition strategy and trends is currently, in order to understand what they foresee people’s entertainment needs will be.

https://techjury.net/blog/netflix-statistics/#gref This data would surely be useful to weave into my report, since it gives data of what kinds of users use Netflix and the content they consume.

https://www.statista.com/statistics/1275623/distribution-netflix-budget-worldwide-program-type/ This source gives insight into what Netflix has spent is spending its budget on, which, again, would give an indication of what their analysis says people will consume.


## Data Analysis 

**Question 1: What was the genre that spent most days on Netflix’s USA Top 10 TV and Movies list?**

1. Create a pivot table and place “Genre” both as a row and as a value. In the value section check “Summarize by” COUNTA.
<img width="690" alt="Screen Shot 2022-08-09 at 11 13 43 PM" src="https://user-images.githubusercontent.com/110010308/183828453-b14f0b55-4e3d-4653-9827-244de258a710.png">
2. Copy the table and paste into a new sheet. Paste Special --> Values Only. Then, rearrange Column B Z-->A (largest to smallest)
<img width="233" alt="Screen Shot 2022-08-09 at 11 14 46 PM" src="https://user-images.githubusercontent.com/110010308/183828613-09e310ca-b821-406f-ac06-0c00aec1324d.png">

The most popular genre overall is Drama. 


**Question 2: What is the genre with the highest viewership score, overall?**

1. Create a pivot table with “Genre” as a row and “Viewership score” as a value. 
<img width="625" alt="Screen Shot 2022-08-09 at 11 15 58 PM" src="https://user-images.githubusercontent.com/110010308/183828794-5e30ef6b-cd75-42c0-a661-f96eba174a97.png">
2. Copy and Paste Special → Values only into a new sheet and rearrange column B from Z → A again.
<img width="241" alt="Screen Shot 2022-08-09 at 11 16 20 PM" src="https://user-images.githubusercontent.com/110010308/183828864-e86fde3d-aef8-411b-98cb-70a5d6369401.png">
The genre with the highest viewership score is Kids, and by a lot. 


**Question 3: What percentage of movies and TV shows in the Top 10 are Netflix Exclusives?**

1. Create a pivot table with “Titles” as a row and “Netflix Exclusive” as a Value. From doing this, we know that there are 635 titles
<img width="470" alt="Screen Shot 2022-08-09 at 11 17 14 PM" src="https://user-images.githubusercontent.com/110010308/183829020-0647b2b9-82a6-410f-9628-a44c4746880b.png">
2. Then, place “Netflix Exclusive” as a Filter, and filter out the blanks (blanks mean it’s not an exclusive). This will leave all the values that are Netflix Exclusives.
<img width="463" alt="Screen Shot 2022-08-09 at 11 17 54 PM" src="https://user-images.githubusercontent.com/110010308/183829108-d5cf3abd-0880-44ef-9588-9c4a515ea960.png">
3. Divide 404 by 635 and multiply by 100.

63.6% of titles on the Top 10 lists are Netflix Exclusives.


**Question 4: What are the five TV shows that spent most days on the Top 10? And movies?**

1. Create a pivot table placing “Title” as a row, “Days in Top 10” as a Value and filter by TV shows only. Make sure to summarize by COUNT for Values, because it will automatically appear as SUM, but since the values on the spreadsheet record the days in top 10 for every day that passes, it will add up to exorbitant amounts.
<img width="619" alt="Screen Shot 2022-08-09 at 11 18 43 PM" src="https://user-images.githubusercontent.com/110010308/183829263-6b31b68f-2f04-454c-ac6d-0f122d19854f.png">
2. Copy and Paste Special → Values Only into a new sheet and rearrange column B from Z → A again
<img width="442" alt="Screen Shot 2022-08-09 at 11 19 03 PM" src="https://user-images.githubusercontent.com/110010308/183829319-85f401a7-b1ef-4cd8-8506-dd1c853dcf3b.png">

Do the same for the top 5 movies.

<img width="476" alt="Screen Shot 2022-08-09 at 11 19 41 PM" src="https://user-images.githubusercontent.com/110010308/183829421-165ebe03-086f-4fa5-807f-eccaa49de4be.png">

**Question 5: What are the most popular titles in each genre?**

1. Create a pivot table using “Titles” as a row, “Days in Top 10” as a value and “Genre” as a filter, and filter per each genre. The screenshot below is an example of the Action genre. “Money Heist” is the most popular title in this genre.
2. <img width="627" alt="Screen Shot 2022-08-09 at 11 20 12 PM" src="https://user-images.githubusercontent.com/110010308/183829498-1d0ab131-9da9-4ea0-9d99-e3c8ef541899.png">

Action: Money Heist
Comedy: Space Force
Crime: The Serpent
Documentary: Jeffrey Epstein: Filthy Rich
Drama: Ozark
Family: Despicable Me 2
Fantasy: The Witcher
Horror: Midnight Mass
Kids: Cocomelon
Reality: Too Hot To Handle
Romance: Sweet Magnolias

## Data Visualization

<img width="652" alt="Screen Shot 2022-08-09 at 11 26 17 PM" src="https://user-images.githubusercontent.com/110010308/183830443-02dfa5aa-fa4a-4460-af5c-1c79fd9e3782.png">

<img width="642" alt="Screen Shot 2022-08-09 at 11 26 30 PM" src="https://user-images.githubusercontent.com/110010308/183830471-af71d3e1-895a-4a4d-97fd-ed0566abf426.png">

<img width="643" alt="Screen Shot 2022-08-09 at 11 26 44 PM" src="https://user-images.githubusercontent.com/110010308/183830507-4484d668-46ac-49b8-bc61-3f29d06c4a07.png">
