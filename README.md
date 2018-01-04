# busDriverV2

## Description
Version 1 utilizes Twilio as the primary method for creating and updating in the db. However, concerns for cost (~ $0.10/message) became an issue when estimating the cost of a trip at ~ $4.00. We have hundres of trips per year, thus the need for an alternative. Additionally, many felt placing the responsibility on the student was the less than logical choice; the new version tasks the driver to add students as they get on the bus. The student-body can be narrowed down to specific teams or grade-levels.

## Usage
Using Flask, we've created a simple login for teachers that only takes a second. From there, teachers create a trip by identifying their bus (from a list) and then adding the destination. Finally, teachers can quickly tap to add their students. They can query the entire student-body with jquery handling the input and limiting the responses to records with the entered characters. Additionally, elements of the db contain different clubs/teams/grade-levels in the school so teachers can filter the list themselves.
