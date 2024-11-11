# Assignment 3 & 4: Critique by Design with Tableau (MakeoverMonday)
## My critique chart: https://ourworldindata.org/energy-production-consumption#how-much-energy-does-the-world-consume
![Original_chart](https://github.com/user-attachments/assets/a45c1ad6-c53a-43f6-83b7-58392891eadc)

## Part 1: Critique the visualization (Score out of 10)
- Usefulness 8
- Completeness 6
- Perceptibility 6
- Truthfulness 8
- Intuitiveness 5
- Aesthetics 8
- Engagement 7
#### Describe your overall observations about the data visualization here.  What stood out to you?  What did you find worked really well?  What didn't?  What, if anything, would you do differently?   *
This visualization is really rich in information—documenting the global primary energy consumption’s growth from 1800 to present, colored by different energy sources such as coal, oil, solar, etc. Using the four types of visualization in Good Charts, this visualization fits the description of a visual discovery—it is both data-driven and exploratory. Audience can immediately conclude that there was a tremendous growth in energy consumption ever since 1950s, consisting of predominantly growing consumption of coal, oil and natural gas. Overall the data-driven part is done very well: a huge set of data is shown in this chart and the visualization techniques are sufficiently applied to showcase the big dataset well—the coloring of the energy sources works well in helping the audience identify different energy sources, and the line graph delivers a clear picture of the growing trend. The visual exploration aspect is also handled relatively well as this interactive chart allows readers to adjust the year parameter. However, given the sheer size of the data and the various energy sources documented, only changing the year parameter gives little insights into a more detailed comparison of different energy sources, especially the renewable sources that were only developed after around 2000. Moreover, since the scale of renewable energy is much smaller compared to fossil fuels, stacking them together almost makes it impossible to identify their amount. I will add functionality to filter different energy sources so that it is easier to see individual source’s trend more clearly—you can see different renewable energy sources’ changes in the past 10 years or see the total amount of renewable energy consumption compared to fossil fuel energy sources. 
#### Who is the primary audience for this tool?  Do you think this visualization is effective for reaching that audience?  Why or why not? *
The primary audience for this tool is people who probably work in the energy industry and are interested in looking at the general trends of energy consumption. I think this visualization is effective for reaching that audience, as the audience probably has some existing knowledge of this space and is generally more familiar with different data visualization tools. Therefore, they might be comfortable with looking at a data-rich chart and using the interactive functionalities. 
#### Final thoughts: how successful what this method at evaluating the data visualization you selected? Are there measures you feel are missing or not being captured here?  What would you change?  Provide 1-2 recommendations (color, type of visualization, layout, etc.) *
I think the division of the informative and emotive evaluation is really comprehensive. One additional aspect is whether it directly targets the potential audience. A chart can be highly informative and beautifully made, but if the target audience is not used to reading data visualizations, a much simpler chart may turn out to be much more effective. 
('---')
## Part 2: Wireframe a solution
#### Goal: The goal of this initial draft is to make it easier to distinguish the several renewable energy consumption trends from the non-renewable sources, as the latter is significantly higher. I also want to use a color scheme that is more relatable to the energy field. 
<div class='tableauPlaceholder' id='viz1731368144091' style='position: relative'><noscript><a href='#'><img alt='Global primary energy consumption by sourcePrimary energy is based on the substitution method and measured in terawatt-hours. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gl&#47;GlobalPrimaryEnergyConsumptionDraft&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GlobalPrimaryEnergyConsumptionDraft&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gl&#47;GlobalPrimaryEnergyConsumptionDraft&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1731368144091');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

('---')
## Part 3: Test the solution
### Interview 1: Late 20s, Master's Student in Data Analytics, No Prior Energy Experience

### Interview 2: LATE 20s, PhD Student in Biology, No Prior Data or Energy Experience

('---')
## Part 4: Build the solution