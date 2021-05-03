# basketball_analyzing
This is a data science project about analyzing some activities in basketball game.
Source:
UCI: https://archive.ics.uci.edu/ml/datasets/Basketball+dataset#
4 students from Universidad de los andes, for which they prefer to be Anonymous.


Data Set Information:

There are different trials. For which, pass, shoot and pick up the ball have 5. and hold and dribble there are 2.
First of all, we gathered the 4 users who were willing to be our test samples.
Then, one by one we made them do the following 5 activities: Pass, hold the ball, shoot pick up the ball, and dribble.
Each activity had a different way of gathering its corresponding data.

For holding the ball, we made the volunteer stand in one place in a holding position.
Once ready, we run the app. After 5 seconds we stop it and save the data with the userâ€™s first initial,
the activity and the number of the trial. For this label we did a total of 3 trials for each person.

Next we started collecting the data of passing. The volunteer starts with the ball in a holding position.
Next we run the app, for which after 3 seconds we tell the volunteer to pass the ball to one of us, once
finish we stop the app. For this label we did a total of 5 trails for each person.

Then, we collected the data of dribbling. The volunteers start with the ball in holding position. Then, 3 seconds
after we run the app we tell him to dribble and after 5 he started the dribbling we said to stop.
Once he stops we go and stop the app. For this label we did a total of 3 trials for each person.

Continuing with the activity of shooting, we let the volunteer get ready in a holding position with the ball, and
then we run the app. For which, he shoots immediately after we start the application. Once finish, we stop the app.
For this label we did a total of 5 trials for each person.

Finally, we gather the data of picking the ball. For this data, we just start the app,
and after 3 seconds the user picks up the ball, and at the 6 seconds we stop the app gathering this range of data.
For this label we did a total of 5 trails for each person.

Finally we did a different way of collecting the data. For which one user in a set of time did each activity spontanously. Every time he did an activity we
collected the time for which he did it in a chronometer, and in a video all for which started closely at the same time.


Attribute Information:

we use acceloremeter measures x y z in ms2 and gyroscope measures r phi theta. for X the data is in g
