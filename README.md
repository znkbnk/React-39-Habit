Step 1: Create a Contact Us Form Component:

- Create a new component for the Contact Us form. 
You can create a file named ContactUsForm.js.

Step 2: Add the "Contact Us" Button to SkewedNavbar:

- In your SkewedNavbar.js add the "Contact Us" button.

Step 3: Manage Form Visibility State in App Component:

- In your App.js component, you should manage
the visibility of the Contact Us form. 

Step 4: Modify Contact Us button:

- In your project's HTML file (usually index.html),
include the FontAwesome library.
- Install Animate.css in your terminal using npm.
- In your SkewedNavbar component file, import the
FontAwesome library.
- Replace the "Contact Us" button with a "Contact Us"
icon using FontAwesome.

Step 5: Update your ContactUsForm component:

- Inside your ContactUsForm component,
create a function named sendEmail that
uses EmailJS to send the email.
- In the handleContactSubmit function,
call the sendEmail function with the form data.
- Make sure to replace "YOUR_EMAILJS_SERVICE_ID",
"YOUR_EMAILJS_TEMPLATE_ID", and "YOUR_EMAILJS_USER_ID"
with the actual values you obtained from EmailJS.
- Don't forget to pass prop's to your components.

