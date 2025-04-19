## Facebook Login

### Login Valid Scenarios
- Login with a valid email address and a valid password
- Login with a valid phone number and a valid password
- Login with different ways of writing phone number [+995599123456, 599123456]
- Login with valid user without verifying email or phone number
- Login with valid password after using forgotten password functionality
- Check show password button
- Check copy/paste of password
- Validate that after login user is redirected to NewsFeed page
- Login with a deactivated account
- Login with a suspended account

### Login Invalid Scenarios
- Login without filling phone or email field
- Login without filling password field
- Login with an invalid email (not registered)
- Login with an invalid email (wrong format)
- Login with an invalid phone number (not registered)
- Login with an invalid phone number (wrong format)
- Login with an invalid password with valid email
- Login with an invalid password with valid phone number
- Login with an invalid password 3 times
- Login with a valid password after being blocked from accessing the app
- Login with providing an old password
- Login with old password after using forgotten password functionality
- Login without internet connection

### Redirections to other sections
- Validate redirection to forgotten password page
- Validate redirection to sign up page
- Validate redirection to create a page

### Compatibility
- Test using Chrome
- Test using Firefox
- Test using Edge
- Test using Safari
- Test using Safari on iPhone
- Test using Chrome on iPhone
- Test using Chrome on Android
- Test using any browser on a tablet
