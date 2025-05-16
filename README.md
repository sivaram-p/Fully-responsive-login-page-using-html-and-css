# Frontend of login-page
In this repository I'm creating a basic login page using html and css with some minor js. This will further be used as a part of full stack web development repositories


# 1.html
There are two pages login page and sign up page where the user is directed to login if he has some credentials and directed to sign up page if he doesn't
  # 1-LOGIN
  The login collects the data like userid, password and sbmits to the browser for the backend to acess it each userid and password has its own id for the easy usage of them in js and , m  
  further in backend development

  # 2-SIGNUP
  It is called when the user fails to login or the user is a new user where he would need to fill up a form that takes his details like full name, mobile-no:, new userid, about, password 
  and for a profile picture as in the case of login page this also holds some id for future purposes.There is a condition that when user tries to make his/her profile picture might want to 
  see a preview of it this is achieved using js and also if not satisfied he/she need to replace/remove the input profile picture for this a custom button named remove img
  is also made which has some js operations to perform.
  
# 2.CSS
This holds the css lines that make styling for the html document

# 3.JS
It has not much purpose considering the current state but will be super useful when going to the future stages of this project.In current state js is used to achieve a preview of the profile picture in the signup page which is a case we discussed above in order to achieve this we initialise the icon of profile image with a custom stock-image link when the user inputs the image file js changes the source of the link that had been displaying to the new input file link. This way a preview of input is obtained then for remove img button js changes link back to stock-image link. 

# SUMMARY

  # 🧱 login.html
  Collects user ID/email + password.
  Form is prepped for backend hookup.  
  Has link to sign up if the user doesn’t have an account.
  # 🧾 signup.html
  Form fields:
  Full name
  Mobile
  Email/User ID
  About section
  Password
  Profile pic upload
  Profile image shows preview after selection.
  "Remove Image" button resets to default avatar.
  # 🎨 style.css
  Uses flexbox, some responsive tweaks.
  Centered forms in a card-like UI.
  Avatar styled as a round image.
  Clean layout, no libraries used.
  # ⚙️ JS (inline or external)
  Image preview via FileReader.
  Reset preview via remove button.
  JS IDs are used to target inputs and image.
# ⚡ To Do (Eventually)
  Add real backend.
  Form validation.
  Field error handling.
  Dark mode maybe.

