## STEPS

# The functionality is almost the same that "master-Redux-DashBoard"

1.  I only made some adjustment in order to show the single student chart in a single page, the earlier version, the student data was displayed next to students lists

2.  I Look to long hours of bootstrap tutorial.

3.  Creating the table was a pain in the ass coz I need to change the structure. For that I have to map only in the body of the table, if I map in the parent component, it creates me a table for every element which is not cool at all!

## online deploy ok
npm run build

* In order to put in online I need to make some changes in the package json coz it was already outdated

"scripts": {
    "start": "react-scripts start",
    "build": "CI= react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  }

