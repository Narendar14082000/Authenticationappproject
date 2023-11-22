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

**9. Forgot Password (Bonus):**

- Access `forgot-password.ejs`.
- Option to generate a random password and send it via email.
- Alternatively, send a reset password link with an expiration time.

**Note:**

- Ensure the server is running and connected to the database.
- Update configuration files with your credentials.
