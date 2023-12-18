# Personal Website via GitHub Markdowns
A Static HTML/CSS/JavaScript Website using GitHub as Database for its content

**[🔗 Remixable DEMO @ PicoApps](https://a.picoapps.xyz/window-population)**

**[🔗 LIVE @ wilhelm.digital](https://wilhelm.digital/)**

## Table of Contents
1. [Features](#features)
2. [Screenshots ☀️ Day Mode](#screenshots-️-day-mode)
3. [Screenshots 🌗 Night Mode](#screenshots--night-mode)
4. [Technologies and Libraries](#technologies-and-libraries)
5. [How to Use?](#how-to-use)
   - [Step 1: Clone the Repository](#step-1-clone-the-repository)
   - [Step 2: Customize the Website](#step-2-customize-the-website)
   - [Step 3: Add Content](#step-3-add-content)
   - [Step 4: Deploy the Website](#step-4-deploy-the-website)

# Features
* **Dynamic Content Fetching**: The website dynamically fetches and displays content from GitHub repositories, showcasing projects, posts, and listenings, keeping the content fresh and updated
* **Responsive Design**: Tailored for various device sizes and screen resolutions using Tailwind CSS, ensuring a seamless user experience across desktops, tablets, and mobile devices
* **Interactive Particle Background**: Integrates an animated particle system (using particles.js) as a background, adding a visually engaging and interactive element to the website
* **Dark Mode Toggle**: Includes a user-friendly toggle switch for dark mode, enhancing visual comfort and accessibility for different lighting conditions and user preferences
* **Markdown Rendering**: Utilizes Showdown.js to convert Markdown files into HTML, providing an easy way to write and display styled content
* **Social Media Integration**: Offers quick access to various social media platforms and contact methods, encouraging engagement and connectivity
* **Interactive Footer with Elevator Effect**: The footer, powered by elevator.js, provides a unique, humorous interaction for navigating the page with an 'elevator ride' sound effect
* **Scroll Down Animation**: Features an animated scroll-down button, guiding users to explore more content intuitively
* **Custom Styling for Markdown Content**: Special CSS styling is applied to Markdown content, enhancing readability and visual appeal
* **Content Shuffling and Expansion**: Content is randomly shuffled for variety, and a 'Show More' button is provided for expanded viewing, keeping the initial page view neat while allowing deeper exploration.


# SCREENSHOTS ☀️ Day Mode
![day](https://github.com/tobwil/markdown_website/assets/72387477/906b8086-02a1-489f-b8e8-16f12bc270f7)

![contentday](https://github.com/tobwil/markdown_website/assets/72387477/05bc9f86-bd80-48fb-939c-120d14ed046b)

---

# SCREENSHOTS 🌗 Night Mode
![night](https://github.com/tobwil/markdown_website/assets/72387477/2530b4d9-6d79-4127-9aa9-d057144c7b24)

![contentnight](https://github.com/tobwil/markdown_website/assets/72387477/756b6e58-6bba-4c71-8bdb-727cfae6a64d)

# Technologies and Libraries
* Tailwind CSS (v2.2.3)
* Font Awesome (v6.4.2)
* Showdown.js (v1.9.1)
* Particles.js (v2.0.0)
* Elevator.js
* Native JavaScript
* HTML5
* CSS3

# How to use?
## Step 1: Clone the Repository
**Fork or Clone the Original Repository**: If the original repository is available on GitHub and allows forking, you can fork it. Alternatively, you can clone it directly to your local machine using Git. For forking, use the GitHub interface. For cloning, use:
```
bash
Copy code
git clone https://github.com/tobwil/markdown_website
```
**Create Your Own Repository**: If you forked the repository, you already have a copy on your GitHub account. If you cloned it, create a new repository on GitHub and push the cloned content to your new repository.

## Step 2: Customize the Website
**Update Repository Links**: In the JavaScript code, change the baseUrl variable to point to your own GitHub repository:
```
javascript
Copy code
const baseUrl = "https://api.github.com/repos/[Your-GitHub-Username]/[Your-Repo-Name]/contents/";
Modify Content: Replace the existing content with your own. This includes updating Markdown files in the 'posts', 'projects', and 'listening' directories.
```
**Adjust HTML and CSS**: Customize the HTML and CSS files to match your personal branding, style preferences, and content layout. Update titles, headings, and links.

**Customize JavaScript**: Modify the JavaScript as needed to suit your content structure and interactivity preferences.

## Step 3: Add Content
**Create Markdown Files**: Add your own Markdown files in the respective folders (posts, projects, listening) in your GitHub repository. These files should contain the content you want to display on your website.

**Commit and Push Changes**: After adding or updating the content, commit your changes and push them to your GitHub repository:
```
bash
Copy code
git add .
git commit -m "Update content"
git push origin master
```
📋 ***Project Markdown Layout***
```
# Title
Subtitle
<br>

<img src="IMAGE URL" height="200">
<br>

## Key Features

* Feature 1
* Feature 2
* Feature 3
<br>

**[<i class="fa-solid fa-up-right-from-square"></i> Uncover the Project - Click Here](PROJECT URL)**
```
📋 ***Listening Markdown Layout***
```
<a href="SPOTIFY URL">
    <img src="IMAGE URL" width="200" height="200">
</a>
```
📋 ***Post Markdown Layout***
```
# Title (price)
Subtitle
<br>

[<i class="fa-solid fa-fire"></i> Check it out](LINK URL)
```
## Step 4: Deploy the Website
**GitHub Pages**: You can use GitHub Pages to host your website directly from your GitHub repository. Go to the repository settings on GitHub, find the "Pages" section, and select the branch you want to deploy.

**Custom Domain (Optional)**: If you have a custom domain, you can configure it in the GitHub Pages settings.
