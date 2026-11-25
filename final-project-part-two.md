| [Home Page](https://christinelin10.github.io/christinelin-portfolio/)| [Data Viz Examples](dataviz-examples) | [Critique by Design](critique-by-design) | [Final Project I](final-project-part-one) | [Final Project II](final-project-part-two) | [Final Project III](final-project-part-three) |

# Final Project Part II: Left Further Behing
> How America's struggling students are falling further behind in math and reading, from fourth grade through senior year.

Draft Shorthand story: [Widening Gap in US Student Performance](https://carnegiemellon.shorthandstories.com/widening-gap-in-us-student-performance/index.html)

## Wireframes / Storyboards
My draft story is build in Shorthand, with charts made in Tableau and Datawrapper. It moves from the national average to the gap at each stage of schooling and ends with who leaves and who stays. Each frame below is one section of the draft. 

### Frame 1: Decades of progress, undone

What the reader sees: For decades, American students made slow but steady gains in reading and math. Then, around 2012, progress stopped. I also introduce my own experience teaching math at Springfield High School, where many ninth graders arrived far below grade level.
Visualization: 13-year-olds' average math and reading scores, 1978–2025 (NAEP Long-Term Trend).

<iframe title="Average math and reading scores of 13-year-olds, 1978 to 2025" src="https://public.tableau.com/views/finalproj_chart1a/Sheet1?:showVizHome=no&amp;:embed=true" style="width: 100%; border: none;" height="600"></iframe>

### Frame 2: The top held steady. The bottom fell.

What the reader sees: The decline wasn't shared. Since 2012, the highest-scoring 13-year-olds lost 4 points in math, while the lowest-scoring lost 29. The gap between them grew from 89 to 114 points.
Visualization: 13-year-olds' math scores at the 10th and 90th percentiles, 1978–2025.

<iframe title="Math scores of 13-year-olds at the 10th and 90th percentiles, 1978 to 2025" src="https://public.tableau.com/views/finalproj_chart1b/Sheet1?:showVizHome=no&amp;:embed=true" style="width: 100%; border: none;" height="600"></iframe>

### Frame 3: Fourth grade

What the reader sees: By fourth grade, the gap is already growing. The strongest readers scored 265 in both 2013 and 2024, while the weakest fell from 174 to 158.
Visualization: Fourth-grade reading scores from the 10th to 90th percentile, 2013–2024 (NAEP).

<iframe title="Reading Performance in 4th Grade" src="https://datawrapper.dwcdn.net/Qo085/1/" style="width: 100%; border: none;" height="320"></iframe>

### Frame 4: Middle school

What the reader sees: In middle school, struggling students fall the furthest. The gap among 13-year-olds in math is now the widest in the history of the test.
Visualization: Range plot of 13-year-olds' math scores from the 10th to 90th percentile, 1990–2025.

<iframe title="Range plot: the gap between the 10th and 90th percentile in 13-year-olds' math scores, 1990 to 2025" src="https://datawrapper.dwcdn.net/N9KLt/2/" style="width: 100%; border: none;" height="350"></iframe>

### Frame 5: Senior year

What the reader sees: By 12th grade, nearly half of seniors score below NAEP Basic in math. Since 2013, the gap grew by 10 points in math and 15 in reading. But NAEP only tests students who are still in school.
Visualizations: Twelfth-grade math and reading scores by percentile, 2013 vs. 2024, and range plots of the 12th-grade gap in each subject.

<iframe title="Twelfth-grade math and reading scores by percentile, 2013 vs. 2024" src="https://public.tableau.com/views/finalproj_chart4a/Sheet1?:showVizHome=no&amp;:embed=true" style="width: 100%; border: none;" height="600"></iframe> <iframe title="Reading Performance in 12th Grade" src="https://datawrapper.dwcdn.net/sJXHb/1/" style="width: 100%; border: none;" height="300"></iframe> <iframe title="Math Performance in 12th Grade" src="https://datawrapper.dwcdn.net/hGF8d/1/" style="width: 100%; border: none;" height="300"></iframe>

### Frame 6: Who leaves

What the reader sees: The students at the bottom are the ones most likely to leave. Ninth graders who scored in the lowest fifth in math were about seven times as likely to drop out as those in the fourth fifth, so the true senior-year gap is likely wider than the data shows.
Visualization: Percentage of 2009 ninth graders who dropped out by 2012, by ninth-grade math score.

<iframe title="Percentage of 2009 ninth graders who dropped out by 2012, by ninth-grade math score" src="https://public.tableau.com/views/finalproj_chart5/Sheet1?:showVizHome=no&amp;:embed=true" style="width: 100%; border: none;" height="500"></iframe>

### Frame 7: Who stays

What the reader sees: More young people are staying in school than ever before. But staying in school isn't the same as catching up, and the story closes by calling for support for the lowest-scoring students at every stage of school.
Visualization: Percentage of 16- to 24-year-olds in school or graduated, 1970–2022.

<iframe title="Percent of 16- to 24-year-olds in school or graduated, 1970 to 2022" src="https://public.tableau.com/shared/DRD29Z4FJ?:showVizHome=no&amp;:embed=true" style="width: 100%; border: none;" height="500"></iframe>

#### Design choices across the story
- Consistent colors: the 10th percentile (struggling students) and 90th percentile (strongest students) use the same two colors in every chart, with other values in gray.
- Headline titles: each chart's title states its takeaway rather than describing the chart.
- Range plots for the gap: each bar runs from the 10th to the 90th percentile, so the bar's length is the gap.
- Sources and notes: each chart notes which test it uses (NAEP main assessment or NAEP Long-Term Trend), since the two are on different scales and can't be compared directly.

## User research 

### Target audience
> My target audience is teachers and parents of school-age children: people who care about how students are doing but are not data experts. The story should make sense to them without a statistics background.
> For this round of testing, I interviewed three Carnegie Mellon graduate students. They are not teachers or parents, but they are a fair test of my core requirement: a reader without a background in education data should be able to follow the story. I showed each person my draft Shorthand story without explaining it first. In Part III, I would like to test the revised story with at least one teacher or parent, who are closer to my intended audience.

### Interview script
> I introduced the session by saying: "This is an early draft of a data story I'm working on. It's still rough, so honest reactions are the most helpful thing you can give me. Please think out loud as you scroll through. I won't explain anything until the end."

| Goal | Questions to Ask |
|------|------------------|
| Find what draws readers in | 1. What was the most interesting part? Why? |
| Find where readers get lost (for example, percentiles or chart types)	| 2. What was the most confusing part? What made it hard to follow? |
| Learn which findings land	| 3. What was the most surprising thing you learned? |
| Learn which chart carries the story	| 4. Which chart or moment had the most impact on you? Why? |
| Collect direct suggestions	| 5. What is the one thing you would change to make the story clearer? |

### Interview findings
> I interviewed three CMU graduate students. My notes combine their answers rather than separating them by person, so the table below lists the responses I recorded for each question across all three interviews.

| Questions | Responses |
| 1. What was the most interesting part?	| The story itself: the narrative of how the gap develops through school. |
| 2. What was the most confusing part? What made it hard to follow?	| The math vs. reading graphs: having both subjects in the same charts made them hard to read. |
| 3. What was the most surprising thing you learned? |	The difference between high performers and low performers. |
| 4. Which chart or moment had the most impact on you? | The dropout rate. |
| 5. What is the one thing you would change to make the story clearer? | Show a metric for the average difference (gap) that includes the 10th percentile.
Include the full overall average.
Mark specific dips in the year-by-year data.
Label the y-axis to say what the scores are. |

> Summary: The narrative and the contrast between high and low performers worked; the gap between top and bottom students was the most surprising finding, and the dropout section had the most impact. The biggest problem was readability: combining math and reading in the same charts was confusing, and the score axes did not explain what the numbers mean. Interviewees also wanted the gap expressed as a single number and wanted the overall average shown for context.

### Identified changes for Part III
Because my user interviews were about my Part I graphics, I was able to implement most of the feedback that I received. 

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Math vs. reading graphs were confusing | Separate math and reading into their own charts (or clearly labeled side-by-side panels) instead of combining them. |
| Score axes were unclear ("what scores?")	| Label every y-axis with the test and scale, for example "NAEP math score (0–500)," and add a short note explaining what NAEP scores measure. |
| Interviewees wanted a single gap metric that includes the 10th percentile |	Add the size of the gap (90th minus 10th percentile, in points) to each section, using the range plots and direct labels such as "114-point gap." |
| Interviewees wanted the full overall average	| Show the overall average alongside the 10th and 90th percentiles, so readers can see how the average hides the split. |
| Interviewees wanted specific dips marked	| Add annotations to key years in the year-by-year charts, such as the 2012 peak and the 2022 low. |
| The dropout rate had the most impact	| Give the dropout section more emphasis, with a stronger headline and its chart placed prominently. |

## References
- IDEO.org. Design Kit: Prototyping, Activity 06, "Test and Get Feedback," and Activity 07, "Iterate."
- National Center for Education Statistics. NAEP Data Explorer. https://www.nationsreportcard.gov/ndecore/xplore/NDE
- National Center for Education Statistics. NAEP Long-Term Trend Assessment results. https://www.nationsreportcard.gov/ltt/
- National Center for Education Statistics. Digest of Education Statistics, Tables 219.62a–c and 219.70. https://nces.ed.gov/programs/digest/

## AI acknowledgements
_I used AI to generate csv data for DataWrapper_

