# Course-registration
## About
This project demonstrates the process of the student course registration form. It is built using Bonita 7.10.1

This example involves several steps:
- Define the data model using Business Data Management
- Define the organization
- Create the BPMN diagram
- assign the actors to the task
- Develop the forms to the user task
- Initiate the task by a simple form
- Develop the operations needed to perform the process

## Course Registration steps
- Students fills the online form
- Application will be received by admission unit
- Admission unit checks the completeness of the form
- If there is any incompleteness, requests the students to update with missing details
- Check the validation of the form according to the previous GPA
- Head of the department passes the acceptance of the registration
- Deputy Registrars allow the permission to the follawance of the course
- Admission unit send the letter of offer to the student via mail

## Screenshots
- Businees object created for the process
![ScreenShot](https://github.com/Mursina/course-registration/blob/master/screenshots/Business%20Data%20Model.png)

- Actors defined in the process
![ScreenShot](https://github.com/Mursina/course-registration/blob/master/screenshots/Actors.png)

- User credential to the portal
![ScreenShot](https://github.com/Mursina/course-registration/blob/master/screenshots/Members.png)

- BPMN diagram for the project
![ScreenShot](https://github.com/Mursina/course-registration/blob/master/screenshots/BPMN%20diagram%201.png)
![ScreenShot](https://github.com/Mursina/course-registration/blob/master/screenshots/BPMN%20diagram%202.png)

- Contracts defined for the application form
![ScreenShot](https://github.com/Mursina/course-registration/blob/master/screenshots/contracts.png)

- UI for application
![ScreenShot](https://github.com/Mursina/course-registration/blob/master/screenshots/forms.png)
![ScreenShot](https://github.com/Mursina/course-registration/blob/master/screenshots/Updated%20form(with%20read%20only%20option).png)

- Current validation status(There are no errors in the diagram. The status only says the information due to the use default form design in Bonitasoft)
![ScreenShot](https://github.com/Mursina/course-registration/blob/master/screenshots/Validation%20status%20(5.4.2020).png)
