# Wireframes / storyboards
I have went ahead with the Tableau dashboard option. I felt that I have some intresting things which can be done with my subscription services dataset. For reference, you can also visit [Part 1](https://data.world/makeovermonday/generative-ai-search-trends-in-the-united-states).<br>

So my story focuses on two different audience: <br>
1. C-suite employee (includes CEO, CFO, etc): This one focuses on financial performance, customer preferences, and revenue-generating trends. This will help the decision makes here understand customer behavior, the most profitable content genres, and the customer lifetime value (CLTV). This serves two purposes: One, seeing what my customers want to watch? what their preferences are? what brings most revenue? etc. Second, where to put my marketing money: this includes both marketing dollars and production(eg: similar to netflix originals) which is also told by data. This has four visualisations:<br>
1.1. Customer Lifetime Value Histogram (shows ranges of customer value) <br>
1.2.Genre Preference Trend (bar or line chart showing how customers' genre preferences have shifted over time)<br>
1.3.Revenue by Genre (heatmap showing which genres bring the most revenue)<br>
1.4. Customer segments (pie chart showing what percentage of total belongs to which segment of customer (basic, standard, premium)).

   Here's a look:
<div class='tableauPlaceholder' id='viz1728006773302' style='position: relative'><noscript><a href='#'><img alt='Admin Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Su&#47;SubscriptionServices&#47;AdminDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SubscriptionServices&#47;AdminDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Su&#47;SubscriptionServices&#47;AdminDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1728006773302');
  var vizElement = divElement.getElementsByTagName('object')[0];
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1227px';}
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

2. Producer Dashboard: This dashboard is aimed at content producers looking to invest in future projects by kind-of exploring audience preferences, viewing behavior, and content profitability. I have introduced this after my user research, so it's a bit half baked. I have worked on visualisations, but not made the final dashboard yet...<br>
The visualisations include:<br>
2.1. Popular Genres among Premium Customers (bar chart highlighting top genres)
2.2. Average Viewing Hours per Genre (showing which genres hold the audience's attention the longest)
2.3. Monthly Revenue Breakdown by Genre (stacked bar showing monthly genre-based revenue)

# User research 

## Target audience
Audience Description:<br>
1. CEO of Subscription Service: Interested in understanding customer profitability, content trends, and actionable insights for maximizing revenue.<br>
2. Content Producers: Focused on identifying audience preferences and which content genres are worth further investment based on user behavior and revenue data.<br>
Text here!

## Interview script
I found one random person sitting in Rotunda, and two of my friends to complete the interview.

| Goal | Questions to Ask |
|------|------------------|
|Overall Flow|What to do understand by first look and no info given?|
|Identify improvements in dashboard usability|Is there anything missing?|
|Insights actionability|Will you like something more to be included? (I described user persona here)|


## Interview findings

| Questions               | Interview 1 | Interview 2 | Interview 3 |
|-------------------------|--------------------------------|-------------|-------------|
|What to do understand by first look and no info given?|"At first glance, the charts seem focused on customer value and revenue breakdown by genre. It feels like it's showing the profitability of different types of customers|Amazing, looks good... As a CEO its good. An alternate use can be to present it to producer/director for digital content, but there is no use for CLTV for them.|I immediately see a focus on customer lifetime value and genre preferences. The layout hints at helping me decide what content to focus on, but some connections aren't immediately clear.|
|Is there anything missing?|Nope, looks good. Colors can be a bit better, the Yellow and Gold is disteracting.|A brief introduction would help first-time users understand what each visualization is trying to say. |There’s a lot of good data here, but I think including a filter to switch between customer types or subscription plans would be helpful. |
|Will you like something more to be included?|I'd like a clearer breakdown of high-value customers and which genres are attracting them. It seems like this insight is there, which I'd like to know as a CEO!|An alternate dashboard for producer/director can cater to more than one audience! So try including that.|It would help if there were more details about the revenue per customer per genre. It’s difficult to make a clear financial decision without seeing how much each customer contributes to the total revenue for a genre. (But I think this was not aas helpful, because a CEO knows how much a user type pays already)|


# Identified changes for Part III


| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
|Color issue| Changed colors and gradings to grey since colors don't provide any value in CLTV graph.|
|Adding label|Added legends to pie chart and got rid of legends, since they are not needed anymore.|
|5 graphs are too squeezed|Got rid of a graph(multi-device access and scatter plot with user-rating vs monthly charges)|
|Graphs can start around 6000 for premium subscriber bars|Changes axes parameters|


# Final thoughts

I feel that the project has evolved nicely, especially after integrating feedback from user research. The CEO dashboard is now fine-tuned to focus on what matters most: Customer Lifetime Value (CLTV), revenue-driving genres, and customer segments. The changes: like improving the color scheme for better clarity and removing unnecessary graphs—really made the visualizations clearer for decision-making. <br>
For the Producer dashboard, it's still a bit of a work in progress, but the core visualizations are in place. Based on user feedback, I need to make sure it better reflects the needs of content producers, like highlighting which genres are most popular with premium subscribers and tracking engagement over time. Moving forward, adding interactivity (like filters for subscription types) will make the dashboards even more actionable and user-friendly for this persona (Since, a action director may only prefer stats about his genre, or a producer maybe fizated on producing only Comedy).<br>
The personas of CEO and Content Producer really helped guide the direction of the project. The question format (What would this user need to act on certain thing?) really helped in brainstorming what do include and what to de-prioritize. 


# Persona:

1. CEO of Subscription Service Persona:<br>
Primary Focus: Maximizing profitability, improving customer retention, giving insights about original productions and strategic decision-making for business growth.
Since they’re already well-versed in customer segmentation, they know how different subscription segments (like Basic, Standard, and Premium) are priced for their service. They also have proper understanding of Customer Lifetime Value (CLTV), how much each customer segment is worth, and what’s required to keep those customers loyal.
The CEO knows company’s costs of content production and acquisition and how much revenue it brings in. They also stay on top of market trends and know what’s going on, especially in terms of customer behavior and content preferences.
What the CEO really cares about is understanding which genres are driving the most revenue. They want to know what their customers watch and how they can use that information to make decisions about marketing and content development. They’re also keen on reducing customer churn(they know what customer churn is), keeping those high-value subscribers engaged. So, dashboards that make complex financial and audience data easy to digest are a must for helping the CEO make effective decisions.<br>
2. Content producer/director persona:<br>
Primary Focus: Creating and acquiring content that is liked by audience, ensuring high engagement while managing production costs.<br>
The cost of production is always at the top knowledge! Producing genres like Sci-Fi might be more expensive than something like Comedy, so they have to carefully weigh the cost against the potential returns. They’re also well aware of what content keeps viewers engaged.<br>
What the content producer really wants to see is data on premium subscribers—what they watch and which genres keep them engaged. Understanding viewing times and engagement is important because it helps them decide where to invest in. They’re also interested in knowing which genres are bringing in the most revenue. This information is critical for ensuring that the company’s investment in content pays off.
They have to balance budget constraints while also keeping up with current market trends They need quick insights into audience preferences and genre profitability for content creation and licensing efforts.









