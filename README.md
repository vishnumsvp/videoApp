# videoApp
Video application based on Angular2
This is a self-learning application developed based on Angular2 on front end and API developed based on Nodejs, Express and MongoDB.

WorkFlow
--------
- Users logs in and API will return a valid JWT.
- JWT are stored on local storage and only authenticated users with valid JWT will be allowed to access the application inner pages.
- The Video Dispaly page will display list of Videos returned from API with title, description.
- On selection of video item, the application will navigate to Details page, where more details are displayed about the video.

Foreseen Enhancements
----------------------
- Adding thumbnail dispaly in the Video Dispaly page
- Scrollspy intergration in the video display page to have lazy load options
- Change in the theme
- Adding more Test cases.
- E2E test integration.
