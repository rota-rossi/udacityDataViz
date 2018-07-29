# PISA Data Survey


### Description

PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

The survey contains not only the students performance in the tests, but also several metrics varying from socioeconomic informations (family assets) to the perceived attention given by the teacher.

In this visualization, I'll be focusing on the relation between the math grade and family factors, by country.

#### Design Choices 

My viz will contain a world map, that will allow for the user not only to see what countries were in the survey, but also to interact with it to see the graphs for that specific country.

Besides the map, my plan is to add a set of charts to compare the student math grades to several factors, like:
- Parents education level (Heatmap);
- If parents live with the child;
- Parents employment status (Heatmap);
- Study Time With Parents (Bar Chart);

#### First Version

https://public.tableau.com/profile/leorossi#!/vizhome/Pisa-Final/ParentsInfluenceonMathResults


#### Feedback

from Taly Hotimsty (taly.hotimsky@gmail.com):

> 1. Is it possible to provide the summary on top? (looking at it at first, I wasn't sure what the data was or what we were trying to analyze from it)

I added this summary on the project documentation;

> 2. Is there a rationale for StudyTime with Parent not to show numbers straight up as the others? (only when you hover over the groups)

Changed for consistency 

> 3. Wouldn't it merit a tooltip, link, anything about what ISCED even means and how it's relevant to the graph?

These are the ISCED Levels that are used by the graphs:

Level 0: Pre-primary education.
Level 1: Primary education or first stage of basic education.
Level 2: Lower secondary education or second stage of basic education
Level 3: Upper secondary education
Level 4: Post-secondary non-tertiary education
Level 5B: First stage of tertiary education: typically shorter, more practical/technical/occupationally specific programmes leading to professional qualifications.
Level 5A: First stage of tertiary education: largely theoretically based programmes intended to provide qualifications for gaining entry into more advanced research programmes and professions with higher skills requirements.
Level 6: Second stage of tertiary education (leading to an advanced research qualification).

Added an legend box that explains those levels

> 4. I like the crossings of Mother x Father in Parent Employment Status and Parents at Home

> 5. It made me wonder how the Parent at Home related to their Employment status. (ie. is working from home affecting results in a certain way while at home because searching for a job affects it a different way?)

> 6. Overall the presentation is clean

> 7. I couldn't really tell what the numbers for average meant in context. For instance, "average math of 397" means what? Is 397 a grade? Out of what? 1000? etc

The averages should be seen as a comparative measure, not as an absolute measure. 

> 8. The description could use a bit more detail about the data (student's age and data source are the two that come to mind straight up)

This informations are available on the writeup.

#### New Visualization:

https://public.tableau.com/profile/leorossi#!/vizhome/Pisa2012-Final/ParentsInfluenceonMathResults

#### Changes made after the considerations:

- Added a new Dashboard to show an overview with the top Averages on the three disciplines (Math, Reading and Science);
- Added explanations on ISCED Levels;


## Resources

#### Pisa ###

Programme for International Student Assessment (2000 to 2012)
https://en.wikipedia.org/wiki/Programme_for_International_Student_Assessment_(2000_to_2012)

PISA Codebook for student questionnaire data file:
https://www.oecd.org/pisa/pisaproducts/pisa2012database-downloadabledata.htm

### Tableau ###

Tableau Prep:
https://www.tableau.com/products/prep

Tableau Tutorials:
https://www.tableau.com/learn/training

Tableau Tip Tuesday: How to Create Diverging Bar Charts 
http://www.vizwiz.com/2016/01/divergingbarchart.html

### ISCED ###

International Standard Classification of Education
(ISCED) Levels:
https://en.wikipedia.org/wiki/International_Standard_Classification_of_Education



