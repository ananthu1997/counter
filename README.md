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
