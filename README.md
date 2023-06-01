# `Vehicle Scenario`

## GIVEN ASSIGNMENT DETAILS

Instructions:

Build an application using React.js.
The application should be able to create, display, update, delete Scenario and Vehicle, a
scenario can have multiple vehicles, and vehicles should be able move when user click a button
based on the scenario and vehicles parameters.

The scenario should have following fields:
- Scenario id
- Scenario name
- Time

 The Vehicle should have following fields:
- Vehicle id
- Vehicle name
- Initial Position X
- Initial Position Y
- Speed
- Direction (can have only Towards, Backwards, Upwards and Downwards).

For storing data use json-server.

You have to create sidebar like displayed in the below images.

Inside Home page user can be able to select the scenario whichever scenarios he has created and start simulation, when user click start simulation vehicles should start moving based on the direction and speed, till the scenario time, if the vehicles is going outside the container then vehicles should hide.

While adding the Vehicle do proper validation like user should not be able to add the positions
greater than the Home pages graph container size.

After Completion of this project you have to deploy the application to any platform (such as
vercel, netlify etc) and upload code to your github accounts public repository, and write a
proper README.MD file explaining how to install your project and how to run your application
along with the json-server and brief explanation about the project.

## About the project

In this project directory, there is an application made with ReactJS. Users can add scenarios and vehicles, and each scenario can have multiple vehicles. Users can read, create, update, and delete scenarios and vehicles. When a scenario is deleted, all vehicles under it will also be deleted.

The application can create, display, update, and delete scenarios and vehicles. A scenario can have multiple vehicles, and vehicles will move when the user clicks a button based on the scenario and vehicle parameters.

On the Home page, users can select the scenarios they have created and start the simulation. When the user clicks the play button, vehicles starts moving based on the direction and speed until the scenario time is over.

The scenario have following fields:
- Scenario id
- Scenario name
- Time

The Vehicle have following fields:
- Vehicle id
- Vehicle name
- Initial Position X
- Initial Position Y
- Speed 
- Direction (can have only Towards, Backwards, Upwards and Downwards).

json-server is used for storing data use.

For animation I have used Framer motion library.

## Live project link

https://app.netlify.com/teams/satyaharika1235/overview

## `Tools Used`
Visual Studio

### FRONTEND
- React
- Framer motion
### BACKEND
- npm install
- json server
