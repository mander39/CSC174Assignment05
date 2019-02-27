# CSC174 Team Manhattan
## Assignment 5
- 2/22/19
- Odd Student Out: Two Students are from the same country, and the third is from a different country, making her the odd student out.
### Domain
The Domain of this assignment are the three classmates, who of which share home countries and one of which is from a different country.
### Triples to define the Ontology
- Each student has had their home country
- Each student has had their home town within that country 
- Each student has a major/minor
- Each student has written about their lives before college
- Each student has written about their lives while at the University
- Each student has had their extra-curricular activities
### Taxonomy Explanation
Homepage will have h2s with the Students names, and under those a h3 with called Home country, a section with their country and image of the student.
The individual pages will have a h1 with their names, h2s of home country, home town, precollege life, college life, and extra curriculars. The sub content for the first two are in sections, the next two are in p tags, and the last one is an ul containing li tags.
On every page, the navigation is an unordered list at the top with li tags
### Choreography Explanation
I have arranged the topics in order of which would have come first in their lives. It starts at their home country, because that is the thing that makes one student the odd one out. It then goes to hometown, precollege experience, current college experience, and ends off with the extra curriculars they've done in college

### Slider Notes - Michael 
To change the images go into the slider.inc file. 
The code didnt come with any documentation, so look for these (ctrl+F) varibles in the source code (jssor.slider) to adjust the behavior:
- $PauseOnHover = on by default (slideshow pauses on mouseover)
- $AutoPlayInterval = 3 seconds by default, I changed it to 6 seconds since 3 seemed too fast. 
- The "sections" with just country name in them should probably be h4s, w3c validator is throwing errors at those 

### Validation Notes - Amanda
- I checked the validation stuff this morning after doing the CSS and it is still throwing errors about the sections
- It's also throwing an error about the font upload code even though that's exactly what Google fonts had me upload
