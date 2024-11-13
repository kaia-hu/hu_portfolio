# Assignment 3 & 4: Critique by Design with Tableau (MakeoverMonday)
## My critique chart: https://ourworldindata.org/energy-production-consumption#how-much-energy-does-the-world-consume
![Original_chart](https://github.com/user-attachments/assets/a45c1ad6-c53a-43f6-83b7-58392891eadc)
I am passionate about the energy transition movement and the environmental impact of the energy industry, so I decided to review this visualization which provides a really comprehensive overview of the energy consumption trend globally. This graph does seem a bit crowded at first glance, especially in more recent years. There have been a lot more different types of energy sources in recent years, yet they are not reflected clearly on this chart. I want to make some changes to improve that. <br>
## Part 1: Critique the visualization (Score out of 10)
Usefulness 8 <br>
Completeness 6 <br>
Perceptibility 6 <br>
Truthfulness 8 <br>
Intuitiveness 5 <br>
Aesthetics 8 <br>
Engagement 7 <br>
#### Describe your overall observations about the data visualization here.  What stood out to you?  What did you find worked really well?  What didn't?  What, if anything, would you do differently?   *
This visualization is really rich in information—documenting the global primary energy consumption’s growth from 1800 to present, colored by different energy sources such as coal, oil, solar, etc. Using the four types of visualization in Good Charts, this visualization fits the description of a visual discovery—it is both data-driven and exploratory. Audience can immediately conclude that there was a tremendous growth in energy consumption ever since 1950s, consisting of predominantly growing consumption of coal, oil and natural gas. Overall the data-driven part is done very well: a huge set of data is shown in this chart and the visualization techniques are sufficiently applied to showcase the big dataset well—the coloring of the energy sources works well in helping the audience identify different energy sources, and the line graph delivers a clear picture of the growing trend. The visual exploration aspect is also handled relatively well as this interactive chart allows readers to adjust the year parameter. However, given the sheer size of the data and the various energy sources documented, only changing the year parameter gives little insights into a more detailed comparison of different energy sources, especially the renewable sources that were only developed after around 2000. Moreover, since the scale of renewable energy is much smaller compared to fossil fuels, stacking them together almost makes it impossible to identify their amount. I will add functionality to filter different energy sources so that it is easier to see individual source’s trend more clearly—you can see different renewable energy sources changes in the past 10 years or see the total amount of renewable energy consumption compared to fossil fuel energy sources. 
#### Who is the primary audience for this tool?  Do you think this visualization is effective for reaching that audience?  Why or why not? *
The primary audience for this tool is people who probably work in the energy industry and are interested in looking at the general trends of energy consumption. I think this visualization is effective for reaching that audience, as the audience probably has some existing knowledge of this space and is generally more familiar with different data visualization tools. Therefore, they might be comfortable with looking at a data-rich chart and using the interactive functionalities. 
#### Final thoughts: how successful what this method at evaluating the data visualization you selected? Are there measures you feel are missing or not being captured here?  What would you change?  Provide 1-2 recommendations (color, type of visualization, layout, etc.) *
I think the division of the informative and emotive evaluation is really comprehensive. One additional aspect is whether it directly targets the potential audience. A chart can be highly informative and beautifully made, but if the target audience is not used to reading data visualizations, a much simpler chart may turn out to be much more effective. 
## Part 2: Wireframe a solution
#### Goal: The goal of this initial draft is to make it easier to distinguish the several renewable energy consumption trends from the non-renewable sources, as the latter is significantly higher. I also want to use a color scheme that is more relatable to the energy field.         
<div class='tableauPlaceholder' id='viz1731466023543' style='position: relative'><noscript><a href='#'><img alt='Global primary energy consumption by sourcePrimary energy is based on the substitution method and measured in terawatt-hours. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gl&#47;GlobalPrimaryEnergyConsumptionDraft&#47;Draft&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GlobalPrimaryEnergyConsumptionDraft&#47;Draft' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gl&#47;GlobalPrimaryEnergyConsumptionDraft&#47;Draft&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1731466023543');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Part 3: Test the solution
### Interview 1: Late 20s, Master's Student in Data Analytics, No Prior Energy Experience
<ins> Can you tell me what you think this is? </ins>	 <br>
The title is telling me that this is about the global primary energy consumption. <br>
<ins> Can you describe to me what this is telling you?</ins> <br>
From the title and the legend, it is telling me about the changing trend in the consumption of different energy sources (like how much is coal/gas consumed) <br>
<ins> Is there anything you find surprising or confusing?</ins> <br>
I don't like stacked graphs, it always makes me really confused about reading individual categories' change over time.
Some wording in the title and subtitle is confusing, what are "primary" and "substitution" <br>
The title is really general yet the graph has a lot of information. I think I will be less lost if the title provides me with a story.<br>
<ins> (I pointed out the legend and interactive panel on the right) What do you think of the interactive features? </ins> <br>
Oh I didn't even know that this is interactive. The interactive feature is nice. However, they still don't provide enough guidance for me to find a particular story. <br>
<ins> Who do you think is the intended audience for this?</ins> <br>
Anyone curious about the topic of energy consumption. I don't think the audience is only someone who is in the energy field.<br>
<ins>We then started a discussion about the purpose of this graph. </ins> I explained that this is a data-driven and exploratory visualization that aims at helping the reader to extract interesting findings, instead of having embedded information beforehand. The interviewee said: "That makes a lot of sense now." I then showed them the original article in which this visual was posted, they read the paragraph and indicated that using the paragraph title "How much energy does the world consume?" can make the goal clearer to the audience. "However it is possible that the reason that I was confused was that I didn't know any context before; reading the article and then see this chart makes a lot more sense", they said.<br>
<ins>Is there anything you would change or do differently?</ins> <br>
Sort the stacked areas, make the sorting more meaningful. (For example, having the energy source that has been consumed the most on the bottom.) <br>
Change the title, make it easier to understand; it has to give the audience an initial target to seek in the chart.  <br>
### Interview 2: LATE 20s, PhD Student in Biology, No Prior Data or Energy Experience
<ins> Can you tell me what you think this is? </ins>	 <br>
The title is telling me that this is about the global primary energy consumption. <br>
<ins> Can you describe to me what this is telling you?</ins> <br>
Our energy consumption is increasing exponentially and it's highly dependent on carbon reserves <br>
Our energy consumption sources are getting more diverse <br>
<ins> I then went through the article content of this chart and demonstrated the interactive functionality of this chart </ins> <br>
<ins> Is there anything you find surprising or confusing?</ins> <br>
Surprising:<br>
fossil fuel rise and fall with administration <br>
based on the trend of renewables, they seem that they have a lot of space to grow  <br>
Confusing:<br>
I don't know what traditional biomass is <br>
the unit of calculation is not listed on the y-axis <br>
"substitution method" <br>
I also don't know what "terawatt hours" is <br>
<ins> Who do you think is the intended audience for this? </ins> <br>
I think this is for all people interested in climate policy and energy trends. <br>
It's for both people with expertise to extract key ideas, but also accessible for people who have no prior knowledge to get a basic trend  <br>
<ins> Who do you think is the intended audience for this?</ins> <br>
Anyone curious about the topic of energy consumption. I don't think the audience is only someone who is in the energy field.<br>
<ins>Is there anything you would change or do differently?</ins> <br>
Make the legend simpler by putting TWh in the y-axis instead of putting them for every source in the legend <br>
<ins> What do you think of the changed color theme in this draft? </ins><br>
I like it, it's straightforward. Maybe there are too many shades of light blue. You can look at more distinguishable colors.
### In-class Critique
<ins> What worked? </ins>	 <br>
The color makes sense; the correlation between the type of energy and the color can help the audience utilize their common sense in reading the colors (grey--nonrenewable)<br>
The stacked graph makes sense; it not only shows the total trend in energy consumption but you can also generally tell the composition in consumption. <br>
It clearly shows that the trend started changing drastically around the 60s. <br>
<ins>What didn't work </ins>	 <br>
The unit is not clear <br>
<ins>I brought up that since this is a highly exploratory data-driven chart, I couldn't tell a story from this </ins>	 <br>
Someone brought up maybe I could add in some data on climate change to see if the change in energy consumption patterns correlates with climate change. <br>

## Part 4: Build the solution
After getting the feedback from my reviewers, I first decided to brainstorm on the main story that I wanted to deliver through my chart. The in-class critique gave me a new idea so I found some data on global greenhouse gas emissions from 1850 to now. I overlaid this data on top of my chart, and I found the trend of both surprisingly matching each other. To make the story more clear, I decided to filter out renewable energy consumption since they only took off around 2000s and their volume is tiny relative to that of the nonrenewable energy consumption. This made the graph a lot clearer in its story on how the rise in greenhouse gas emissions is closely in step with global fossil fuel consumption. <br> 
I then cleaned up the axes so that both axes included the measuring unit of the data. And I also modified the chart title to deliver the main story more efficiently. I also added the time scale of the data as well as the data source in the subtitle to add more credibility and details. <br>
One thing that I wasn't able to do was adding footnotes to explain the calculation methods. Since many reviewers reflected that they didn't know what the "substitution method" meant, adding this information in the footnote can help the audience understand the chart better. However, I did remove those terms from the chart title so that there will not be immediate confusion when the reader first looks at this chart. <br>

<div class='tableauPlaceholder' id='viz1731468719120' style='position: relative'><noscript><a href='#'><img alt='Greenhouse Gas Emissions Rising in Step with Global Fossil Fuel DemandFrom 1900 to 2020 | Source: Our World in Data  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gl&#47;GlobalPrimaryEnergyConsumptionRefinedVersion&#47;RefinedVersion&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GlobalPrimaryEnergyConsumptionRefinedVersion&#47;RefinedVersion' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gl&#47;GlobalPrimaryEnergyConsumptionRefinedVersion&#47;RefinedVersion&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>              
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1731468719120');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
