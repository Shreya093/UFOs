# UFOs


## Project Overview

The purpose of this project is to build an HTML page that will allow us to pull up information from a javascript data file using filters on the web page. The request from a client was to display a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria creating a dynamic website. The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website.

## Results

### Welcome to UFO Sightings!

<img width="1440" alt="mainpg" src="https://user-images.githubusercontent.com/88418201/139943474-1adbb933-f338-4cd5-a742-a0c7248b1f40.png">

### How the filters appear when we first land on the page :

<img width="1440" alt="filterpg" src="https://user-images.githubusercontent.com/88418201/139943615-831ee0b7-c940-42f5-bd8a-402feb403321.png">

### How the filters appear after giving the multiple search criteria :

By giving in the suggested placeholder elements as the filters, the web page returns 2 matches. Click off the input box or press enter to initiate the filter. To reset the filter criteria, click the **UFO Sightings** at the top left of the website.

<img width="1440" alt="new" src="https://user-images.githubusercontent.com/88418201/139944359-74814ace-4af2-4ce5-893b-64bf5455af4a.png">

## Summary

### Drawback :

The major drawaback is that for filtering the UFO sightings web page the user must know the specific dates, cities, or shapes to search. The filters requires correct lower-case spellings and cannot include spaces at the end. The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon". The only acceptable input would be "el cajon".

### Recommendations :

1. We can ignore the case-sensitivity and allow  for upper and lower cases while giving the filter criterias and add a trim function to catch spaces at the end of words.

<img width="1427" alt="Screen Shot 2021-11-02 at 1 14 32 PM" src="https://user-images.githubusercontent.com/88418201/139945379-dbc887cd-f710-4932-8cf5-6b21ed05611a.png">

<img width="1427" alt="Screen Shot 2021-11-02 at 1 15 30 PM" src="https://user-images.githubusercontent.com/88418201/139945484-cd77bc9a-e1b4-4764-9975-f8d3f8bd5698.png">

2. A filter on a date range might be preferable than a singular date. Typing 1/2010 did not bring up all the dates from January as hoped. Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month. It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings.

<img width="1427" alt="Screen Shot 2021-11-02 at 1 17 06 PM" src="https://user-images.githubusercontent.com/88418201/139945688-3c0de2a2-7851-464c-b976-f9bcb73638ce.png">


