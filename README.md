# ODKLink
Example of a Shiny Script To Link ODK Form Directly To A Shiny Front End App

Put the app.R and functions.R files within the same folder
Store the ODK xlsx file in that same folder

Modify the "user inputs" at the top of app.R

Able to link to Ona or Kobo.

Requires numeric ID for project. In ona you can see this from the URL of the project, but not easy to find in Kobo. Can use the function available_data to see numeric IDs for each form associated with your account.

available_data(paste(username,password,sep=":"),api = servername)

The idea is that this will be modified for users needs rather than taken as is - but can easily build from this skeleton to add plots/customised outputs tied to the specific project.
