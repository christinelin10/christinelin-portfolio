| [Home Page](https://christinelin10.github.io/christinelin-portfolio/) | [Data Viz Examples](dataviz-examples) | [Critique by Design](critique-by-design) | [Final Project I](final-project-part-one) | [Final Project II](final-project-part-two) | [Final Project III](final-project-part-three) |

# Critique by Design: 8 Fastest Cars in the World, 2026
[MakeoverMonday](https://makeovermonday.vercel.app/)

This page documents my critique and redesign of a visualization of the world's fastest production hypercars as of 2026, from choosing the original chart through critique, sketching, user testing, and a final redesign in Tableau.

## Step One: The Visualization

![Original visualization](original-data-viz.png)
[Original Data Visualization](https://makeovermonday.vercel.app/dataset/8-fastest-cars-in-the-world-as-of-2026)

I chose this data visualization because it is barely a visualization at all. It is essentially a table of information about the eight fastest cars in the world. The table is transparent, accurate, and easy to read, but it leaves the work of finding patterns to the audience. This is what I believed would make it a good candidate for a redesign. All of the information is there; however, there is nothing about the design that helps the audience see what is interesting about it. It also seemed most useful for people who are already interested in cars and actively looking for this information, but, and on the flip side, incredibly less engaging or enticing for anyone else. I wanted to see whether a redesign could make the data more visually appealing and draw in a wider audience. 

The dataset covers eight production cars -- the fastest cars in the world as of January 2026. The dataset lists ten key features: car name, car manufacturer, country of origin, engine type, top speed in miles per hour (mph), top speed in kilometers per hour (km/h), horsepower, toque, price, and the number of units produced. The dataset also lists a few calculated columns, like price per horsepower and speed per horsepower. 

## Step Two: The Critique
Using Stephen Few's Data Visualization Effectiveness Profile, my main observation was that there is little to no data visualization here. The original is essentially a table of information; however, coming from a quantitative background, this has some true strengths. The data is fully transparent, accurate, easy to read, and easy to understand. Every data point is visible, and nothing is hidden. This is why I rated its Completeness at a 9/10. I only docked 1 point because one of the calculated columns is not fully labeled. 

Where the dataset fails is in turning the information into insight -- i.e. telling a story. Because it is a table, the reader has to compare numbers row by row to find any patters, and nothing in the design draws attention to what is interesting or surprising in the data. It is, as previously mentioned, not very visually engaging. This is why I rated it a 1/10 in Aesthetics. I would have given it a 0/10, but this was not an option. 

The primary audience appears to be people who are already interested in cars and may be searching for the listed metrics. For them, I'm sure the table is fairly effective, since they are looking for this information, will take the time to read and compare manually, and deeply understand what the table is truly representing. However, for the average audience member, the table is not an effective design that draws anyone else in. 

Based on this critique, I decided to focus my redesign on making the data more visually appealing and exciting, with the question of "fastest" at the center. 

## Step Three: Sketch a Solution

<div class='tableauPlaceholder' id='viz1794542483832' style='position: relative'><noscript><a href='#'><img alt='Top Speed vs Horsepower ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ca&#47;car_first_sketch_mm&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='car_first_sketch_mm&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ca&#47;car_first_sketch_mm&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1794542483832');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

This first draft 'sketch' is a scatterplot of Top Speed (mph) vs Horsepower with each car colored to represent the engine type. This sketch responds to the main weakness I found in my critique: the table did not tell a story. Plotting these tow columns against each other makes the relationship between speed and horsepower visible at a glance. It is interesting to note that the most powerful car, the Rimac C Two, has the lowest top speed making me think that it is the 'slowest.' This sketch suggested that the more interesting story in this data is the question and definition of what 'fast' really is, which became the starting point for my final rendition. 

## Step four: Test the solution

I showed my Step Three sketch (Top Speed vs Horsepower scatter plot) to two people without explaining it first. 
Then I asked the following questions and received the following responses, in short. 

Results: 

| Question | Interview 1 (First year MISM student and TSWD classmate) | Interview 2 (Second year MISM student and TSWD classmate)|
|----------|-------------|-------------|
| Can you tell me what you think this is? | A graph about some cars' top speeds versus horsepower | Same as Interview 1 |
| Can you describe to me what this is telling you? | Just about the top speed and horsepower of cars. | The cars are probably very expensive and are supposed to be very fast. |
| Is there anything you find surprising or confusing? | I do not understand why the dots are different colors | (Pointed out the color legend) I am confused why we are only looking at these 8 cars |
| Who do you think is the intended audience for this? | People who enjoy cars | Same as Interview 1 |
| Is there anything you would change or do differently? | The data seems very dry | I think the engine information may not be necessary unless this is specifically for someone who understands cars |

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

