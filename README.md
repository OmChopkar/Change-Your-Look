# Change Your Look : Hair Studio ✂️

A multi-page website built for a modern hair studio. This project showcases frontend development skills through a responsive, interactive user interface designed to attract clients and facilitate online appointment bookings.

## 🌟 Key Features
* **Modern & Responsive Design:** Fully adapts to desktop, tablet, and mobile screens.
* **Interactive UI:** Features smooth scrolling, CSS fade-in animations, dynamic hover effects.
* **Functional Appointment Form:** Integrated with Formspree for real-time email bookings.
* **Dynamic Media Dashboard:** A custom grid featuring an auto-playing video, Google Maps integration, an automated image slideshow.

## 🛠️ Tech Stack
* **HTML5:** Semantic structure and layout.
* **CSS3:** Custom styling, CSS Grid, Flexbox, and `@keyframes` animations.
* **JavaScript:** The responsive mobile menu and automated slideshows.
* **External Libraries:** FontAwesome (icons).

## 🚀 Live Demo
[Insert link to your live GitHub Pages site here, e.g., https://yourusername.github.io/change-your-look]

## 📧 Setting up the Booking Form

This project uses [Formspree](https://formspree.io/) to handle form submissions without needing a dedicated backend server. 

Here is how to set it up:

1. **Create a Free Account:** Go to [Formspree](https://formspree.io/) and sign up for a free account.
2. **Create a New Form:** Click the **+ New Project** button, and then create a **New Form**. Give it a name like "Hair Studio Bookings".
3. **Copy Your Endpoint URL:** Once created, Formspree will provide you with an integration URL that looks something like this: `https://formspree.io/f/your_unique_id`.
4. **Update the HTML:** * Open the `appointment.html` file in your code editor.
   * Locate the `<form>` tag around line 13.
   * Replace the `action` attribute placeholder with your new Formspree URL:
     ```html
     <form action="[https://formspree.io/f/YOUR_FORM_ID](https://formspree.io/f/YOUR_FORM_ID)" method="POST">
     
     <form action="[https://formspree.io/f/your_unique_id](https://formspree.io/f/your_unique_id)" method="POST">
     ```
5. **Test the Form:** Open your live site, fill out a test appointment, and hit submit. Formspree will ask you to activate your email address on the first submission, and then all future bookings will be sent directly to your inbox!

## 📂 Project Structure
```text
Change-Your-Look/
├── index.html           # Main landing page (Services, Testimonials, Contact)
├── about.html           # Team showcase and interactive 2x2 media/stats grid
├── appointment.html     # Dedicated booking portal
├── css/
│   ├── style.css        # Main page styling
│   ├── about.css        # Dark theme and grid styling for the About page
│   └── appointment.css  # Form styling
├── js/
│   └── script.js        # Slideshow logic and animated counters
└── media/               # Organized image and video assets
