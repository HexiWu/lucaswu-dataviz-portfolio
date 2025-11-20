| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Final Project Part I

## Outline
I fell in love with hiking as an undergraduate and spent weekends chasing dramatic views in mountain parks and nature reserves. When I moved to the U.S. for graduate school, that ritual followed me from trips to Yosemite to quick walks in Frick Park in Pittsburgh. Hiking became my default way to slow down and feel like myself again.

However, I noticed something uncomfortable about my own habits. I pictured myself as the kind of hiker who prefers rugged and scenic trails in my head. In practice, the trails I actually chose were usually the ones that were easiest to reach. I realized that what we think we like and what we actually choose are often shaped by things we don’t notice.

That realization made me wonder: how many other hikers think they are choosing with their hearts, when their feet are really just following convenience? National data show that this pattern is common. Many outdoor participants say they enjoy challenging or remote environments, but their actual behavior is strongly influenced by proximity and ease of access—people are far more likely to visit places that require less travel time and simpler logistics (Outdoor Foundation 2024). In other words, convenience quietly shapes outdoor choices more than most of us admit.

To explore this tension between what hikers say they want and what their environments make easy, I turn to two complementary public datasets. The U.S. Forest Service’s National Visitor Use Monitoring (NVUM) program provides nationally representative surveys of visitors to national forests, including their activities, demographics, trail types, amenities used, and trip characteristics. The National Park Service’s Visitor Facilities open data portal adds facility information about trailheads, parking, lodges, restrooms, and other infrastructure. These datasets let me move from my anecdote to a broader question:

When hikers choose a trail, how much of that choice is about preference and how much is about access and infrastructure being in the right place?

## Project Structure
I plan to organize my final project into four sections.

### What We Think We Want vs. What We Actually Choose
I will compare stated trail preferences with reported trail use from the NVUM dataset. This helps me show the tension between our ideal image of hiking and our everyday behavior shaped by convenience.

### Who Gets to the Trail 
I want to explore how hikers physically get to the trail. The NVUM dataset includes the use of parking lots, public transportation, car roads, cableways, and other infrastructure. I plan to visualize these patterns to show how much trail access depends on what kinds of infrastructure exist around parks.

### Trail Hospitality
Finally, I will focus on hospitality infrastructure. This includes huts, B&Bs, restrooms, lodges, agritourism sites, and other facilities around trails. I want to show how hikers make their trail choices based on the availability of these facilities using NPS datasets.

### Call to action
My call to action is twofold.

For individual hikers, I hope we can pause and make one intentional choice. The next time you look for a trail, don’t just pick the easiest one. Choose one trail that inspires you and lets you see something new. A single choice driven by genuine preference can bring us closer to the version of outdoor life we imagine for ourselves.

For land managers and planners, I hope that people designing parks and trails take seriously how much access shapes behavior. When good facilities are available, more people show up. By investing in infrastructure that lowers barriers, planners can make outdoor recreation possible for more people.

## Initial sketches
Visualizations 1, 2 & 3 paint a clear demographic portrait of hikers, showing how gender, employment, and age patterns shape the outdoor recreation community.
<div class="flourish-embed flourish-chart" data-src="visualisation/26296069"><script src="https://public.flourish.studio/resources/embed.js"></script>
	<noscript>
		<img src="https://public.flourish.studio/visualisation/26296069/thumbnail" width="100%" alt="chart visualization" />
	</noscript>
</div>
<div class="flourish-embed flourish-chart" data-src="visualisation/26297092">
	<script src="https://public.flourish.studio/resources/embed.js">
	</script>
	<noscript>
		<img src="https://public.flourish.studio/visualisation/26297092/thumbnail" width="100%" alt="chart visualization" />
	</noscript>
</div>
<div class="flourish-embed flourish-chart" data-src="visualisation/26296992">
	<script src="https://public.flourish.studio/resources/embed.js">
	</script>
	<noscript>
		<img src="https://public.flourish.studio/visualisation/26296992/thumbnail" width="100%" alt="chart visualization" />
	</noscript>
</div>

Visualization 4 compares the reported use of trails and the stated preferences of hikers for the same types of trails.
<div class="flourish-embed flourish-chart" data-src="visualisation/26294173"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/26294173/thumbnail" width="100%" alt="chart visualization" /></noscript></div>

Visualization 5 evaluates the  frequency of use of Mountain accessibility infrastructures.
<div class='tableauPlaceholder' id='viz1763603030419' style='position: relative'><noscript><a href='#'><img alt='Frequency use of Mountain accessibility infrastructures ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Infrastructures_17636029722270&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Infrastructures_17636029722270&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Infrastructures_17636029722270&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
	var divElement = document.getElementById('viz1763603030419');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Visualization 6 illustrates which kinds of hospitality facilities hikers actually choose. 
<div class="flourish-embed flourish-chart" data-src="visualisation/26345954">
	<script src="https://public.flourish.studio/resources/embed.js">
	</script>
	<noscript>
		<img src="https://public.flourish.studio/visualisation/26345954/thumbnail" width="100%" alt="chart visualization" />
	</noscript>
</div>

# The data
My primary dataset is the U.S. Forest Service  National Visitor Use Monitoring ([NVUM](https://www.fs.usda.gov/recreation/programs/nvum/)) dataset, which contains survey data on visitor trail use patterns and preferences for infrastructure. These data allow me to paint a clear demographic portrait of hikers, compare stated versus reported travel preferences, and evaluate the frequency of use of accessibility infrastructures.
To analyze the perceived importance of hospitality services, I also incorporate facility-level information from the National Park Service (NPS) Visitor Facilities open-data portal([NPS](https://public-nps.opendata.arcgis.com/search?q=Facilities)). 

# Method and medium
To complete this final project, I plan to use Shorthand to build the presentation and integrate interactive visual storytelling. All visualizations will be created using Flourish and Tableau. I initially hoped to include a dataset linking hikers’ path choices with geographic trail locations, but I was unable to find a publicly accessible dataset that provides spatial information and preference attributes. If I locate a suitable dataset later in the process, I may incorporate it into the final story.

## References
•	U.S. Forest Service. National Visitor Use Monitoring (NVUM) Program. Retrieved from
	https://www.fs.usda.gov/recreation/programs/nvum/  
•	National Park Service. NPS Visitor Use Statistics & Facilities Open Data Portal. Retrieved from
	https://public-nps.opendata.arcgis.com/	  
• 	Outdoor Foundation. 2024. 2024 Outdoor Participation Trends Report. Boulder, CO: Outdoor Industry Association.  

## AI acknowledgements
Parts of the writing were refined with AI-assisted editing tools to improve phrasing and clarity. 
