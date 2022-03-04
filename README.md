# UFOs

## Project Overview

### Relevant Files & Folders
Relevant Folder: static
Relevant HTML File: index_challenge.html

### Purpose
The purpose of this challenge was to assist “Dana” with visualizing UFO sighting data through a customized webpage that includes a table of fully functional filters to define UFO search criteria. 

### Data Analyzed
UFO Data:
-	Data.js file of UFO sightings between 1/1/2010 to 1/13/2010, including the date, city, state, country, shape, duration, and comments of said UFO sighting.  

### Deliverables 
The deliverables for this assignment were:
-	Deliverable 1: Filter UFO sightings on multiple criteria
-	Deliverable 2: A written report on the UFO analysis 


## Results

### Website Overview
Dana,
   I have created a website for you (index_challege.html).  On this webpage, you will see a title and header image, an introductory paragraph, and a table of UFO sighting from January 1 to January 13, 2010. 
   
  ![image](https://user-images.githubusercontent.com/92705556/156701519-56a9eb77-4ab5-43ea-8395-d3b6f46ae9f8.png)
 
  

### Filters Explanation
To the left of the table is a list of filters options.  These filters allow you to parse out specific sightings by date, city, state, country, and shape.   The input boxes show examples of the input data for each box.  You can choose to filter the UFO data by a single filter or multiple filters.  
 
 ![image](https://user-images.githubusercontent.com/92705556/156701542-1ed6d452-72ed-444f-99f5-2a8e38a820c8.png)


If you want to search for a specific date (ex. 1/2/2010), you would simple enter 1/2/2010 and press “tab” or “enter”. In this example there were eight sightings on 1/2/2010.  You can better refine your search on 1/2/2010 by adding additional criteria like “ca” for the state of California.  If you were to do this, you would see that there are two sightings in California on 1/2/2010 (screenshot below).  

![image](https://user-images.githubusercontent.com/92705556/156701556-47371cdb-e61a-40f5-b1ee-4622e0e2df6c.png)

 

### Clear the Filter
To clear the filters, either refresh the page or delete the input in the filter box(es) and then press “tab” or “enter”.


## Summary

### Drawback
While this webpage has functional filters to parse out and display the UFO sighting data, I see some drawbacks to its functionality.  

1)	All data has been entered in lowercase letters.  Proper grammar says to capitalize city and state names (i.i Fresno, CA rather than fresno, ca).  However, the filtering on this webpage is case specific and does not allow for capitalized letters.  I believe this drawback may cause problems for some users that are used to capitalizing proper nouns.  

2)	There is no summary statement or paragraph providing high level info on the data displayed (additional details provided the section below.)

### Additional Recommendations
1)	I believe a statement or paragraph should be added just above the table summarizing the table’s contents.  For example, I would say __“The table below summaries a total of 111 UFO sightings in the US and Canada between the dates of 1/1/2010 and 1/13/2010.”__ **

I believe this is important because without a little context, it is hard to know what to filter for.  For example, there is no info on sightings anywhere but the US and Canada.  Rather than wasting time filtering for “Australia” or the “UK” it is easier to just tell the user upfront that sightings are only in the US (“us”) and Canada (“canada”).

2)	I would add functionality to the table to allow for column sorting.  It is hard to search for a city or state if you don’t know all the potential options.  By allowing for column sorting within the table, you can retain all rows on the page but be able to better visualize trends in the data through grouping of column values.

__** Note - For disclosure: I summarized these data by copying and pasting the html table into Microsoft Excel and sorting values as discussed in bullet points above.__   


## Code Info

### Example Code Snippets of Java Code (found in app.js file under static folder)
![image](https://user-images.githubusercontent.com/92705556/156702192-f1685d5c-0577-4ecf-915f-31550cd909c8.png)
![image](https://user-images.githubusercontent.com/92705556/156702201-56fc364b-e0ea-490c-9928-64e3f7ebbeae.png)

