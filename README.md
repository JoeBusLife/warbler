# Warbler
### For this project I took an already existing code base (provided by Springboard) of a twitter clone and added functionality, searched for & fixed bugs, and created the automated tests
<br>

## Additions, changes and improvments made
- Implemented logout functionality
- Implemented likes functionality
- Added ablity to edit user profile
- Added user bio to user profile page
- Added user banner photo to user profile page
- Added user location to user profile page
- Added bio to user cards
- Fixed unfollow button not showing up correctly on list_users route
- Removed ability for a user to follow themself
- Added like button to messages_show route
- Fixed Python Error that occured where when you try to click unfollow on a user after already unfollowing them in another window
- Fixed Python Error that occured where when you try to click unlike on a post after already unliking it in another window
- Stopped join page from being accesable while logged in
- Added error feedback for signup form, when a username is already taken. Before it would only say "Email already taken" even when it was actually the username that was alreay taken.
- When user follows/ unfollows: changed redirect from being user profile page to being the page the user was just on.
- When user likes/ unlikes: changed redirect from being user profile page to being the page the user was just on.
