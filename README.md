# Trailhead-Leaderboard
As part of the Salesforce Summer of Trailhead event we built a trailhead leaderboard that ran in a developer org.  Feel free to use this at your event, or any event for that matter where a point tracking leaderboard is used.  

This has been uploaded as an unmanaged package here: https://login.salesforce.com/packaging/installPackage.apexp?p0=04t370000001V3r


Summary:

The contact object has been used to store the participants in the event.  We've added custom fields to track points at check in, points total, and points earned "today".  We monitored the participants developer trailhead profile and manually updated the Total Points field which updated the visualforce page.  

The field "SF Dev User Id" was used to store the user id of thier developer profile (in the url of their trailhead profile) then the formula field "Trailhead URL" will populate a link for the user. Make sure their trailhead profile is public (they have to edit).

A recordtype and custom list view are included for easy edit.




Other items that are important:

-A static resource contains the countdown js file.

-Trailhead Leaderboard Settings - This is a custom setting letting you change the Header Message, Finish Message, and Target Time of the countdown without having to edit the VF page.

-You can access the Visualforce page for results but our group also did a public facing Site so we could share externally.
