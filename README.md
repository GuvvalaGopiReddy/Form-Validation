User Authentication System

This is a simple web-based user authentication system built using HTML, CSS, and JavaScript, featuring:

🔐 Features

1. User Registration with validation:

  	-->Full name (min. 5 characters)

  	-->Valid email

  -->Valid 10-digit phone number

  -->Secure password (min. 8 chars, not "password" or name)

  -->Password strength indicator

  -->Real-time validation with visual feedback

2. Login System:

  -->Email & password-based login

  -->Error message on invalid login

  -->Persistent login using local Storage

3. Dashboard:

  -->Displays logged-in user info

  -->Option to logout

4. Password Requirements Panel:

  -->Live check for common password mistakes

  -->Visual cues for requirement validation

📦 Tech Stack

Frontend: HTML5, CSS3 (with responsive design), Vanilla JavaScript

Storage: Browser local Storage (no backend)

🛠 How It Works

1. Registration:

	-->Form collects user data

	-->Input is validated in real-time

	-->Data is saved in local Storage

	-->Displays success message and redirects to login

2. Login:

	-->Authenticates against data in local Storage

	-->On success, shows dashboard and saves session (current User)

3. Dashboard:

	-->Displays full name, email, and phone

	-->"Logout" clears session and returns to login page
