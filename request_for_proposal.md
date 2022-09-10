# WorkOutLoud — Request for Proposal (v1.0)

WorkOutLoud Team

**Members:** Van Nguyen, Charlie Truong, Nickholas Boboaca, Bao Nguyen

Hello WorkOutLoud team, 

My name is Dwayne Johnson, an actor known for my physical fitness. I would like to create a unique workout app for my fans to be able to exercise easier at home. 

WorkOutLoud is a mobile-friendly app where users can create workouts that are spoken out loud. In addition, the app would be able to count down exercise reps using the device’s microphone. “Voice guided custom workouts”.


## BUSINESS REQUIREMENTS

1. Features
    1. Account management
        1. P0 - Register, log in/log out
        2. P0 - Email authentication 
            1. The app should send an email to verify the user’s email.
        3. P0 - Account settings
            2. The user can edit their names.
        4. P1 - Login with Google Account
    2. Workout management
        1. P0 - The user can create, save, delete, and view workouts.
        2. P0 - The user can create and edit the workout name, exercise name, exercise duration/rep count, breaks.
        3. P0 - The app has an audible voice that counts down exercise duration/rep count or a continuous rep countdown timer. 
        4. P0 - The user can play/pause/stop a workout and select the next/previous exercise in a workout.
        5. P1 - The user can use voice commands to play/pause/stop a workout and select the next/previous exercise in a workout.
        6. P1 - The user can set workout labels, such as difficulty level, type of workout, muscle groups. 
        7. P2 - The user can set different voices for workouts.
        8. P2 - The user can set a multiplier (adjust a scale) to make workouts easier or more difficult. This would adjust the exercise duration/rep count.
    3. Exercises
        1. P0 - The user can view, edit, and delete their past workouts on an exercise history page. 
        2. P1 - The user can create, edit, delete different exercises.
        3. P1 - The user can view and share different exercises to use in workouts.
    4. Search
        1. P1 - The app has preset default workouts for users.
        2. P1 - The user can filter community workouts based on workout labels.
    5. Community
        1. P1 - The user can share/unshare workouts via a link.
        2. P1 - The user can favorite workouts.
        3. P1 - The user can clone workouts.
        4. P1 - The user can share a link to their profile and find other profiles.
        5. P2 - The user can add friends.
        6. P2 - The user can share workouts, share exercises, create posts, upload images, comment on posts, and like posts.
        7. P2 - The user can view a user’s favorite workouts, exercise history, feed, and friends.


## SOFTWARE REQUIREMENTS

1. Devices:
    1. P0 - Users should be able to access the application on both desktop and mobile browsers.
    2. P1 - Users should be able to access the application on an iOS device. 
    3. P2 - Users should be able to access the application on an Android device 
    4. P2 - Users should be able to access the application on an Apple watch or WearOS device.
2. User Interface:
    1. P0 - Responsive
    2. P1 - Dark and light mode compatible
3. User Authentication / Login:
    1. P0 - Users should be able to create and access their account on the app.
4. Offline Capability:
    1. P0 - Information can be used online or offline once the website has been loaded for a workout.
5. Security:
    1. All communication will be happening from a HTTPS domain
        1. SSL protocol will be used to create an encrypted link between web server and web browser.
6. Scalability
    1. The application should be able to handle 10,000 active users/month and be able to manually or automatically provisioned to manage a larger userbase.
7. Reliability
    1. P0 - Unit and integration tests to ensure proper deployment.
    2. P0 - CloudWatch metrics and alarms to track billing usage and utilization rate.


## HARDWARE REQUIREMENTS

1. Data storage
    1. User accounts and app data will be stored on AWS.
2. Server:
    1. The backend API will be hosted on Amazon.
    2. The static website files will be hosted on Amazon so it can be accessible from anywhere.
3. Compatibility:
    1. A desktop or mobile device with reliable network connection.

## SUPPORT

1. Maintenance:
    1. Consistent maintenance to the web app to allow for reliable service and performance.
2. Upgrade:
    1. The ability to add to more features to further improve user experience.

I need this app to be completed by May 2023. Our initial budget for this project is $100k. It can be negotiated as the technical details and requirements are fleshed out as they may change during development. If there are any questions or issues with the requirements, please let me know, so we can clarify the details. We are expecting you to supply the technical details.

Thank you,

Dwayne “the Rock 🪨” Johnson
