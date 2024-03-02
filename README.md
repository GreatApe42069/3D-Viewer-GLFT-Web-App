# Node Runners 3D Viewer Web App

Welcome to the Node Runners 3D Viewer Web App – an interactive platform for viewing 3D models in your browser.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Node Runners 3D Viewer Web App is a Flask-based web application that allows users to view 3D models with ease. The application utilizes Babylon.js for rendering and provides an interactive environment for exploring 3D content.

## Features

- **Simple and Intuitive Interface:** A user-friendly interface for easy navigation.

- **File Drop Functionality:** Drag and drop GLTF files directly onto the canvas for seamless interaction.

- **Responsive Design:** Works on various devices and screen sizes.

## Prerequisites

Before getting started, make sure you have the following installed:

- [Python](https://www.python.org/downloads/)

- [Virtualenv](https://pypi.org/project/virtualenv/)


## Installation

**Clone the repository to your local machine:**

git clone https://github.com/GreatApe42069/3D-Viewer-GLFT-Web-App.git


-Navigate to the project directory:

`cd 3d-view-web-app`


-Set up a virtual environment:

`python -m venv venv
.\venv\Scripts\activate`


# Usage

**-Run the Flask application:**

`python 3d-view-web_app.py`


**-Open your web browser and visit:**

http://127.0.0.1:5000/ to access the 3D Viewer Web App.

**-Explore the interactive 3D viewer and drag and drop GLTF files onto the canvas for an immersive experience.**

## Customization

***You can customize the application by modifying the HTML template (templates/3d-view-web_app_index.html) and Flask script `3d-view-web_app.py Make changes according to your preferences and needs.***

### Flask App Customization:

**Styling and Templates:**

-Update the CSS styles in your Flask app's HTML templates for a personalized look.

-Create a separate CSS file and link it to your HTML templates for more organized styling.

-Explore and use different front-end frameworks (Bootstrap, Bulma, etc.) for ready-made styles.


**Banner Image:**

-Add a banner image to your Flask app's HTML template for a customized header.

-Store the banner image in a designated folder, and update the HTML template accordingly.


**Page Title:**

-Customize the page title in the HTML template to reflect your app's identity.

**Custom Domain:**

-If deploying on a cloud platform, consider setting up a custom domain for your Flask app like on  "Heroku"

***Here's a summary of the next steps:***

**Commit Changes:**

***Make sure all your changes are committed to Git.***


**Download and install the Heroku CLI and logging in before deploying `heroku login`:**

-Download and install the Heroku Command Line Interface (CLI) using the following commands:

`curl https://cli-assets.heroku.com/install-heroku.ps1 -UseBasicParsing | Invoke-Expression`


*This command downloads and installs the Heroku CLI using PowerShell.*

-You can now verify the installation by opening a new PowerShell window and running:

`heroku --version`


**Login to Heroku:**

-Open your terminal or command prompt and run the following command to log in to your Heroku account:

`heroku login`

*(This command will open a new tab in your web browser, prompting you to log in. Once logged in, return to the terminal.)*


**For Windows:**

-If you haven't done so already, Navigate to your project directory in the terminal.

Run the following command to create a new Heroku app. You can use the following command in your project directory:

`heroku create your-app-name`

**Push to Heroku:**

-Push your code to Heroku with the following command:

`git push heroku master`

**Open the App:**

-Once the deployment is successful, open your app in the browser with:

`heroku open`

**Troubleshooting:**

-If there are any issues, you can check the logs with:

`heroku logs --tail`


### 3D Viewer Web App Customization:

**Background Color:**

-Change the background color of the 3D viewer canvas by modifying the CSS styles.

**3D Model:**

-Replace the default 3D model with your custom model.

-Allow users to upload their own 3D models through the Flask app.

**File Drop Functionality:**

-Enhance the file drop functionality to support multiple file types.

-Provide visual feedback on successful file uploads.

**Interactive Elements:**

-Implement interactive elements using Babylon.js 
-features (animations, user interactions).

-Customize lighting and shading effects.

**Responsive Design:**

-Optimize the 3D viewer for different screen sizes and devices.

**Dynamic Content:**

-Dynamically load 3D models based on user preferences or selections.

*Textures and Materials:**

-Experiment with different textures and materials for the 3D models.


# Contributing

**If you'd like to contribute or donate to the development of `The Node Runners 3D Viewer Web App` , please donate in Dogecoin. For contributors its as easy as opening issues, and creating pull requests**

***For Those want to support, Send all Donations to:***
 
**DC8iWykpcZS6HVZdCNLvJehunRyXotGoHH**

## License

This project is licensed under the MIT License.

