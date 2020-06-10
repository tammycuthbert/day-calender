# 05 Third-Party APIs: Work Day Scheduler

This is a simple calander application allows the user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

This application uses [Moment.js](https://momentjs.com/) library to work with date and time.

Here is a link to the live application https://tammycuthbert.github.io/day-calender/

## User Story

```
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```

The following animation demonstrates the application functionality:

![dayCalander](https://user-images.githubusercontent.com/63136631/84235740-fc7edc00-aabb-11ea-8f3c-34cbcc6e6569.gif)

