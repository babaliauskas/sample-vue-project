# RunBuggy front-end test project

# Scenario

This application lists drivers and allows users to see details about a specific driver.

### User Stories

1. As a user I should see a loading indicator whenever data is being retrieved [X]
2. As a user I should see a list of drivers (first name only) when I visit the root of the application (/) [X]
3. As a user I should be able to click on a driver and be navigated to a detail page for that specific driver [X]
4. As a user I should see first name, last name and id when I see a driver's details [X]
5. As a user I should be able to navigate to the detail page directly through URL [X]

### Requirements

1. This project is configured to use the vuetifyjs.com library of pre-built components, try to leverage this as much as possible

### Bonus tasks

1. Add client side filtering on the list [X]
2. Try to find a way to minimize the amount of bandwidth needed when navigating between the list and details page [X]
3. Try to make the list component configurable (e.g.: allow for different font styles, or colors) [X]
4. Create a component which takes a driver object as a property and displays an avatar of the first and last name initials [X]

### Hints

Try to build components for repeatable items, trying using template slots
Look in to Vuex for state persistance

## How to get started

- run npm install in application folder
- run npm serve
- visit local server (http://localhost:8080 by default)
