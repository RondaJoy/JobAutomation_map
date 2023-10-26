
**UCB Data Analysis Bootcamp**
## PROJECT 3 - Occupation Trends by State using Map Visualization

---------------
### Purpose:
Investigate the potential future impact of computer automation on jobs across the U.S. using data obtained from two sources:
- US Bureau of Labor Statictics, 2022-2023
- "The Future of Employment: How Susceptible are Jobs to Computerization?"; Carl Benedikt Frey and Michael A. Osborne; September 17, 2013

The former provides current information pertaining to the number of people employed in distinct categorical occupations within every U.S. state.  The latter assigns a probability ratings for each occupation using a complex algorithm pertaining to the likelihood of obsolescence due to computer automation. By merging these two datasets we can get a better idea of which occupations may be lost to technology and how many jobs might be impacted/lost in each state.

With regard to the associated dynamic map with rich text on click, data was limited to those occupations which scored 80% or higher probability of obsolescence due to emerging technologies. The number associated with each state in the tooltip of the map is equivalent to the sum of all jobs per state within the filtered dataset.  A click event function was added to make additional information accessible for each state.  By clicking on the name, a bar chart is displayed in a popup.  This bar chart constitues the 10 occupations with the highest likelihood of being lost to automation within the next couple of decades along with the number of people currently employed with a matching job title.  Note:  Most of these have a probability rating of 98-99%.  

[Map URL - Click Here](https://rondajoy.github.io/JobAutomation_map/)

--------------
### Contents of Repository:  
- 1 x .pdf document (The_Future_of_Employment.pdf)  *academic paper which served as source data for analysis*
- 1 x README file

SEE FOLDER LABELED "docs"
- Code Script
  - 1 x JavaScript file (Job_Loss_from_Automation_map_FINAL.js)
- Supporting Scripts
  - 1 x .css file (style.css)
  - 1 x html file (index.html)
- Resources Folder
  - 2 x .csv files (automation_data_by_state_2.csv, occupation_salary_2.csv)

-------------------
### Contributions:  
Thank you to Chris Barr and Michał who both contributed to my plea for support on Stackoverflow.
[StackOverflow URL](https://stackoverflow.com/questions/76909891/difficulty-rendering-rich-information-on-click-map-using-jquery)

------------------
### License:
[MIT](https://choosealicense.com/licenses/mit/)
