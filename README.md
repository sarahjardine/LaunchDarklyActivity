Build Instructions

- Replace <CLIENT_SIDE_ID> on idex.html page with Client-Side ID key from your LaunchDarkly Enviornment found under Account Settings > Projects.
- Create a feature flag named Coffee Flavor 
    - For the Key, enter coffee_flavor
    - Check the box for "SDKs using Client-side ID"
    - Save flag
    - Click on flag name to edit.
        - Click "Add user targets"
        - Under true click on "Add users..." and select  Bob Loblaw.
        - Under false click on "Add users..." and select Gob Bluth.
- Create a feature flag named Moccamaster
    - For the Key, enter moccamaster
    - Check the box for "SDKs using Client-side ID"
    -  Save flag
    - Click on flag name to edit.
        - Click "Add user targets"
        - Under true click on "Add users..." and select  Gob Bluth.
     - Under false click on "Add users..." and select Bob Loblaw.
- Turn on and off feature flag to see the messages change

NOTE: There is not a proper login screen, therefore the target individual users feature isn't really applicable. However, I wanted to show that I understand how users are populated into the user list and how this feature would work if there was the ablitiy to log in. 
