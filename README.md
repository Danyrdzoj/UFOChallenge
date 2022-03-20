# UFOChallenge
Sightings with JavaScript

## Project Overview
The goal of this project was to learn how to take data stored as a JavaScript array or list and organize it into a table that will visually adjust as "events" change (i.e. filtering). We use Javascript functions to loop through the data to build the table and create a customized dashboard in order to react when an element is changed. Filters with event listeners are included in the customizations, which will record information when an element changes and create an interactive webpage.Filters can be used in a variety of ways. We went over how to display default data in the table, listen for a button click, and trigger the table to update based on the user's input using a select criteria in this exercise. Finally, we use HTML, Bootstrap, and CSS to read the Javascript code and create a user-friendly webpage with filters, images, and a topic synopsis.

## Topic
Are we the only ones in this universe? For centuries, many people have been obsessed with UFO sightings. Is it a genuine government conspiracy or a hoax? We've been tasked with assisting in creating a website where others can access information about reported sightings and see for themselves. This website should include the following:

* A topic description or summary * A table displaying all of the information from the data source * Search filters allowing visitors to update the table based on the search criteria they enter
* 
![Image](Modulo%2011_4.png?raw=true)


Here we can show how to select, drop and display information
You will notice that a **"Filter Search"** section has been added.
![Image](Modulo%2011_6.png?raw=true)

You can filter by one or all of the search criteria shown. For example, if you search by **"City"**, you will see that the table updated to show the reported sightings that was recorded for that specific city.

![Image](Modulo%2011_3.png?raw=true)

If you add a shape, the table will update filtering further to only display the information containing that shape.


Or if you delete your previous entries and enter **"State"** and **"Shape"**, the table will update using your new criteria.
![Image](Modulo%2011_5.png?raw=true)


## Summary
Unfortunately, the page has a number of flaws. They are as follows:

* The search box is "case-sensitive." The table will not update if you do not enter exactly how the data is stored, and partial entries are not permitted. This is a problem because it does not intuitively tell the user how to enter the information other than the "default" example shown.

* There is no button to click, no wording, and no action to inform the user that the table will update after you press "enter."

* Because it is not linked to a "live" source, the data is limited and out of date.

**Further Development Suggestions:**

It can greatly improve the user experience with the following enhancements.

* Include extra customizations, such as click-buttons, dropdown lists, and/or auto-fill, to help "guide" the user and make the page more interactive.

* Add functionality to pull data from a live source that includes current and archived data from all over the world, not just the United States.

* Include a "Latest News" section that will highlight the most recent reported sighting.
