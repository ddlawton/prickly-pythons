# Thursday, Dec 15 2016, Notes

## Recap of our 6th (and last) meeting this semester!
First of all: scones!

Brent Smith presented part of his code utilizing the subprocess.Call() function to run sextractor and open up ds9 among other things. 
The python code can be found here as a ipython notebook presentation:<br>
https://github.com/prickly-pythons/prickly-pythons/tree/master/code_from_meetings/subprocess <br>
If you have sextractor installed, you can also run the code on your own.

Bhavin Joshi then gave an example of using subprocess.Popen() to call a program writing binary files and then moving those files to another directory from within python. This can also be found here (as subprocess.py):
https://github.com/prickly-pythons/prickly-pythons/tree/master/code_from_meetings/subprocess <br>

Finally, I showed an example of using the multiprocessing module to start several processes at the same time, 
basically adapting your code for running in parallel. 
The code also contains a way to play a sound when the program is done. 
This can be found (and run) here:<br>
https://github.com/prickly-pythons/prickly-pythons/tree/master/code_from_meetings/multiprocessing<br>

As Sean pointed out, it can be a little tricky to figure out how far the code is if running on several cores, but we found this work-around that can basically produce several progress bars:
http://homepages.see.leeds.ac.uk/~eeaol/notes/2013/04/multiprocessing-progress-bars/

See you next year!
