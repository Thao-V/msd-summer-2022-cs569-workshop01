# CS569 Workshop 01
# Create an app to show/hide a list of students
## Data Structure
* Each student has a first name, last name and phone number.
## App Structure
* App Component: is a root component which shows the List component.
* List Component: displays a list of student components. This component has an input which is a list of students. This list of students will be provided by the App component.
* Student Component: shows the information of a student and index which are input from the List Component.
* Color directive: changes the background color of the student component based on the index of this student. If this index is even, the color is yellow. If this index is odd, the color is green.
* Student component has an input element and button 'Update'. When the button is clicked the text value of this input element will replace the name of this student. The log including index, old name and new name will be send from this component to the List Component.
* Provide a button to show or hide the list. When the list is hidden, the text "Have a happy day" will be displayed. Otherwise, the text will be hidden.
# You need to submit this workshop before 10 PM
# I will show you the solution on Monday (05/30/2022) from 10 AM - 11 AM
