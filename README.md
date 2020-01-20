# Picture-This
Picture This is a school assignment at YRGO where we got the opportunity to learn how to create an Instagram Clone using CSS, HTML, Javascript, PHP and a SQL database.

![header-img](https://media.giphy.com/media/3oz8xSfBvRqfbU9n0c/source.gif) 

## Features
* As a user I should be able to create an account.
* As a user I should be able to login.
* As a user I should be able to logout.
* As a user I should be able to edit my account email, password and biography.
* As a user I should be able to upload a profile avatar image.
* As a user I should be able to create new posts with image and description.
* As a user I should be able to edit my posts.
* As a user I should be able to delete my posts.
* As a user I should be able to like posts.
* As a user I should be able to remove likes from posts.
### Extra feature
* As a user I should be able to follow and unfollow other users.


## Installation
1. Clone the repository 
```bash
$ git clone https://github.com/Juljulia/Picture-This
```
2. Set up a webserver with the document root as the cloned repository.

### Testers 
* Maja Alin
* Victor Ljungblad
* Terese Thulin

### Code Review
Comments by Terese Thulin
* [modal-box.js](assets/scripts/modal-box.js) - I like how you solved your functionality with modal windows.
* [index.php:L3](https://github.com/Juljulia/Picture-This/blob/169ba2b0902c2d57f05749343ccd046d46055225/index.php#L3) - I suggest making this into a function (check if user is logged in) since it's repeated in all pages.
* [edit-post.php:L20](https://github.com/Juljulia/Picture-This/blob/169ba2b0902c2d57f05749343ccd046d46055225/edit-post.php#L20) - I suggest making this into a function (check for success messages) since it's repeated in all pages.
* [edit-post.php:L25](https://github.com/Juljulia/Picture-This/blob/169ba2b0902c2d57f05749343ccd046d46055225/edit-post.php#L25) - I suggest making this into a function (check for errors) since it's repeated in all pages.
* [index.php:L7](https://github.com/Juljulia/Picture-This/blob/169ba2b0902c2d57f05749343ccd046d46055225/index.php#L7) - I suggest formatting your paragraph with css instead of using br since it's not semantic.
* [functions.php:L20-116](https://github.com/Juljulia/Picture-This/blob/169ba2b0902c2d57f05749343ccd046d46055225/app/functions.php#L20) - It's recommended to add DockBlocks to your functions for better readability.
* [styles](https://github.com/Juljulia/Picture-This/tree/master/assets/styles) - I appreciate how you've separated your css into multiple files for better readability.
* [login-signup.css:L24](https://github.com/Juljulia/Picture-This/blob/169ba2b0902c2d57f05749343ccd046d46055225/assets/styles/login-signup.css#L24) - I suggest renaming and reusing this class on other column flexboxes to make code more DRY.
* [parse.php:L4](https://github.com/Juljulia/Picture-This/blob/169ba2b0902c2d57f05749343ccd046d46055225/app/parse.php#L4) - I suggest turning this into a function and calling that in your files instead of requring parse.php
* [parse.php:L18](https://github.com/Juljulia/Picture-This/blob/169ba2b0902c2d57f05749343ccd046d46055225/app/parse.php#L18) - I suggest turning this into a function and calling that in your files instead of requring parse.php
* Overall your code is clean and well commented. I really appreciated that when reviewing your code!
