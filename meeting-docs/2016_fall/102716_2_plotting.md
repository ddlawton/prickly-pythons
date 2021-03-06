# Thursday, Oct 27 2016, Notes

## Recap of our 3rd meeting this semester!
0. Cookies from sprouts!
This meeting was focused on how to make different types of plots in python and setting the plotting parameters. 
Karen went through examples of the following which can all be found as ipython notebooks or pdf files [here](https://github.com/prickly-pythons/prickly-pythons/tree/master/code_from_meetings/making_plots).
1. Making a simple plot in object-oriented way
2. Adding an extra y-axis to the plot
3. Making subplots (including bar plots and histograms)

Then, Seth talked about the matplotlibrc file which can control your default plot settings. He used a matplotlibrc file from [this github site](https://github.com/spacetelescope/pylunch/tree/master/4-matplotlib). Here are his 3 ways to set the defaults:

1) system wide matplotlibrc file-lives in your installation. Type "find / -name matplotlibrc" in command line to see it.

2) Tell your code to read a specific matplotlibrc file
```
import matplotlib
matplotlib.rc_file("test2.matplotlibrc")
```

3) create a user specific default file
   - in your home directory > mkdir .matplotlib
   - put file called "matplotlibrc" in this directory

Finally, we looked at a cool video that Sean made using [healpy](http://healpy.readthedocs.io/en/latest/index.html) of a satellite mapping the sky.

Remember to put topic request for next meeting in two weeks here: https://github.com/prickly-pythons/prickly-pythons/issues/9

