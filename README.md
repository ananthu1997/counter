# QT-QML Assignment
Ananthu S Ajayan
24275
# counter
This is the code for the Counter logic.I have implemented using the thread functionality.
Here we have implemented three buttons for start,stop and restart.
when thu user clicks the start button,thread will start the counter from value zero and iterate to 
the value given inside the run function.
Thread have overide function run,Which will be running when thread->start is called inside the program
If the user clicks the stop button,the counter will stop the count at that value.So for the stop button we have declared 
two variables stop and stopped as true.Whenever again start button is operated,the run function will check if stopped is 
true,then it will start the counter from the value we have stopped earlier.
For the restart button,we will keep the stop variable as false and make the iterated value as 0 and also call 
thread->start from the restart button.Then the counter will again start from 0.
This is how the counter logic works.
The reason for implementing this code is that it was executing by use of thread.So there was a proper 
organization for the code while implementing these start,stop and restart button

# qmllanguage
This is the code for translation from one langauge to other language.Here we have given a combo box of 
four languages which consist of hindi,malayalam,kannada and english.
So when we select each option coressponding english translation will be converted to other language translation.
So for implementing translation for each language,first we have to create a ts file inside the project definition.
After that we perform a lupdate translation to the project file,then open linguist and open the ts file inside the linguist.
Then do the corresponding translation for each word inside that,After performing that we release the translation.
Then the corresponding qml file will be generated for that language.
The reason for implementing this code,it supports translation from one to another language using the lupdate and lrelease translation.
So its easier to do the translation by using the ql-qml.

# property_binding
This is the code for signal-slot propert binding,where there are two buttons like sender and reciever.When we click on sender button it sends
a signal to the reciever , and inside the reciever we will increment the count and also we are providing an animation
inside the reciever button.We are also providing animation at the sender button.So each time when button is clicked the animation 
is also changing corespondingly.
The reason for implementing this code is to understand the working of signal-slot and also implement the sequential animation
to the code.
