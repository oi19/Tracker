# Tracker :
  
  - A tracking app with many features that help you record your tracks , and save them  as well as listing all previous saved tracks made by the user,
    And the ability to keep tracking user's location off and on the trackScreen to provide more features to the app , More Over, The ability to add new features
    such as deleting tracks and editing track names , searching for other users and see their records     
  - Adding the abitlity toggle between screens using navigation stucture (SwitchNavigator,StackNavigator, BottomTabNavigator
  - Using context for state management for dynamic usage with the flexibility to change it to redux 
  
  
  # Project Structure 
  
  ## App.js 
   - This file creates the app structure by creating app Container and the Navigation structure as well as the state managment whether context(Providers) or redux 
  
  
  ## src folder 
   - api folder
       - tracker.js 
          - handles the api requests as well as handling the authentication process 
            
   
   - components folder()
      - Form.js 
      - LoginText.js
      - Map.js
      - Spacer.js
      - TrackForm.js
   
   - context folder 
      - createDataContext.js (responsible for creating Context & blue print for using Context)
      - AuthContext.js ( handles the athentication process)
      - LocationContext.js (handles  the location data )
      - TrackContext.js ( handles the track's creating, posting and fetching processes)
   
   - hooks
      - userLocation.js
      - useSaveTrack.js
    
   - screens 
      - AccountScreen.js
      - AutoLoginScreen.js
      - SigninScreen.js
      - SignupScreen.js
      - TrackListScreen.js
      - TrackCreateScreen.js
      - TrackDetailScree.js
    
   - _mockLocation.js ( responsible for fake locations )
   - NavigationRef.js (responsible for Navigation)


# Setup
   ```shell script
git clone https://github.com/oi19/react-native/tree/tracker
cd Tracker
```
Run the following command to run your server in  different cmd inside  track-server folder .

```shell script
- cd track-server
- npm run dev
```
and
```shell script
- cd track-server
- npm run tunnel 
```

or
```shell script
- cd track-server
- ngrok http 3000
  ```

Run those following commands to run the app in inside Tracker folder.

```shell script
- cd Tracker
- npm start
```

