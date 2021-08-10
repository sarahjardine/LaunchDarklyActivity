Build Instructions

1. Replace <CLIENT_SIDE_ID> on idex.html page with Client-Side ID key from your LaunchDarkly Enviornment found under Account Settings > Projects.
2. Create a feature flag named Coffee Flavor 
  a.  For the Key, enter coffee_flavor
  b.  Check the box for "SDKs using Client-side ID"
  c.  Save flag
  d.  Click on flag name to edit.
      i. Click "Add user targets"
         a. Under true click on "Add users..." and select  Bob Loblaw.
         b. Under false click on "Add users..." and select Gob Bluth.
3. Create a feature flag named Moccamaster
  a.  For the Key, enter moccamaster
  b.  Check the box for "SDKs using Client-side ID"
    c.  Save flag
  d.  Click on flag name to edit.
      i. Click "Add user targets"
         a. Under true click on "Add users..." and select  Gob Bluth.
         b. Under false click on "Add users..." and select Bob Loblaw.
4. Turn on and off feature flag to see the messages change

NOTE: There is not a proper login screen, therefore the target individual users feature isn't really applicable. However, I wanted to show that I understand how users are added into the list and how this feature would work if there was the ablitiy to log in. 
