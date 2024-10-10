| [home page](https://pratyushjain99.github.io/portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](Project1) | [final project II](Project2) | [final project III](Project3) |

# The final data story
> Have a look at my visualisation [here](https://public.tableau.com/views/SubscriptionServices/Insights), and the data can be found [here](https://www.kaggle.com/datasets/safrin03/predictive-analytics-for-customer-churn-dataset).

The story goes like this (try toggling and following yourself):

<div class='tableauPlaceholder' id='viz1728538665522' style='position: relative'><noscript><a href='#'><img alt='Content That Drives Revenue: Insights for CXOs and Producers ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Su&#47;SubscriptionServices&#47;Insights&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SubscriptionServices&#47;Insights' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Su&#47;SubscriptionServices&#47;Insights&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1728538665522');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='1016px';vizElement.style.height='1043px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


# Changes made since Part II

Since Part II, I made some key changes based on feedback and additional insights I got from interviews. In particular, I fine-tuned both dashboards to better align with their personas!<br>

### C-suite dashboard
I ensured the focus was on the growth and money i.e. revenue. I revised the Customer Lifetime Value (CLTV) visualization and made it clearer, highlighting actionable insights for the CEO. I also updated the Revenue by Genre chart to better reflect which genres drive the most revenue, simplifying the pie chart segmentation to provide a quicker, clearer overview of customer segments. Previously the revenue tree had green-red hue highlights, where green depicted the genres you should put more money in, but from Professor's feedback, it was unclear for the audience. I further matched it to other slides. Although the professor's feedback said pie chart maybe not what gos there. But, I believe from previous internship experience, that a C-suite employee would definitely want to seethe pie of subscriber base.<br><br>
Try it yourself:
<div class='tableauPlaceholder' id='viz1728540920816' style='position: relative'><noscript><a href='#'><img alt='Admin Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Su&#47;SubscriptionServices-Admin&#47;AdminDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SubscriptionServices-Admin&#47;AdminDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Su&#47;SubscriptionServices-Admin&#47;AdminDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1728540920816');
  var vizElement = divElement.getElementsByTagName('object')[0];
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1227px';}
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

### Producer/Director dashboard
Based on feedback, I replaced the "Viewership vs Revenue" chart with a more detailed scatter plot that shows how engagement correlates with revenue generation. It also conveys that, based on our data, there is ABSOLUTELY no correlation between what people prefer to watch and what brings most revenue. I also added the "Genre Trend in New Customers" chart to show how content preferences are evolving in newer customers, providing insights for future content production. Apart from generating more revenue, a producer should be careful about what new customers are watching! Moreover, the best part is for a director. Since most directors mostly work with a specific genre (like Speilberg, Nolan with Sci-Fi ; James Cameron for Action, etc), they can specifically select a genre from the legend, and it would highlight that genre across all graphs!<br><br>
Try it yourself:
<div class='tableauPlaceholder' id='viz1728540961212' style='position: relative'><noscript><a href='#'><img alt='Producer dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Su&#47;SubscriptionServices-Prod&#47;Producerdashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SubscriptionServices-Prod&#47;Producerdashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Su&#47;SubscriptionServices-Prod&#47;Producerdashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1728540961212');
  var vizElement = divElement.getElementsByTagName('object')[0];
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1527px';}
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script><br>


## The audience
For my final data story, I focused on two distinct audiences, tailoring the dashboards to address their unique needs and priorities. Imagine yourself in their shoes while operating the dashboard.

### C-suite (CEO, CFO)
As a CEO or CFO of a subscription service, the primary concern is profit maximization. You’re already familiar with the financial ins and outs, understanding how different customer segments like Basic, Standard, and Premium contribute to the company’s revenue. You’re constantly thinking about where to allocate your budget—should more go into marketing to attract new customers? into producing original content that will retain high-value subscribers? or both?<br>

You know how much each subscriber is worth through metrics like Customer Lifetime Value (CLTV), and you're focused on retaining those high-value customers. What matters most to you is figuring out which genres are generating the most revenue and whether your content investments align with what your audience wants. This dashboard is designed to give you a quick, actionable insight into how genres are performing and where to best utilise your resources to maximize profitability.
<br>
##### Call to Action: Focus on retaining premium subscribers and increasing revenue by investing in high-performing genres like Comedy and Drama, while also exploring underutilized genres like Sci-Fi and Fantasy for future growth opportunities.

### Content Producer/Director
On the other side, imagine you’re a Producer or Director tasked with creating content for a streaming platform. The goal is to engage your audience while managing production costs. You know that producing certain genres,like Sci-Fi or Action, can be expensive, but these genres often deliver higher engagement. The challenge is striking the right balance between the cost of production and the content’s ability to attract and retain viewers.<br>

You also have a deep understanding of your audience’s preferences. You know that different segments of your audience gravitate toward different genres, and your job is to create or acquire content that aligns with those preferences. This dashboard helps you see which genres resonate most with your audience and how you can adjust your investments to keep viewers engaged while staying within budget.<br>

##### Call to Action: Invest in genres with strong engagement among premium subscribers, like Action and Drama, but remain mindful of production costs. Additionally, pay close attention to what new subscribers are watching, as this can guide future content decisions.
These personas helped guide the overall structure and design of my dashboards, ensuring the data is presented in a way that’s relevant, easy to understand, and actionable for both decision-makers and content creators.

## Final design decisions
Other than the changes I have already mentioned above, I have made some general modifications:<br>

1. Color scheme: I changed the color palette from the initial version to a more neutral and consistent scheme that avoids unnecessary distraction. The use of red and green was reduced to avoid any bias or confusion. For example, I switched the Customer Lifetime Value (CLTV) chart to greyscale to better highlight the different ranges of customer value without the distraction of color. I also got rid of red-green in revenue treemap by switching to the matching color to deliver consistency! <br>
2. Chart selection: Based on user feedback, I removed unnecessary visualizations that were cluttering the dashboard, such as the multi-device access chart and the engagement heatmap, which were not providing meaningful insights. I replaced them with a scatter plot that links viewership to revenue.<br>
3. Interactive Filters: To make the dashboards more dynamic and interactive , I added filters for genres, allowing the user to drill down into specific genres if they want to focus on a particular type of content esp. for genre-specific director(e.g., Action or Comedy).<br>

## References
Have a look at my visualisation [here](https://public.tableau.com/views/SubscriptionServices/Insights), and the data can be found [here](https://www.kaggle.com/datasets/safrin03/predictive-analytics-for-customer-churn-dataset).<br>
1. S, S. (2023, October 6). Predictive analytics for customer churn: [Dataset. Kaggle.](https://www.kaggle.com/datasets/safrin03/predictive-analytics-for-customer-churn-dataset) <br>
The dataset was my one and only reference, other than that I have not used any data or images from anywhere to tell my story!

# Final thoughts
Reflecting on the project, I believe the most critical aspect was tailoring the dashboards to meet the distinct needs of two very different personas. The best way to achieve this was by forming key questions that each persona would need answers for—whether it’s the CEO/CFO seeking insights on profitability and customer retention or the Producer/Director focused on content engagement and cost management.<br>

The financial objectives of a CEO with the creative and content-focused needs of a producer/director required careful consideration in terms of design and data presentation. I’m confident that the final dashboards provide actionable insights (call-to-action) for both personas, helping them make data-driven decisions. However, I would have liked more time to further refine the interactive features. Overall, this project was a valuable exercise in creating targeted, data-driven visualizations for multiple stakeholders.
