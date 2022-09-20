# Assignment 3 & 4: Critique by Design

### Step one: find a data visualization

The goal of this visualization is see if the global number of deaths from outdoor air pollution has increased. If so, by how much? Based on the grey reference line representing parity, we can determine whether the number has increased or declined. Readers can choose between log and linear scatter plots and filter results based on continent.

I think the graph has too many texts in it. Using log to compare difference in numbers did not make sense. It misleads the readers in terms of magnitude of the numbers.

<iframe src="https://ourworldindata.org/grapher/outdoor-pollution-deaths-1990-2017" loading="lazy" style="width: 100%; height: 600px; border: 0px none;"></iframe>

### Step two: critique the data visualization

Describe your overall observations about the data visualization here.  What stood out to you?  What did you find worked really well?  What didn't?  What, if anything, would you do differently?   

Usefulness: The goal of this visualization is see if the global number of deaths from outdoor air pollution has increased. If so, by how much? With the grey reference line representing parity, we can see whether the number has increased or declined easily. 
Completeness: When I hover over the points, detailed information on the specific number of deaths of the country pops up. And I can filter the points based on continents. It shows the comparison clearly.
Perceptibility: The author of this visualization did plot the numbers directly, but the points are all clustered together in the scatter plot (X: linear, Y: linear). The only visualization interpretable is the scatter plot (X: log, Y: log). The readers can see in which countries the number of deaths increased. However, since the goal is to compare the number of deaths, drawing the log loses the contrast between a large number of deaths and a small number. I would use the numbers directly in a bar chart to show contrast between large and small numbers.
Truthfulness: As mentioned above, using the log loses the contrast between a large number of deaths and a small number of deaths. 
Intuitiveness: The points above the gray line are countries in which the number of deaths has increased. The points below are those in which the number has declined. 
Aesthetics: The label texts are a little crowded, covering up the points themselves. I would not have the label texts in the visualization, but as a pop up.
Engagement: It is engaging in that it allows people to filter based on continents and see detailed information when hovering over. 

Who is the primary audience for this tool?  Do you think this visualization is effective for reaching that audience?  Why or why not?

The primary audience for this tool is people who are conducting research on deaths from outdoor air pollution. The visualization is showing in which countries the number has increased. But it's not showing by how much the number has changed accurately. In the log graph, it almost looks like all the countries has a similar number of deaths. In reality, India and China has a much much larger number. It's not effective for people who are studying this problem scientifically.

### Step three: sketch out a solution

Initially, I did not come up with the idea of using a bar chart to draw the difference between the number in 2019 and the number in 1990. So I tested my solution using the scatter plots. I designed the bar chart based on feedback from my audience. In my original sketch, I removed the texts from the dots to make the graph less crowded. I only kept the (X: log, Y: log) scatter plot because the linear scatter plots were not interpretable. 

<div class="flourish-embed flourish-scatter" data-src="visualisation/11194073"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Step four: Test the solution

##### Student, age 23
- Can you tell me what you think this is?
The x-axis is the number of deaths from outdoor air pollution in 1990. The y-axis is 2019. The dots are countries from different continents.

- Can you describe to me what this is telling you?
Given the red line, there is a positive relationship between the number of deaths in 1990 with the number in 2019.

- Is there anything you find surprising or confusing?
The dots were a little confusing. I didn't know they were coutries at first.

- Who do you think is the intended audience for this?
People who study outdoor air pollution deaths.

- Is there anything you would change or do differently?
(I told the student the goal is to see if the global number of deaths from outdoor air pollution has increased.) It would be great to just see the difference directly.

##### Adult, age 50
- Can you tell me what you think this is?
Number of deaths caused by outdoor air pollution in 1990 and 2019.

- Can you describe to me what this is telling you?
There is a positive relationship between the number of deaths in 1990 with the number in 2019.

- Is there anything you find surprising or confusing?
It's a little blank. 

- Who do you think is the intended audience for this?
It's for presentations on this topic. 

- Is there anything you would change or do differently?
(I told the person the goal is to see if the global number of deaths from outdoor air pollution has increased.) There should be explanations on what the dots are.

### Step five: Build your solution

Based on the feedback, using a scatter plot with reference line prompts people to think the goal is to show a positive relationship between the number of deaths in 1990 with the number in 2019. And it would be clearer to just show the difference in numbers direcly. Therefore, I came up with the bar chart. The difference is calculated using the number of deaths in 2019 minus number of deaths in 1990, as indicated by the subtitle. A negative difference means the number declined, and a positive difference means the number increased. Moreover, using the numbers directly instead of log shows the magnitude of numbers correcetly. An improvement I can make with the bar chart is to color the positive and negative numbers using two contrasting colors. I did not figure out how to do this in Flourish,

<div class="flourish-embed flourish-chart" data-src="visualisation/11227678"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


[Return to Homepage](/README.md)
