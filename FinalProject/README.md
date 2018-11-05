Idea:
- A bank of user uploaded images
	> *Maybe ranked by upvotes
- Within each image:
	> A list of user uploaded captions
	> Ranked by upvotes

User interactions:
1) Upload images
2) Upload captions
3) Upvote on captions
4) Upvote on images
5) View images & captions

Data Model <br/>
The application will store Users (Vote and Upload history), Images, and Image-Captions

Each Image has its own ID (Collision avoiding algorithm needed) </br>
Each Image has its Captions DB </br>

An Example User: </br> <pre>
{
&nbspusername: "usr123",
&nbsphash: ********,
&nbsphistory: [ [Image upload history] [Image voting history] [Caption upload history] [Caption voting history] ]
} </pre>

An Example Image: </br> <pre>
{
name: "FunnyImage",
creatorName: "Jack0245",
score: 3 // # of upvotes
captionsDB: // Captions uploaded by users
} </pre>

An example caption: </br> </pre>
{
	caption: "Gotta miss class because of that"
	captionCreator: "Ruby542"
	score: 5 // # of upvotes
} </pre>

Link to db.js of Schema </br>

Wireframes: </br>
Sample screenshots

Site-map: </br>
Outline of website

Modules for research</br>
- 6 points -> Integrate Facebook Login for the web
- 2 points -> Use Bootstrap CSS

Link to main project file (skeleton app) </br>

References: </br>
Facebook login - https://developers.facebook.com/docs/facebook-login/web#redirecturl </br>
Bootstrap - http://getbootstrap.com/docs/4.1/getting-started/introduction/

