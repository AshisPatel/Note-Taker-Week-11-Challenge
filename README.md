<h1>Note Taker</h1>
  <image src='https://img.shields.io/badge/license-MIT-green.svg' />
  <h2>Description</h2>
  
   ![Viewing, adding, and deleting notes on the Note Taker application](https://github.com/AshisPatel/Note-Taker-Week-11-Challenge/blob/main/noteTakerPreview.gif)

  Note Taker is a web application that is hosted via heroku! You can visit the app by following the website link in the *Website* section. The app lets you add and delete notes. All of this data is stored on a server that is connected to the front-end using node.js and express.js. 

  <h3>Technologies Used</h3>
  <ul>
    <li>Node.js</li>
    <li>Express.js</li>
    <li>Nanoid (for unique ID generation)</li>
    <li>Special thanks to UTA for providing the front end code for this assignment</li>
  </ul>

   <h3>Functionality</h3>
   
   The front-end functionality was provided by UTA. The back-end functionality was setup using express.js, and a few additional node packages. There are five API calls that are accounted for, three GETS, one POST, and one DELETE. The first GET takes the user to the homepage at the / route request. The second GET will retrieve the notes array stored in the db.json file on the server given the request for /api/notes. The third GET will catch any other /* routes and return the user to the homepage. The POST request will take the note title and note text and package it as an object for the server to read. Once the server receives the object, it generates a unique id using nanoid and then stores it in the db.json file. The DELETE request will take the unique ID of the note that the user would like to delete and sends it to the server. The stored object is found in the notes array of the db.json file and deleted before the db.json is updated and then sent back to the front-end. 

  <h2>Table of Contents</h2>
 <ul>
  <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#website">Website</a></li>
  <li><a href="#questions">Questions</a></li>
 </ul>

  

  <h2 id="usage">Usage</h2>
  <p>Upon navigating to the home page, click the Get Started button to access the notes interface. Here, you can click on any of the notes in the note-list to the left to view pre-existing notes. You can click the '+' button in the top-right corner to enter a note in the center of the screen. Each note needs a note title and some note text. Once this is provided, a save icon will appear in the top-right corner next to the '+' button. Saving a note will add it to the notes list on the left. Notes can be deleted by clicking on the red trash icon on the note. </p>
  
 
  
  <h2 id="license">License</h2>

  MIT - Find out more about this project's license(s) at: [https://choosealicense.com/licenses/](https://choosealicense.com/licenses/)

  
  <h2 id="website">Webiste</h2>
  
  Website: [Note-Taker Webpage](https://fathomless-bayou-34449.herokuapp.com/)

  

  <h2 id="questions">Questions</h2>
  
  <p> 
  Made by: AshisPatel<br />
  Github Profile: https://github.com/AshisPatel<br />
  </p>Email: ashis.n.patel@gmail.com<br />
  
  <h2>End Note - A Thank You to the Reader</h2>

  Thank you for checking out my project and README! With this project, I have taken my first steps into creating a full-stack project, so to that we have a mini-celebratory moment! 🥳 With that said, working with express.js was neat! There's some weird stuff going on with how certain variables over-write in terms of getting responses, however thanks to this I got to do a lot of delving into the syntax and learned a lot. The routing system is really nice, and APIs have been slightly demystified. On next week's episode of Ashis becomes a developer, we get to tackle databases! Then, we can have a website, where we don't all have the same notes. I believe I cleared out all my embarrassing  random notes from the website, so if you see anything there _it wasn't me_. 

  **Fun Fact**: The placement of candles on birthday cakes has various potential origins. Ancient Egyptians used candles during coronations, which were held to raise the status of humans to gods. Later, ancient Greeks placed candles on moon-shaped honey cakes made for the goddess Artemis. The Greeks thought that the smoke from blown-out candles lifted prayers and wishes to the tops of Mount Olympus. Another hypothesis as to the origin of birthday candles is rooted in the German practice of placing a candle in the center of bread or cake baked into the likeness of baby Jesus, which symbolized the light of life.

  _Me after I fixed the delete function_

  ![Three teammates celebrating](https://github.com/AshisPatel/Note-Taker-Week-11-Challenge/blob/main/celebration.gif)