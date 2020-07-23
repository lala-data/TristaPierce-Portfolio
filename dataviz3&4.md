# Critique By Design 


## Original Data Visualization

<img src="ogdataviz.png" width="800"/>
Source: [PA Health](https://www.health.pa.gov/topics/disease/coronavirus/Pages/Cases.aspx)


With the second spike of COVID-19 cases sweeping the nation, I wanted to research PA cases. 
I found this visualization which explains the cases reported by day for each region. 
I believe the information on the current graph is valuable, but there was a lot of room for improvement. 

Using  Stephen Few's Data Visualization Effectiveness critique method, I saw that the current format of the visualization was not complete. 
The regions are not specified, and a cumulative case amount was not displayed. Also, the data of regions with low numbers was not easily readable. 


## The Process of Design 
First, I sketched a redesign on paper and submitted it to three individuals for feedback. 

<img src="sketch.png" width="800"/>

I chose a stacked bar graph to capture not only individual region case numbers but also state wide cumulative amounts. 
I also created a color-code map of the regions, vice just a color legend. 
This allows for even more information, because the audience might not be familiar with or be able to visualize each region. 
During my sketch, I knew I would have to case my x-axis wisely, and my color scheme appropriately to fit both the graph and the map. 
The feedback I received but that the bars in the graph were not easily differentiable, this level to me stacking them differently.


## Final Product

<div class='tableauPlaceholder' id='viz1595533457307' style='position: relative'>
<noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;PA&#47;PACOVID&#47;Dashboard&#47;1_rss.png' style='border: none' /></a>
</noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
<param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='PACOVID&#47;Dashboard' /> <param name='tabs' value='no' /><param name='toolbar' value='yes' />
<param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;PA&#47;PACOVID&#47;Dashboard&#47;1.png' />
<param name='animate_transition' value='yes' /> <param name='display_static_image' value='yes' /> <param name='display_spinner' value='yes' /> <param name='display_overlay' value='yes' />
<param name='display_count' value='yes' /> <param name='language' value='en' /> <param name='filter' value='publish=yes' /></object></div> 
<script type='text/javascript'> var divElement = document.getElementById('viz1595533457307'); var vizElement = divElement.getElementsByTagName('object')[0];
if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
else { vizElement.style.width='100%';vizElement.style.height='727px';} var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>
