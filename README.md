# Hack day at &lt;/salt&gt; - Open Trivia API implementation

This project was created by me in one day at the School of Applied Technology as a part of Hack-day.

## Usage
 Clone the repository and install both the client and the server with npm. Start the application from the root folder by running
* `npm run start-server`
* `npm run start-client`

The client will open up automatically when you run the client script. To play simply choose your level of difficulty, type and category of question and click the button to play.

If the load button never finishes it might mean that the api does not have enough questions for the current difficulty/type/subject, try changing to a broader search.

## Structure
The page is running create react app with a Express backend proxy. The data is fetched from the [Open Trivia Database](https://opentdb.com/).


![menu](menu.png)
![playing](while-playing.png)
