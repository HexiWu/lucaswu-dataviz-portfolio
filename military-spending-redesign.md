# Military Spending Visualization Redesign

## Original Visualization and Rationale for Selection
I selected the Visual Capitalist graphic titled **“Ranked: Top 10 Countries by Military Spending”** because it contains several notable shortcomings.  
The most immediate issue I observed was a mismatch between **numerical values and visual area**. For example, the United States accounts for **37.9%** of global military spending, yet its green sector appears almost the same size as the **Rest of World** segment, which represents only **25.3%**. This misalignment makes the graphic visually misleading.

Additionally, although the underlying dataset spans **1988–2021**, the visualization includes only **2021**, ignoring temporal patterns that could provide more meaningful context.  
The graphic also contains heavy stylized elements—icons, ornaments, textures—that distract from the core data rather than supporting it.

These limitations made the visualization a strong candidate for critique and redesign.

![Picture3](https://github.com/user-attachments/assets/abc97062-149a-49bc-af7f-bf2a069f1047)


---

## Early Design Direction & Feedback from In-Class Critique
For my solution sketch, I chose a **simple descending-order bar chart**.  
Each bar represents a country’s military spending, ordered from highest to lowest so the ranking is immediately clear. This approach prioritizes readability and proportional accuracy, allowing users to interpret the magnitude of spending without distortion.
During the critique session, I received several useful comments:
- **Color differentiation:**  
  My initial color style did not clearly distinguish high-ranking countries from lower ones.
- **Value readability:**  
  Viewers wanted the exact spending amounts displayed directly on the bars rather than requiring hovering.
- **Dynamic title:**  
  The title should update automatically to reflect the selected year.
These insights shaped the improvements in the final redesign.

<img width="468" height="365" alt="Picture2" src="https://github.com/user-attachments/assets/4c154b69-cdb7-4ebb-b77b-a12062fead13" />

---

## Refinements and Final Bar Chart Design
Based on the initial sketch, I implemented several refinements:

- I standardized the color palette using a **blue gradient**, assigning darker shades to the highest-spending countries so viewers can immediately identify the top spender.
- I added **data labels** directly on the bars to make exact values easily readable.
- I incorporated a **year filter**, allowing users to browse the full **1988–2021** dataset and observe how spending patterns shift over time.
- I redesigned the title so that it **updates dynamically** with the selected year.

This redesign offers a much clearer and more flexible way to explore the data than the original static infographic.

<div class='tableauPlaceholder' id='viz1762987248659' style='position: relative'><noscript><a href='#'><img alt='Global Military Spending by Country — 2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MakeoverMonday_17629872332760&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MakeoverMonday_17629872332760&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MakeoverMonday_17629872332760&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1762987248659');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

---

## Adding a Geographic Perspective
As I refined the redesign, I realized that military spending is closely tied to geography.  
To capture this dimension, I added a **map visualization** showing the **top 20 spending countries** for each selected year.

- Each country is shaded using the same **blue color scale**, with darker tones representing higher spending.
- I placed both **country names** and **spending values** directly on the map to maintain clarity.
- This geographic layer reveals **regional clusters and geopolitical patterns**—insights that cannot be observed from the bar chart alone.

Together, the bar chart and the map provide a more comprehensive and contextually grounded view of global military spending.

<div class='tableauPlaceholder' id='viz1762987326161' style='position: relative'><noscript><a href='#'><img alt='Global Military Spending Map (Top 20 Countries)  — 2020 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MakeoverMonday_17629872332760&#47;Sheet12&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MakeoverMonday_17629872332760&#47;Sheet12' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MakeoverMonday_17629872332760&#47;Sheet12&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1762987326161');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

---
