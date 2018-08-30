# GO1-Front-End-Test
Files for GO1 Front End tech test.

## Front-end Scenario

Build a slim application to retrieve, filter and display training events based on a user's location and the current date.

## Requirements
* You can use any javascript framework.
* Retrieve events data using the supplied mock api (or build your own for bonus points).
* If you wish to build your own, the data for events should contain:
    - Title
    - DateTime in ISO 8601 format
    - Image url
    - Available Seats
    - Location (City)
    - Description

* Your application should:
    - Show the next five events in a list, ordered from soonest to latest.
    - The event should show the course image, title, date and location.
    - Clicking on the event should open a new interface with the full event's information.
    - [Transpile ES6](https://css-tricks.com/transpiling-es6/) (you'll need this to use the supplied mock api)

* You should include some test coverage for this application.
* Commit your work to a repository regularly (and make it public or send us the .git directory)
* Record how long you work on this application (be honest, accurate task estimation is important in this industry)

## Suggestions
An application like this can be deployed quickly using [Create-react-app](https://github.com/facebook/create-react-app), which will supply the packaging, test framework and transpiling needed.

However do not feel constrained by this! If you are more confident in another framework (eg. React, or Angular, Vue), build this application in whatever you like to work with.

You will need to calculate distance between positions to achieve the required functionality.  A library such as [TurfJS](http://turfjs.org/) will allow you to do make these calculations easily.

## Extra Credits
Include a map library to display location/events.
Package your application in a Docker container.
Achieve >80% test coverage.
Impress us by adding something amazing that's not documented above.
