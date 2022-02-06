# Budget-Tracker

The challenge this week is to update an existing budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online

## Acceptance Criteria

```
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```

![Screen Shot of application](https://user-images.githubusercontent.com/90152576/152694996-d1c483a8-c238-4128-ac62-8cdea7039d9f.png)

https://pure-harbor-24321.herokuapp.com/

## Process of making this application

Get the existing budget tracker application working

Use indexedDB to allow for offline functionality so information is save and then uploaded when online again

Use serviceworker to save and load all the the html, css and js in the cache so everything loads when offline

also dont forget to add manifest for icons and etc to download app on device
