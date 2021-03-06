# Warbler
### For this project I was given an existing code base (provided by Springboard) of a twitter clone. I added various functionality, searched for & fixed bugs, and created the automated tests.

### Live Site: https://warbler-joeh.herokuapp.com/
<br>

## Additions, changes and improvements made
- Implemented logout functionality
- Implemented likes functionality
- Added ability to edit user profile
- Added user bio to user profile page
- Added user banner photo to user profile page
- Added user location to user profile page
- Added bio to user cards
- Fixed unfollow button not showing up correctly in user search results (list_users route)
- Removed ability for a user to follow themself
- Added like button to page that shows a single message (messages_show route)
- Fixed backend Error that occurred when you tried to click unfollow on a user after already unfollowing them in another window
- Fixed backend Error that occurred when you tried to click unlike on a post after already unliking it in another window
- Stopped join page from being accessible while logged in
- Added error feedback for signup form when a username is already taken. Before it would only say "Email already taken" even when it was actually the username that was already taken.
- When user follows/unfollows: changed redirect from being user profile page to being the page the user was just on.
- When user likes/unlikes: changed redirect from being user profile page to being the page the user was just on.
