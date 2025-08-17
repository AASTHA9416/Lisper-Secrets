=========================
🤫 Random Secret Sharer
=========================

A simple Node.js web application that fetches and displays a random user-submitted secret from an external API. This project demonstrates a basic backend setup using Express, EJS for server-side rendering, and Axios to handle HTTP requests.

-----------
## Features
-----------
* Fetches a random secret and associated username from the Secrets API.
* Dynamically renders the content on the page using EJS templates.
* Clean, minimalist interface.

---------------------
## Technology Stack
---------------------
* Backend: Node.js, Express.js
* Templating Engine: EJS (Embedded JavaScript)
* HTTP Client: Axios
* Package Manager: npm

-------------------------
## Setup and Installation
-------------------------

To get a local copy up and running, follow these simple steps.

### Prerequisites
Make sure you have Node.js and npm installed on your machine.
- Node.js (https://nodejs.org/)

### Installation
1. Clone the repository:
   git clone https://github.com/AASTHA9416/Lisper-Secrets.git

2. Navigate to the project directory:
   cd Lisper-Secrets.git

3. Install NPM packages:
   npm install

4. Run the application:
   node index.js

5. Open your browser and navigate to http://localhost:3000.

----------------
## API Reference
----------------
This project utilizes the public Secrets API provided by App Brewery.

Endpoint: GET https://secrets-api.appbrewery.com/random

Example Response:
{
  "id": 4,
  "secret": "I've perfected the art of taking selfies in the bathroom to hide the fact that I'm really just sitting on the toilet.",
  "username": "masteroftoiletselfies"
}