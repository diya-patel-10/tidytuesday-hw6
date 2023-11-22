# tidytuesday-hw6

Data from Friends dataset

![](My%20TidyTuesday%20Plot.png)

This visualization takes data from a TidyTuesday challenge on the television sitcom, *Friends*. The data set contains 12,606 observations and contains information about the season, episode, scene, and emotions felt by a character during that scene. This visualization explores how the emotions expressed by the *Friends* characters vary by season. I used a tile plot to visualize these relationships. Notable trends depicted from this visualization are as follows:

-   Feelings of power remain relatively stable in seasons 1-3 but sharply increase in season 4.

-   The levels of joy experienced by the characters remain relatively high throughout the seasons and seem to increase slightly in the later seasons.

-   Neutrality levels starkly decrease as the seasons go on.

-   Levels of sadness remain equally prevalent across all seasons at relatively low rates.

-   As the seasons progress, the characters feel slightly more scare.

There are a few features of this visualization that go beyond what was covered in class. First, it utilizes the geom_tile(), a method to visualize two categorical variables (season and emotion) and one numerical variable (count). Additionally, I flipped the color gradient from the default as I feel the visualization reads more naturally when darker colors represent higher counts. Third, I re-leveled the y-axis variables such that from top to bottom they form a gradient of more positive emotions to more negative emotions. Overall, this visualization employs techniques to visualize changes in frequencies of certain emotions in the *Friends* television show over multiple seasons.
