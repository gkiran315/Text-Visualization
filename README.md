 # Text and Geospatial Visualization

Project to extract and visualize the texts from two blogs, The Wikinews data (roughly 3.3M) contains 11,267 articles and the Huffington Post data (roughly 29.4M) contains 75,293 political blogs.


### Data Processing

The application uses two datasets, one is from wiki news and other is from Huffington post. On intial page load the wiki news data will be loaded and Huffington data will be loaded on initial selection of Huffinton source button in the options pane.

It converts the rawdata into the format of key value pairs where key is the term and values contains the properties of category, total frequency and monthly wise object.

Each monthly wise object contains the blog numbers in which the term occured and monthly frequency

### Functionality 
The application provides an intuitive user interface, options for the selection of source, time interval options, chart type options(ie, option for the selection of word cloud & relationships between the terms or for a particular term) and option for the number of terms to be displayed.

_**Word Cloud and Timeline**_

In default the application visualizes the top 50 words of wiki news with its word cloud and its corresponding time line.

When the user selects the source, required time interval,overview,and  particular number of terms to be displayed then its word cloud and respective time line is displayed.
when the user hover on a particular word on the word cloud its respective time series graph is highlited on the timeline and viceversa.

_**Relations and Timeline**_

When the user double clicks a particular word then all the words of the word cloud become inactive and only the timeseries of that word is displayed.

When the user selects the relationships for the terms and give paticular number of terms to be displayed then the chord diagram representing the relationships among the given number of terms along with its corresponding time series is displayed.


When the user hovers on any word on the chord diagram then its relation with other terms is highlighted along with its timeseries and viceversa.


### Interesting Findings

#### Correlation between news on Iraq and the US-Iraq Status of Forces Agreement

From the visualization, it is noticeable that Huffington Post news related to Iraq drops significantly from late 2008 to early 2009.  This drop occurs around the time the US-Iraq Status of Forces Agreement was signed.  It is likely that the effects of this agreement (the withdrawal of US troops in Iraq) led to less news reporting on Iraq.

#### Comparison of 2008 and 2012 presidential election seasons

It is apparent from the visualization that news coverage of the top 50 terms is at a maximum during the 2008 and 2012 election seasons.

The visualization also shows that the term frequency of elected presidential candidates is substantially higher than the frequency of the other candidate during the months following the election.

#### Iraq as an issue in the 2008 election season

The relationships feature of the visualization shows a correlation between the presidential candidates and Iraq, which suggests that Iraq may have been a major issue in the election.


