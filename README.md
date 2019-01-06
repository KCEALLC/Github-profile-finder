# Github-profile-finder
App built in JavaScript to search real Github users profiles


Description:
Search users profiles, repositories, followers, following, links etc from GitHub using fetch API.
![GitHub Profile Finder](/imgs/githubuserfinder.JPG)

App searches as you type and returns the latest 10 repos of a user sorted in ASC order. 
When no user is found, a message is displayed indicating that there is no user found.

![GitHub User Not Found](/imgs/githubusernotfound.JPG)


Requirements:
- Local live server environment
- GitHub OAuth App registration

Usage:
1. Download or clone the source files to a local folder.
2. You must register your app with GitHub to get your client id and client secret keys.
https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/

Consult the GitHub API guidelines to make changes to your API calls.
https://developer.github.com/v3/

3. Once registered, add your client_id and client_secret to the github.js file in the GitHub Class:
this.client_id = "";
this.client_secret = "";

4. Open index.html with your live server

5. Enjoy!!

NOTE: This app is for educational purposes only and should not be used in production or commercial environments.
