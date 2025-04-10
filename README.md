# JNTUH CAMPUS NAVIGATION WEBSITE- Redirect

This project is a lightweight HTML redirector that distributes traffic across multiple instances of the JNTUH Navigation website. It is designed to enhance load handling and provide a smooth experience to users by randomly redirecting them to one of several hosted versions of the site.

## 🌐 About JNTUH Navigation

JNTUH Navigation is an interactive website designed to enhance the campus experience at Jawaharlal Nehru Technological University Hyderabad (JNTUH). It features:
<li>🏫 A clean, user-friendly directory of all major campus buildings.
<li>📍 Real-time integration with Google Maps for on-the-go navigation.
<li>📱 A fully mobile-friendly and responsive design for use on any device.
The website was proudly used during JNTUH Orientation 2024 to help new students and their parents easily navigate the campus.

### Interface of the JNTUH Navigation Website
<img src="interfacejntu.png">

## 🔀 Purpose of This Project

To maintain performance and manage load during high-traffic events (such as orientations), this redirect page helps by:
<li>Randomly sending users to one of multiple hosted versions of the navigation website.
<li>Balancing traffic to prevent slowdowns or downtime on any single instance.

## 🚀 How It Works

<li>On page load, a small JavaScript function selects a random URL from a list of hosted navigation sites.
<li>The browser is then automatically redirected to the selected URL.

## 📁 Files Included

- `index.html`: The main HTML file containing JavaScript logic for redirection.

## 🛠️ Customization

To add or update destination URLs, modify the `urls` array in the `<script>` section of `index.html`.

## ✨ Deployment

Simply host the `index.html` file on **GitHub Pages** or any web server. When accessed, it will handle redirection automatically.

## 📣 Acknowledgments

Special thanks to the team behind the **JNTUH Orientation 2024** for using this tool to improve the campus visit experience!
