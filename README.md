# CS370-Reminder-App

The beta version of an Android app that allows users to store reminders. Programmed in Java and utilizing Back4App as the back-end, users can create reminder lists and add/remove reminders.

**Time spent: >24 hours**

## User Stories

- [x] A list consisting of reminders the users want to be aware of. The application must allow users to add reminders to a list, delete reminders from a list, and edit the reminders in the list.
- [x] The application must contain a database (DB) of reminders and corresponding data.
- [x] Users must be able to add reminders to a list by picking them from a hierarchical list, where the first level is the reminder type (e.g., Appointment), and the second level is the name of the actual reminder (e.g., Dentist Appointment).
- [] Users must also be able to specify a reminder by typing its name. In this case, the application must look in its DB for reminders with similar names and ask the user whether that is the item they intended to add. If a match (or nearby match) cannot be found, the application must ask the user to select a reminder type for the reminder, or add a new one, and then save the new reminder, together with its type, in the DB.
- [] The reminders must be saved automatically and immediately after they are modified.
- [x] Users must be able to check off reminders in the list (without deleting them).
- [x] Users must also be able to clear all the check-off marks in the reminder list at once.
- [x] Check-off marks for the reminder list are persistent and must also be saved immediately.
- [] The application must present the reminders grouped by type.
- [x] The application must support multiple reminder lists at a time (e.g., “Weekly”, “Monthly”, “Kid’s Reminders”). Therefore, the application must provide the users with the ability to create, (re)name, select, and delete reminder lists.
- [] The application should have the option to set up reminders with day and time alert. If this option is selected allow option to repeat the behavior.

## Notes
App may require users to enable Internet connection in order to function. 

Credit to group member <a href="https://github.com/yan-ye-0102" target="_blank">Yan</a> for laying out the code foundation for the adapters and RecyclerViews.

Credit to group member <a href="https://github.com/sharadpatel11" target="_blank">Sharad</a> for setting up the Back4App database and implementing log-in functionality. 
