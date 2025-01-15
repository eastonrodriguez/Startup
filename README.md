# Startup
## Elevator Pitch
Before I was a Cybersecurity major I was actually a Wildlife Conservation major. I have always been fascinated by God's creations and love learning about obscure species all across the world. So it seemed like a fun idea for me to share that interest with the rest of the class! I'll pick a dozen or so animals that are relatively unknown and I will put their picture up on my website. Underneath the picture will be multiple questions from a to d that will have possible names of that species. After they pic one of the 4 buttons the correct name will pop up with a few fun facts, perhads the audio of what the creature sounds like, and a link to another website for more info. After the quiz is complete the website will tell them what there score was and give them the option to either play again or sign out (of course they will have gone through an authenticaion process of signing up and then signing in before they start the quiz). I think this will be adequately challenging for me while also being enjoyable and educational for the rest of the class.
## html
This startup will have plenty of html to go through since much of the setup has its foundations in html. For each question there will be an image of the animal which will be uploaded by html using the <img> element in the code, the four possibly answers will all be connected to their own buttons through the <button> tag, and of course all of the needed text for the website will be written inside html as well.
## CSS
CSS will be very important for this website as it is for any website. I want the layout of the website to look professional with specific fonts and coloring and most importantly I want to make sure that students that access the website either on their phones or on there labtops will be able to use the website the same because it is well adjusted to different screen sizes. This will all be accomplished through CSS
## React
For React the most important thing that will be used for this website is changing the display of the login form to the quiz form after successfully loging in. It will also be important for keeping track of the score of all the people who play. This quiz will work similar to a kahoot quiz where it will not only show you your own score but also how your score relates to everyone else you has taken the quiz. After every question is asked it will tell the user not only whether they got it right or not but also what percentage of other people got that particular question correct and at the end it will tell you your final scrore as well what percintile you where in. In order to do this I will need to make sure that the user interfaces (UI's) will be used in small components so the whole website will run more smoothly which will be accomplished by using React.
## Web Services
As stated previosly the website will be keeping track of all the sepreate users votes and their seperate accounts. In order to do this the website will need to a server with endpoints for submitting votes and also retrieving vote status for each user.
## Authentication
I will have an authentication process for each user which is expected for the startup. It will have the options of sign in or sign up when the user first enters the website and then after the student has finished the quiz he will log out which will return him to the authentication page. Only registered users will be ablt to take the quiz and the users username will be displayed after they have signed in.
## Database data
The autherized users accounts and the answers they give will all be stored in a database
## WebSocket data
As stated previously after the user answers are given it will be broadcast on the screen how many other users got that question wrong which is data recieved from the server
## Rough Scetch
![Screenshot 2025-01-14 192909](https://github.com/user-attachments/assets/73ac6868-c7ab-4a12-a409-bbf4878a7463)
)
