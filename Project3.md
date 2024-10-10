| [home page](https://pratyushjain99.github.io/portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](Project1) | [final project II](Project2) | [final project III](Project3) |

# The final data story
> Have a look at my visualisation [here](https://public.tableau.com/views/SubscriptionServices/Insights)

The story goes like:

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


Since Part II, I made some key changes based on feedback and additional insights I got from interviews. In particular, I fine-tuned both dashboards to better align with their personas!:<br>

1. C-suite dashboard: I ensured the focus was on the growth and money i.e. revenue. I revised the Customer Lifetime Value (CLTV) visualization and made it clearer, highlighting actionable insights for the CEO. I also updated the Revenue by Genre chart to better reflect which genres drive the most revenue, simplifying the pie chart segmentation to provide a quicker, clearer overview of customer segments. Previously the revenue tree had green-red hue highlights, where green depicted the genres you should put more money in, but from Professor's feedback, it was unclear for the audience. I further matched it to other slides. Although the professor's feedback said pie chart maybe not what gos there. But, I believe from previous internship experience, that a C-suite employee would definitely want to seethe pie of subscriber base.<br>

<div class='tableauPlaceholder' id='viz1728540920816' style='position: relative'><noscript><a href='#'><img alt='Admin Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Su&#47;SubscriptionServices-Admin&#47;AdminDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SubscriptionServices-Admin&#47;AdminDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Su&#47;SubscriptionServices-Admin&#47;AdminDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1728540920816');
  var vizElement = divElement.getElementsByTagName('object')[0];
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1227px';}
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

2. Producer/Director dashboard: Based on feedback, I replaced the "Viewership vs Revenue" chart with a more detailed scatter plot that shows how engagement correlates with revenue generation. It also conveys that, based on our data, there is ABSOLUTELY no correlation between what people prefer to watch and what brings most revenue. I also added the "Genre Trend in New Customers" chart to show how content preferences are evolving in newer customers, providing insights for future content production. Apart from generating more revenue, a producer should be careful about what new customers are watching! Moreover, the best part is for a director. Since most directors mostly work with a specific genre (like Speilberg, Nolan with Sci-Fi ; James Cameron for Action, etc), they can specifically select a genre from the legend, and it would highlight that genre across all graphs!<br>
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
> Talk about who you identified as the audience for your final data story.  Include any other information you've used that helped you narrow the focus (e.g. insights from your interviews, personas, etc.).  Note any specific adjustments you made to your final project to make it work for your audience.

Text here!

## Final design decisions
> You can specifically break out your design decisions here, or include it under *Changes made since Part II* and delete this section. Talk about the design decisions you had to make along the way, and reflect on anything in particular that stands out to you that you learned working through the process.  Include any other information that helps round out your data story. 

Text here!

## References
> You should have already included detailed references on your Shorthand story - if so, you can probably skip this section.  Use this section to capture any additional special notes or information necessary.  If you do this, you probably want to include a link from Shorthand to this page. Make sure to double-check that you aren't using copyright material and that you have added / updated any citations or other content that you used to create your data story.  Make sure you have cited external sources correctly. 

Text here!

# Final thoughts
> You can summarize any final thoughts / reflections that don't fit well in the previous sections here.  How did it go?  What did you run out of time for, or wish you had a chance to revisit?  What were you most excited about?  Include any final reflections as you think they might help us understand your process.  If you already included such reflections elsewhere, you can delete this section. 

Text here!
