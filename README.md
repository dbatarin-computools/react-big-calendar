# react-big-calendar-dbc (fork of react-big-calendar)

An events calendar component built for React and made for modern browsers (read: IE10+) and uses flexbox over the classic tables-ception approach.

[**DEMO and Docs**](http://intljusticemission.github.io/react-big-calendar/examples/index.html)

Inspired by [Full Calendar](http://fullcalendar.io/).

## Use and Setup

`npm install react-big-calendar-dbc --save`

Include `react-big-calendar-dbc/lib/css/react-big-calendar.css` for styles, and make sure your calendar's container
element has a height, or the calendar won't be visible.

## Added features

- Added prop 'useKeymaster' for switching between months with left/right keyboard arrows
- Added prop 'onClickAdd'. In calendar cell will appear "dummy" event, that return event by onClick event
