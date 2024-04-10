# Welcome to the Spotify API Album Finder 🚀
Spotify Album Finder is a web application that allows users to search for albums by artist name using the Spotify API. The application displays the album cover, album name, and a link to the album on Spotify. Built with React, this project demonstrates the use of hooks, API calls, and state management in a modern JavaScript application.
___
### To access the API, head over to the [Spotify for Developers](https://developer.spotify.com/) website and log in with your Spotify account. If you don't have one, you can [Create one](https://www.spotify.com/us/signup?forward_url=https%3A%2F%2Fopen.spotify.com%2F%3F) through the Spotify website.

### After logging in, go to the Dashboard by selecting your profile image in the top-right  of the screen, and then "Dashboard".

### Once you're on the Dashboard, click "Create App".

### Here you're going to give your app a name! Try "Album Finder" or "Spotify Music Finder"!

### Give your app a description and a redirect URL. Since we're creating an app for our personal use, insert the redirect as ```http://localhost/``` and tick on Web API under API/SDK files.

### Agree with Spotify's Developer Terms of Service and Design Guidelines, and you're all set! 💪

### By creating the new app, You now have the "Client ID" and "Client secret". These will be important for when you actually use the Spotify API.

## Open your terminal and copy/paste the below commands
```javascript
git clone https://github.com/prashwinrao/Spotify_API-Album-Finder.git
```

### After cloning open the folder in vs code and paste the below command in the terminal.
```javascript
npm install react-bootstrap bootstrap
```
## Now we have to connect to the Spotify API
### Remember those credentials mentioned earlier? The "Client ID" and "Client Secret"? Those are the Spotify API keys we're going to use for our project!
### To access them on the Spotify for Developers page, go to your Dashboard and then to your app. Next, go to "Settings":
### Next, under "Basic Information", you will find your app's "Client ID". To display your app's "Client secret", select "View client secret."


### The ID and secret are hidden for a reason. Never share this information publically; it should always be secure!
### In your main project folder, you're going to create a file called .env

### Here, you're going to copy the code block below and add your keys from the Spotify API developer settings.
```javascript
VITE_CLIENT_ID=YOUR CLIENT ID HERE
VITE_CLIENT_SECRET=YOUR CLIENT SECRET HERE
```
#### Make sure this .env file is inside .gitignore so you can push your code to GitHub without publishing your keys!

# Now Start the Development Server
```javascript
npm run dev
```

### BOOM!🎉🎉 Enter any artist's name in the search bar and watch the cards get populated with results!
![Final](https://raw.githubusercontent.com/codedex-io/projects/main/projects/build-an-album-finder-with-spotify-api/images/completed-album-finder-2.gif)
