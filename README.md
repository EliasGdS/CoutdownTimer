# Coutdown Timer

Countdown timer done in HTML5, CSS and Javascript.

CodePen: https://codepen.io/eliasgds/pen/xxZoqVW

## Preview
<p align="center">
  <img src="https://user-images.githubusercontent.com/67754744/88970968-9deb0880-d289-11ea-9d43-91cca7bd5bd5.png">
</p> 
  
## Features

- [x] User can see an event input box containing an event name field, an date field, an optional time, and a 'Start' button.
- [x] User can define the event by entering its name, the date it is scheduled to take place, and an optional time of the event. If the time is omitted it is assumed to be at Midnight on the event date in the local time zone.
- [x] User can see a warning message if the event name is blank.
- [x] User can see a warning message if the event date or time are incorrectly entered.
- [x] User can see a warning message if the time until the event data and time that has been entered would overflow the precision of the countdown timer.
- [x] User can click on the 'Start' button to see the countdown timer start displaying the days, hours, minutes, and seconds until the event takes place.
- [x] User can see the elements in the countdown timer automatically decrement. For example, when the remaining seconds count reaches 0 the remaining minutes count will decrement by 1 and the seconds will start to countdown from 59. This progression must take place from seconds all the way up to the remaining days position in countdown display.

## Bonus features

- [x] User can save the event so that it persists across sessions
- [x] User can see an alert when the event is reached
- [x] User can specify more than one event.
- [x] User can see a countdown timers for each event that has been defined.
