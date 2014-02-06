# January 30th Meeting
# Part 1

## Attendees:
Mike, Craig and Stefano

Simon, Tom, Kit, John, Lewis and Laura

## Minutes
Started by going over Task List created after last weeks meeting.
* Need to add Plan to Task list and create a Plan for work being done over the timeframe
* Ask Craig about Monthly Spend graphs
* Any UI design ideas/diagrams need to be checked by Stefano

Mike wants documentation to be kept for every team member for hours spent on tasks, and what tasks everyone has been working on each week. Can keep a table adding to it each week - keep note in minutes and keep the document in google docs or github. Can include references to github/google docs. Evidence needs to be shown to group during meeting but does not need to be documented. If there are any problems should be brought to Mike's attention.

Prototype needs to be completed ASAP - once completed should be easier to adapt and get a better understanding of requirements. 
2 Requirement "categories"
* Specific to HW requirements
* "Exciting" interaction - something simply but different/illuminating
Classes of user needed in Requirements - i.e. RES, Management
Should it be externally facing - for industrialts looking for experts in particular areas within Heriot Watt
Should Journals be included? 
 
Classes of information
* Temporal
* Taxonomy/classification
* What is in the topic models
* Connectivity - Projects -> topics/investigators/schools
 
Need to decide on a method of determining the success/failure of the projects
- Requirements and User Profiles need fleshing out

*Remember to include that info should be visible at a glance, no more than 2/3 drill downs*

Stefano mentioned that he might give us something to do with 7 HCI requirments/best practices

Should try to get data to display in more of a tree structure - currently it is a circular structure

Requirements that should be included in documentation but are secondary requirements which if we have time would be good to look into. 
* Bookmarking 
* Creating Reports (could be simple HTML)

Need to figure out who will be in charge of the Calculations that should be carried out on the data - i.e. to get monthly spend - which Task should they come under? somewhere between UI and PHP

Need to query the database to see what data we have for Heriot Watt, and to show how HW distributes across topics
 - query DB for HW related topics
 - total up money per topic
 - generate a rank-ordered list of topics (by amount of money and weighting to topic)
 - select top 80 ish topics 
 - come up with a list of:
  - What the topics are
  - Money per Topic
  - List of Projects
   - Should find monthly spend for each topic?
 - Need to sanity check the data to ensure topics returned match projects they are linked to
 
### Next Meeting
10.15 Tuesday 4th - Group Meeting 
11.15 Friday 7th - Mike's office

# Part 2 - without mike. Assigned tasks for the next week

* **Laura** SQL queries for sanity checking

* **Tom/Lewis** look at how Stefano has implemented the hex grid stuff

* **Project plan**: Gantt chart?

* **Kit/John** look at what sort of data we're going to want out of the database.

* **Simon** - look at totalling grants / per topic : pre-compute or dynamic checking

* **Use Cases** - anyone who has free time!
