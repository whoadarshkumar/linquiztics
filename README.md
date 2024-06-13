# Linquiztics
![badge][badge-html5]
![badge][badge-bootstrap]
![badge][badge-js]
![badge][badge-jquery]
![badge][badge-mongodb]
![badge][badge-express]
![badge][badge-nodejs]

Linquiztics &mdash; a play on <i>linguistics</i> and <i>quiz</i> &mdash; is a language learning web application that allows users to create their own quizzes and to answer those made by the community of users. It also features incentivization dynamics designed to gamify learning through customized quiz suggestions, experience points, streaks, leagues, and a global leaderboard. 

***Kindly enter a valid email address during the creation of an account. The web application will send an email to this registered email address after the account has been created and in the event of a password change.***

This project consists of the following folders:

| Folder | Description |
| --- | --- |
| <a href = "https://github.com/memgonzales/linquiztics/tree/master/controllers"><code>controllers</code></a> | Contains the JavaScript files that define callback functions for client-side requests |
| <a href = "https://github.com/memgonzales/linquiztics/tree/master/helpers"><code>helpers</code> | Contains the JavaScript files that define helper functions for front-end display and server-side validation | 
| <a href = "https://github.com/memgonzales/linquiztics/tree/master/misc"><code>misc</code></a> | Contains the JavaScript files for initial database population |
| <a href = "https://github.com/memgonzales/linquiztics/tree/master/models"><code>models</code></a> | Contains the JavaScript files for database modeling and access | 
| <a href = "https://github.com/memgonzales/linquiztics/tree/master/public"><code>public</code></a> | Contains the static CSS and JavaScript files, as well as the project assets (images and audio files), for front-end display |
| <a href = "https://github.com/memgonzales/linquiztics/tree/master/routes"><code>routes</code></a> | Contains the JavaScript file that defines the server response to each HTTP method request |
| <a href = "https://github.com/memgonzales/linquiztics/tree/master/views"><code>views</code></a> | Contains the Handlebars template files to be rendered and displayed upon request |

It also includes the following files:

| File | Description |
| --- | --- |
| <a href = "https://github.com/memgonzales/linquiztics/blob/master/package-lock.json"><code>package-lock.json</code></a> and <a href = "https://github.com/memgonzales/linquiztics/blob/master/package.json"><code>package.json</code></a> | Store information on the project dependencies |
| <a href = "https://github.com/memgonzales/linquiztics/blob/master/index.js"><code>index.js</code></a> | Entry point of the web application |

The complete project specifications can be found in the file <a href = "https://github.com/memgonzales/linquiztics/blob/master/Proposed%20Specifications.pdf"><code>Proposed Specifications.pdf</code></a>.

## Running the Application
### Running on the Web
Open the following website: 


### Administrator Credentials  
To log in as an administrator, go to the <a href = "https://linquiztics.up.railway.app/login">Login</a> page and enter the following credentials:
   - Username: <code>linquizticsadmin</code>
   - Password: <code>ASDFGHJKL123;</code>
   
### Login Credentials (For Testing)
To test the features of a (non-administrator) user account, it is recommended to log in using the following credentials:
   - Username: <code>gianinayuchengco</code>
   - Password: <code>ASDFGHJKL123;</code>
   
Note that there are 23 pre-registered user accounts; the usernames are found in the file <a href = "https://github.com/whoadarshkumar/linquiztics/blob/master/misc/add_profile_data.js"><code>misc/add_profile_data.js</code></a>. The password to all these accounts is <code>ASDFGHJKL123;</code>. (The period is not included.)


## Built Using
This project follows the Model-View-Controller (MVC) architectural pattern:
- **Model:** <a href = "https://www.mongodb.com/">MongoDB</a> as the database program and <a href = "https://mongoosejs.com/">Mongoose</a> as the object data modeling tool
- **View:** <a href = "https://handlebarsjs.com/">Handlebars</a> as the template engine
- **Controller:** <a href = "https://nodejs.org/en/">Node.js</a> as the server environment

This web application is deployed on the cloud platform <a href = "https://dashboard.heroku.com/">Heroku</a>. Since Heroku has an ephemeral filesystem, <a href = "https://docs.mongodb.com/manual/core/gridfs/">GridFS</a> is used for the persistent storage of image and audio files.


[badge-html5]: https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white
[badge-bootstrap]: https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=flat&logo=bootstrap&logoColor=white
[badge-js]: https://img.shields.io/badge/javascript-%23323330.svg?style=flate&logo=javascript&logoColor=%23F7DF1E
[badge-jquery]: https://img.shields.io/badge/jquery-%230769AD.svg?style=flat&logo=jquery&logoColor=white
[badge-mongodb]: https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat&logo=mongodb&logoColor=white
[badge-express]: https://img.shields.io/badge/express.js-%23404d59.svg?style=flat&logo=express&logoColor=%2361DAFB
[badge-nodejs]: https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white
[badge-mocha]: https://img.shields.io/badge/-mocha-%238D6748?style=flat&logo=mocha&logoColor=white
[badge-heroku]: https://img.shields.io/badge/Heroku-430098?style=flat&logo=heroku&logoColor=white
