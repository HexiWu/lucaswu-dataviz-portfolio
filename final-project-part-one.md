| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Final Project Part I

## Outline
I fell in love with hiking as an undergraduate and spent weekends chasing dramatic views in mountain parks and nature reserves. When I moved to the U.S. for graduate school, that ritual followed me from trips to Yosemite to quick walks in Frick Park in Pittsburgh. Hiking became my default way to slow down and feel like myself again.

However, I noticed something uncomfortable about my own habits. I pictured myself as the kind of hiker who prefers rugged and scenic trails in my head. In practice, the trails I actually chose were usually the ones that were easiest to reach. I realized that what we think we like and what we actually choose are often shaped by things we don’t notice.

That realization made me wonder: how many other hikers think they are choosing with their hearts, when their feet are really following the most convenient option? National data suggest this is not just a personal quirk. Hiking has exploded since the pandemic—day hiking participation in the U.S. grew by roughly 28% between 2019 and 2023, making it one of the fastest-growing outdoor activities(Outdoor Foundation 2024). Access to safe, nearby nature is not evenly shared. Research on physical activity environments in the U.S. finds that only about one in five homes in low-income neighborhoods has a park within half a mile, and that expanded availability of local recreation spaces is strongly associated with higher physical activity(“Diseases of Poverty” 2023). In other words, being a hiker is much easier if you happen to live near good trails and infrastructure.

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

Visualization 4 compares the reported use of trails and the stated preferences of respondents on a Likert scale for the same types of trails.
<div class="flourish-embed flourish-chart" data-src="visualisation/26294173">
	<script src="https://public.flourish.studio/resources/embed.js">
	</script>
	<noscript>
		<img src="https://public.flourish.studio/visualisation/26294173/thumbnail" width="100%" alt="chart visualization" />
	</noscript>
</div>

Visualization 5 evaluates the  frequency of use of Mountain accessibility infrastructures and means such as cableways, public transportation, parking lots, and car roads.
<div class="flourish-embed flourish-hierarchy" data-src="visualisation/26297209">
	<script src="https://public.flourish.studio/resources/embed.js">
	</script>
	<noscript>
		<img src="https://public.flourish.studio/visualisation/26297209/thumbnail" width="100%" alt="hierarchy visualization" />
	</noscript>
</div>

Visualization 6 illustrates respondents’ perceived importance of various hospitality infrastructures when choosing mountain trails. 
<div class="flourish-embed flourish-chart" data-src="visualisation/26345954"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/26345954/thumbnail" width="100%" alt="chart visualization" /></noscript></div>

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

## AI acknowledgements
Parts of the writing were refined with AI-assisted editing tools to improve phrasing and clarity. 
