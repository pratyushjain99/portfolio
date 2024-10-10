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

## Summary till  Part II
#### Part I: Profit Maximization for Subscription Service

In Part I, I wanted to analyze customer behavior patterns within the context of a streaming platform, aiming to provide actionable insights for executives at subscription services. The goal was to determine what high-paying users are most interested in and how to **maximize profitability** by optimizing engagement and retention strategies.<br>

Using a dataset of over **100,000 records** from a customer churn dataset, I focused on analyzing various features like SubscriptionType, MonthlyCharges, GenrePreference, and Multi-Device Access. The initial visualizations included a bar chart highlighting the most popular genres among premium customers, a stacked bar chart to show how multi-device access affects churn, and a pie chart that segments customers by subscription tier.<br>

The objective was to help CEO identify which user segments and genres bring in the most value, guiding where to allocate marketing and content production budgets.
<br>
#### Part II: Wireframes and Storyboards

In Part II, I focused on **creating wireframes and dashboards** using Tableau to visually represent the insights. The story focused on two key audiences: C-suite executives (like the CEO and CFO) and content producers/directors. The inclusion of producer/director dashboard was a part of feedback I recieved during user -research.<br>

**For the C-suite audience**, the dashboard provides a financial lens, helping them understand customer behavior, content performance, and revenue trends. The visualizations include a Customer Lifetime Value (CLTV) histogram, a genre preference trend chart, a revenue heatmap by genre, and a pie chart showing subscriber segmentation.<br>

**For the content producers/directors**, the dashboard emphasizes audience engagement and content profitability. It includes visualizations like popular genres among premium subscribers, average viewing hours per genre, and a breakdown of monthly revenue by genre. This dashboard helps producers understand where to invest in content based on viewer preferences and engagement trends.<br>

User Research and Findings I conducted user interviews with a few individuals to refine the dashboards. The feedback highlighted improvements in color schemes, the need for clearer breakdowns of high-value customers, and the suggestion to include options of selection of genres for different customer types or subscription plans. Based on this feedback, I made changes, including adjusting colors, removing unnecessary graphs, and fine-tuning the axes parameters for better readability.
<br>
I have created personas here, but I have ddescribed then in the later half of this page (i.e. Part III) as well!<br>

Overall, Part II focused on translating data into meaningful visualizations that provide insights for different decision-makers, guiding them in making informed, strategic decisions.

# Changes made since Part II

Since Part II, I made some key changes based on feedback and additional insights I got from interviews. In particular, I fine-tuned both dashboards to better align with their personas!<br>

### C-suite dashboard
I ensured the focus was on the growth and money i.e. revenue. I revised the *Customer Lifetime Value (CLTV) visualization* and made it clearer, highlighting actionable insights for the CEO. I also updated the Revenue by Genre chart to better reflect which genres drive the most revenue, simplifying the pie chart segmentation to provide a quicker, clearer overview of customer segments. Previously the revenue tree had green-red hue highlights, where green depicted the genres you should put more money in, but from Professor's feedback, it was unclear for the audience. I further matched it to other slides. Although the professor's feedback said pie chart maybe not what gos there. But, I believe from previous internship experience, that a C-suite employee would definitely want to see the pie of subscriber base.<br><br>
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
Based on feedback, I replaced the *Viewership vs Revenue* chart with a more detailed scatter plot that shows how engagement correlates with revenue generation. It also conveys that, based on our data, *there is ABSOLUTELY no correlation between what people prefer to watch and what brings most revenue*. I also added the *Genre Trend in New Customers* chart to show how content preferences are evolving in newer customers, providing insights for future content production. Apart from generating more revenue, a producer should be careful about what new customers are watching! Moreover, the best part is for a director. Since most directors mostly work with a specific genre (like Speilberg, Nolan with Sci-Fi ; James Cameron for Action, etc), they can specifically select a genre from the legend, and it would highlight that genre across all graphs!<br><br>
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
As a CEO or CFO of a subscription service, the primary concern is *profit maximization*. You’re already familiar with the financial ins and outs, understanding how different customer segments like Basic, Standard, and Premium contribute to the company’s revenue. You’re constantly thinking about where to allocate your budget—should more go into marketing to attract new customers? into producing original content that will retain high-value subscribers? or both?<br>

You know how much each subscriber is worth through metrics like Customer Lifetime Value (CLTV), and you're focused on retaining those high-value customers. What matters most to you is figuring out which genres are generating the most revenue and whether your content investments align with what your audience wants. This dashboard is designed to give you a quick, actionable insight into how genres are performing and where to best utilise your resources to maximize profitability.
<br>
**Call to Action: Focus on retaining premium subscribers and increasing revenue by investing in high-performing genres like Comedy and Drama, while also exploring underutilized genres like Sci-Fi and Fantasy for future growth opportunities.**

### Content Producer/Director
On the other side, imagine you’re a Producer or Director tasked with creating content for a streaming platform. The goal is to engage your audience while managing production costs. You know that producing certain genres,like Sci-Fi or Action, can be expensive, but these genres often deliver higher engagement. The challenge is striking the right balance between the cost of production and the content’s ability to attract and retain viewers.<br>

You also have a deep understanding of your audience’s preferences. You know that different segments of your audience gravitate toward different genres, and your job is to create or acquire content that aligns with those preferences. This dashboard helps you see which genres resonate most with your audience and how you can adjust your investments to keep viewers engaged while staying within budget.<br>

**Call to Action: Invest in genres with strong engagement among premium subscribers, like Action and Drama, but remain mindful of production costs. Additionally, pay close attention to what new subscribers are watching, as this can guide future content decisions.**
<br>
These personas helped guide the overall structure and design of my dashboards, ensuring the data is presented in a way that’s relevant, easy to understand, and actionable for both decision-makers and content creators.

## Final design decisions
Other than the changes I have already mentioned above, I have made some general modifications:<br>

1. **Color scheme:** I changed the color palette from the initial version to a more neutral and consistent scheme that avoids unnecessary distraction. The use of red and green was reduced to avoid any bias or confusion. For example, I switched the Customer Lifetime Value (CLTV) chart to greyscale to better highlight the different ranges of customer value without the distraction of color. I also got rid of red-green in revenue treemap by switching to the matching color to deliver consistency! <br>
2. **Chart selection:** Based on user feedback, I removed unnecessary visualizations that were cluttering the dashboard, such as the multi-device access chart and the engagement heatmap, which were not providing meaningful insights. I replaced them with a scatter plot that links viewership to revenue.<br>
3. **Interactive Filters:** To make the dashboards more dynamic and interactive , I added filters for genres, allowing the user to drill down into specific genres if they want to focus on a particular type of content esp. for genre-specific director(e.g., Action or Comedy).<br>

#### Some more design choices (what was going in my head while I designed):

###### Notes on tiny details are inspired from this comment: *["When I built this dashboard, both God and I knew how it worked. Now, only God knows."](https://www.reddit.com/r/ProgrammerHumor/comments/8pdebc/only_god_and_i_knew)*
1. **Subscriber Segmentation Pie:** The red slice represents Basic subscribers, who generate the least revenue, pink is Standard, which is okay, and green is Premium, the highest value. Another goal fot a CEO can be to shift the balance by increasing the green segment. While it appears uniformly distributed now, the focus is to grow the green slice over time as you bring more subscribers into the premium tier.<br>

2. **Marketing Strategy:** To make the green slice bigger, allocate more marketing dollars and content production towards the genres that either generate high revenue or attract premium subscribers. These actions will drive the shift from basic to premium subscriptions. <br>

3. **Gender Preferences by Genre:** While the gender preferences for genres seem similar here, this visualization will become more useful as data evolves over time. For instance, in other datasets, Action might be more preferred by males and Romantic Comedies by females. These distinctions become clearer over time. And we can also further track the growth/change in preference over time.<br>

4. **Revenue by Genre:** Right now, revenue is almost equal across genres, but this dashboard will update monthly (or within a set time) to show which genre is generating the most revenue in that specific period. This is crucial for tracking evolving trends and content profitability in the recent times. What worked 5 years ago may not work now...<br>

5. **Genre Trendline Graph:** There was a very strong temptation to make this the primary bigger graph. The trendline graph is smaller because it's not as critical as revenue data. While I wanted to make it more prominent, as a C-suite employee or even a producer: revenue is more valuable since revenue matters more than viewership for decision-making.<br>

6. **Viewership vs. Revenue Correlation:** This was a shock for me! A key takeaway is that the genre with the most viewership isn’t necessarily the one generating the most revenue — there's absolutely no direct correlation here; which is an important insight.<br>

7. **Revenue Isn't Everything:** It’s also important to note that revenue doesn’t always equal profit. Genres like Sci-Fi may cost more to make, while Comedy is relatively cheaper. So, even high-revenue genres might not be the most profitable. This is a place where background knowledge of a director/producer comes to play.<br>

8. **Director’s Focus:** Directors can click on their specific genre to highlight it across all charts, making it easier to focus on the data relevant to their work.<br>

9. **Viewership vs. Revenue Plot:** This visualization is critical, especially for NEW directors and producers, as it helps them identify their target audience by showing how viewership correlates with revenue generation. They have to choose the most optimal strategy between: Do I want more people to watch my content? OR Do I want to generate more revenue? Or is there a sweet-spot somewhere in between which would be suitable for me!<br>

## References
Have a look at my visualisation [here](https://public.tableau.com/views/SubscriptionServices/Insights), and the data can be found [here](https://www.kaggle.com/datasets/safrin03/predictive-analytics-for-customer-churn-dataset).<br>
1. S, S. (2023, October 6). Predictive analytics for customer churn: [Dataset. Kaggle.](https://www.kaggle.com/datasets/safrin03/predictive-analytics-for-customer-churn-dataset) <br>
The dataset was my one and only reference, other than that I have not used any data or images from anywhere to tell my story!

# Final thoughts
Reflecting on the project, I believe the most critical aspect was *tailoring the dashboards* to meet the distinct needs of two very different personas. The best way to achieve this was by **forming key questions** that each persona would need answers for—whether it’s the CEO/CFO seeking insights on profitability and customer retention or the Producer/Director focused on content engagement and cost management.<br>

The financial objectives of a CEO with the creative and content-focused needs of a producer/director required careful consideration in terms of design and data presentation. I’m confident that the final dashboards provide actionable insights (call-to-action) for both personas, helping them make data-driven decisions. However, maybe, I would have liked more time to further refine the interactive features. Overall, this project was a valuable exercise in creating targeted, data-driven visualizations for multiple stakeholders.

## A big Thanks!
Thank you [Prof. Chris Gorranson](https://www.heinz.cmu.edu/faculty-research/profiles/goranson-christopher) for your  guidance throughout the project and for being cool enough to accept Tableau dashboards for the final submission. Your and Nickolas' advice made the process so much easier (and fun)!
