**Authentication System**

**1. Overview:**

This authentication system includes user sign up, sign in, sign out, password reset, and Google login/signup functionalities.

**2. Setup:**

- Install necessary dependencies (if any).
- Configure your database connection.

**3. Encryption:**

User passwords are securely stored in the database using encryption (e.g., bcrypt).

**4. Sign Up:**

- Access `signup.ejs`.
- Enter a valid email and matching passwords.
- Display notifications for unmatching passwords.

**5. Sign In:**

- Access `signin.ejs`.
- Enter a registered email and correct password.
- Redirects to `home.ejs` on successful sign-in.
- Display notification for incorrect passwords.

**6. Home:**

- Display user information.
- Buttons for Sign Out and Reset Password.

**7. Reset Password:**

- Access `reset.ejs`.
- Enter current password, new password, and confirm new password.
- Display notification for successful password reset.

**8. Google Login/Signup:**

- Access `google-login.ejs`.
- Implement Google OAuth for authentication.

## Deployment

The Authentication app is deployed and accessible at [Deployment Link](https://authentication-sample-app.onrender.com). Please visit the deployment link to explore the application.

## Support

For any issues, contact me throough mail:

- [Narendar](mailto:narendarreddypaindla@gmail.com)
