NPM INSTALLS

npm i -S @react-google-maps/api

npm install --save use-places-autocomplete

npm install @reach/combobox

npm install react-bootstrap bootstrap

npm install react-router-dom

if error run: --legacy-peer-deps

Deploy Script:

npm install gh-pages --save-dev

"homepage": "http://kotaueshima.github.io capstone-project-frontend",

"predeploy": "npm run build",
"deploy": "gh-pages -d build",

then npm run deploy

Project Pitch:

Have you ever wondered what somebody across the world is listening to? This project will create a global platform for users to browse and add songs based on their location. This project will utilize google maps API as well as spotify API to display user locations and song choice.

User story:

As a user, you should be able to browse through a global map, where there will be markers of other user posts, and they should be able to click on these markers to access a title of a song that the user has posted. The song should also have a valid link to a spotify version of the song. The user can also login to create his own posts of a song based on their current location.

Stretch Goals:

Create user specific bitmojis on the map
Overall counter of how many users and the number of posts they have added
Decide (Limti one song per user at a time? to decrease unlimited posts)
Create your own playlists based on user songs
Playlists generated by certain areas of the map (cities? or more specific?)
Most popular song in the world?
