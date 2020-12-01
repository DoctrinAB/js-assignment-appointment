# Appointment web application. 

Doctrin needs a way to let it's customers patients book their doctors appointments online, but to take discussions further we need a POC. 
Please help us create a simple appointment booking application that can ve used as basis for a more deeper investigation. If you have limited time, do what would be your first iteration on the problem.

## These are the requirements for the booking application:

- The application should consist of two views, one view for booking time slots and one view for listing the booked appointments. The list view is for the caregivers so all booked appointments should be listed. 

- The application should have 2 API endpoints, one endpoint for saving appointments and one endpoint for listing appointments.


### Booking view:

- The patient should be able to input his/her social security number.

- The patient should be able to select a DateTime and book an hour-long appointment.

- The patient should be able to submit the appointment form.

- The application should give the patient a notification if the time slot could be booked or not, after submit. A time slot is bookable if the timeslot has not been booked by someone else. 

### List view:

- The application should show a list of booked appointments. This view is for the caregivers so all the booked appointments should be listed.


## API

- One endpoint for posting appointments, should respond with appropriate status code and content. 

- One endpoint for listing all booked appointments. 

## Test

- Please provide some form of testing. At Doctrin we use Jest, Cypress and Mocha. If you feel you have the time to write an End to End test it would be awesome. 

## Technologies:

- MongoDB
- React
- Node.js

