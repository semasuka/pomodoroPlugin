# Strict-Workflow-Beeminder
A Chrome extension that helps you stay focused by blocking sites during work timers and letting you browse during break timers. Now also logs work sessions automatically to beeminder.

## Setup
1. Clone the repository. If you're not familiar with the command line, you can do this by clicking "clone in desktop" and using the github desktop client or by downloading the zip file from the link on the right hand side of the repository.
4. Open Chrome and go to your extensions page (chrome://extensions).
5. Check the developer mode box if it isn't already checked.
6. Click 'load an unpacked extension' and select the folder that contains this repo.
7. Right click on the extension icon (a small red tomato) and click 'Options' or click on 'Options' in the Chrome extension view. Configure the main strict workflow settings to your liking!
8. At the bottom of the options, fill in your beeminder username, auth token, and default goal name. (To find your authentication token, log in to beeminder and point your web browser to https://www.beeminder.com/api/v1/auth_token.json)
8. Start a work session by clicking on the extension icon.
9. Type an (optional) comment in the popup window and hit enter or save comment. When the work session is completed, your datapoint will automatically be logged to your beeminder goal. If you include a hashtag at the end of the comment, the pomodoro will be logged to that goal instead of the default beeminder goal. For example ('this is my comment #goal') will log a value of 1 with a comment 'this is my comment' to the beeminder goal 'goal.' Note that the hashtag must come last. Any text after the hashtag will be ignored and not included in the comment.
