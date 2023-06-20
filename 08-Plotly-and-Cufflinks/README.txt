READ ME FIRST BEFORE PLOTLY PLEASE!
PLEASE READ THIS! DON"T SKIP!

Hi Everyone!

There have been some recent updates to Plotly in May of 2020 which I wanted to let you know about! There's over 300,000 students in this course, so a lot of students are still running older versions of our files and libraries, so it makes it hard to strike a balance between new users on the latest updates and the majority of students still on older versions. So we've kept the videos and notebooks to match what "older" students will see, and here are 3 changes you will have to do if you are watching this post May 2020:

1. Possible Import Error 1: You need to install a new package. In your command line type and run:

pip install chart-studio

Then in jupyter make sure you import it by running the code:

import chart_studio.plotly as py


2.Possible Colorscale Error 2: In the "Real Data US Map Choropleth", when you are creating the data dictionary, make sure the colorscale line is = 'ylorbr', not 'YIOrbr'... so like this:

colorscale='ylorbr'


3.Possible projection Error 3: In the "World Map Choropleth", when you are creating the layout, ensure that your projection line is = {'type':'mercator'} not Mercator with a capital...so like this:

projection={'type':'mercator'}


Please search the QA forums before posting a new question on this, as there are already quite a few answered posts.

Thanks!

Jose