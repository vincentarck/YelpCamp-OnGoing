# YelpCamp OnGoing

## Getting Started

YelpCamp is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. This project was part of Colt Steele's web dev course on udemy. This project was created using Node.
I learned a lot from here, the code here is still not finished

### Prerequisites

Install all the dependencies inside this folder, you can check for more in package.json
* npm
  ```sh
  npm i
  ```

### Installation

_Below is an example of how you can run this project locally on port 3000

1. Make sure you have mongoDB and Mongoose installed on your device
2. Move to the seeds directory to create a static campground with fake data as initial initiation
   ```sh
   cd seeds
   node index.js 
   ```
3. Check your database status, open powershell, go to YelpCamp directory, run this command
   ```sh
   show dbs
   use yelp-camp
   db.campgrounds.find()
   ```
   Make sure something is display in your terminal
   
4. switch to git bash, run 
   ```js
   nodemon app.js
   ```
   make sure `Database Connected` is displayed

<p align="right">(<a href="#top">back to top</a>)</p>

