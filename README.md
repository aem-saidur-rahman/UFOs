# UFOs
UFO Sightings with JavaScript

## Purpose
1. Explain the strengths and weaknesses of JavaScript "standard" and JavaScript version ES6+.
2. Describe JavaScript syntax and ideal use cases.
3. Build and deploy JavaScript functions, including built-in functions.
4. Convert JavaScript functions to arrow functions.
5. Build and deploy forEach (JavaScript for loop).
6. Create, populate, and dynamically filter a table using JavaScript and HTML

## Overview 
To display a table organizing UFO data stored as a JavaScript array. The ability to filter by multiple criteria creating a dynamic website.  The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website. 

## Results:
### Welcome to UFO Sightings! 

<p align="center">  
<img src="https://github.com/aem-saidur-rahman/UFOs/blob/main/static/images/website.png" width="100%" height="100%">
</p>
<p align="center">  
<i>Figure : UFO Sightings Website </i>
</p>



### How the filters appear when first landing on the page:

<p align="center">  
<img src="https://github.com/aem-saidur-rahman/UFOs/blob/main/static/images/filter-landing.png" width="100%" height="100%">
</p>
<p align="center">  
<i>Figure : 5 list elements for filtering </i>
</p>


### How the filters appear after being used: 
By typing in the suggested placeholder elements (shape, triangle) as the filters, the result returns 18 matches.  Make sure to type everything in lower case letters and do not have spaces at the end of the text.  Click off the input box or press enter to initiate the filter.  To reset the filter criteria, click the UFO Sightings at the top left of the website. 

<p align="center">  
<img src="https://github.com/aem-saidur-rahman/UFOs/blob/main/static/images/filter-triangle.png" width="100%" height="100%">
</p>
<p align="center">  
<i>Figure : Filterd data using shape "triangle" </i>
</p>


## Summary: 

### Drawback:
The user must know specific dates, cities, or shapes to search.  Some shapes like "light" might not be as intuitive.  The filters require correct lower-case spellings and cannot include spaces at the end.  The shape that was used, for example, could not be typed as "tri angle",  or "Triangle".  The only acceptable input would be "triangle".


### Recommendations: 
1. The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.

<p align="center">  
<img src="https://github.com/aem-saidur-rahman/UFOs/blob/main/static/images/filter-Triangle-.png" width="100%" height="100%">
</p>
<p align="center">  
<i>Figure : Filterd data using shape "Triangle" </i>
</p>

2. A filter on a date range might be preferable than a singular date.  Typing 11/2011 did not bring up all the dates from November 2011 as hoped.  Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month.  It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings. 


<p align="center">  
<img src="https://github.com/aem-saidur-rahman/UFOs/blob/main/static/images/filter-month-.png" width="100%" height="100%">
</p>
<p align="center">  
<i>Figure : Filterd data using specific month </i>
</p>
