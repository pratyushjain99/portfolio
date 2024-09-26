| [home page](https://pratyushjain99.github.io/portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](Project1) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |
<h1>Playing with data!</h1>

Hi this is me playing with data and trying to make some cool insightful visualisations! 
<h2>Visualization 1: Government Debt as a Percentage of GDP (Bar Chart)</h2>
![Govt debt ratio](viz-gen-govt-debt.png)

**Description:** This bar chart displays government debt as a percentage of GDP for various countries. The chart is from the OECD website using the OECD dataset to highlight how debt ratios have changed over time for specific countries. I downloaded this visualization from the OECD data platform, customized it by selecting the year and countries, and embedded it into my portfolio.

**Key Insights:** The chart helps identify countries with high and low debt-to-GDP ratios. For example, countries like Japan and Italy consistently show high debt levels, while countries like Luxembourg and Korea exhibit relatively low debt-to-GDP ratios. This comparison helps understand economic stability and financial health across nations.

<br>

<h2>Tableau Visualization 2: Heatmap for Govt debt to GDP ratio</h2>


<div class='tableauPlaceholder' id='viz1725995428623' style='position: relative'><noscript><a href='#'><img alt='Govt debt as a percentage of GDP ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;go&#47;govtdebt_17259256607060&#47;GovtdebtasapercentageofGDP&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='govtdebt_17259256607060&#47;GovtdebtasapercentageofGDP' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;go&#47;govtdebt_17259256607060&#47;GovtdebtasapercentageofGDP&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1725995428623');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

**Description:** This heatmap visualizes the change in government debt-to-GDP ratios over time across multiple countries. Each country’s debt is color-coded based on the debt-to-GDP percentage, with blue representing lower values (less than 100%) and orange for higher values (greater than 100%). This color gradient helps in quickly identifying which countries have higher debt levels.

**Key Insights:** Countries like Greece, Japan, and Italy exhibit dark orange, indicating a debt-to-GDP ratio that exceeds 100%, signaling potential financial instability. Conversely, countries like Luxembourg remain in the blue range, indicating better debt management. The heatmap emphasizes the outliers and trends over time, such as how some countries' debt surged after the 2008 financial crisis.



<br>


<h2>My Tableau visualisation for Debt stability analysis</h2>
<div class='tableauPlaceholder' id='viz1726009786345' style='position: relative'><noscript><a href='#'><img alt='Debt stability analysis ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;go&#47;govtdebt_17259256607060&#47;Debtstabilityanalysis&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='govtdebt_17259256607060&#47;Debtstabilityanalysis' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;go&#47;govtdebt_17259256607060&#47;Debtstabilityanalysis&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1726009786345');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>



**Description:** The bar plot visualizes the standard deviation of government debt-to-GDP ratios over time for each country. Countries with a lower standard deviation have more stable debt levels, while countries with a higher standard deviation have experienced more volatility. This visualization allows users to quickly identify which countries have maintained consistent debt management policies and which have seen more fluctuations over the years.

**Why this?** 
This visualization was created to provide insights into the stability of debt levels across countries. While previous visualizations focused on debt levels and changes over time, this analysis goes a step further by examining how consistently countries have managed their debt. Stability in debt levels can indicate stronger financia discipline with policies, while volatility might suggest economic challenges or shifts in policy.

**Insights:**
Countries with low standard deviations (e.g., Norway, COL) are likely to have more stable economic conditions or consistent fiscal policies. On the other hand, countries with high standard deviations (e.g., Greece, Japan) have experienced significant fluctuations, possibly due to economic crises or major policy changes.

**Why I Chose the Colors:** For this visualization, I chose a simple and muted color palette i.e. Grey... Because I felt like there was no useful information which colors can convey. The visualization aims to emphasize the stability and volatility of debt levels across countries, which is well conveyed by the bar graph itself, and the use of bold or vibrant colors would not enhance the core message. Instead, it could introduce unnecessary distractions. Grey is particularly effective in this context because it allows the viewer to focus on the comparative standard deviation values without being overwhelmed by the color itself. The subtle use of grey conveys neutrality, allowing the data to speak for itself.













