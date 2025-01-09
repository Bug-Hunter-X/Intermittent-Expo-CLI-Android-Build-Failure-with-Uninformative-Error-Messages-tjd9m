# Intermittent Expo CLI Android Build Failure

This repository demonstrates a bug encountered when building an Android app using the Expo CLI. The build process intermittently fails with vague error messages, making debugging challenging.  The issue appears related to network connectivity during the build, potentially affecting dependency downloads or cloud service interactions. This example uses a simple counter app to highlight the potential issue.  See bug.js for the code and bugSolution.js for a potential workaround. 

## To Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `expo start`.
4. Attempt to build the Android app using `expo build:android`.  The build may succeed on the first try, or it may fail with an uninformative error.  Repeat steps 3 and 4 until a failure occurs.

## Potential Workarounds

Check the bugSolution.js file for suggested workarounds to address the intermittent build failures. These might involve improving network stability and/or retrying the build process.