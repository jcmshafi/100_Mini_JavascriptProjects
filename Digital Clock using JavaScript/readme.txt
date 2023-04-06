
Building a Digital Clock using JavaScript

Instructions:

1. Create an HTML file with a <div> element that will display the clock.

2. Add a <script> element to the HTML file and write your JavaScript code inside it.

3. Create a function that will update the clock every second using the setInterval() method. 
This function should:

a. Get the current time using the Date() object.
b. Format the time into hours, minutes, and seconds using string manipulation.
c. Display the formatted time in the <div> element.
Call the function once to initialize the clock.



Explanation:

We first create an HTML file with a div element that will display the time and date.

We create all JavaScript functionality in script file.

We create two function called "updateTime()" and "updateDate()" that will update date the time every second using the setInterval() method.

We get the current time using the Date() object.
We format the time into hours, minutes, and seconds using string manipulation.
We display the formatted time in the div element.
We call the function once to initialize the clock.
We use setInterval() to call the updateTime() function every second, so the clock is always up to date.

finally we create css file and link in HTML file and add background image url make it colorful