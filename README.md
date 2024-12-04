# 4906FinalCode

The final versions of my code for my submitted GEOM 4906 Honours Project can be found here. Here is a brief overview of what can be found in each of these files:

<b>Consent Form</b>
<br>
In here are all of the files to create the first webpage with the consent form. The style sheet and image paths reflect the paths in this GitHub repository and will need to be changed if being used else where. As well, the href under the 'buttondiv' div will need to be changed for the webpage to properly redirect to the reporting tool. It is currently referenced to this GitHub repository.

<b>Reporting Tool</b><n/>
<br>
Here are the files necessary to make the main reporting tool run. A config file is included to easily change some of the variables in this file. Some variables would not work properly in the config file so they would need to be changed in the index.html file. These are:
<ul>
  <li>Fitz: This varibale is customized to reflect Fitzroy's boundary. It should be change for other parks with the coordinates of their boundary.</li>
</ul>

All of the paths to stylesheet, images and link to next webpage reflect the paths for GitHub same as the Consent Form.

<b>Reporting Map</b>
<br>
The Reporting Map is the final page of the website and displays the users submitted reponse from the Reporting Tool on a map. This also comes with a config file to easilt change some of the variables. A few things to note:
<ul>
  <li>When setting longitude and latitude of the marker, the index nubers will need to change depending on where these values are located in your spreadsheet (ie. in this spreadsheet long is located in column 7 and lat is located in column 6.</li>
  <li>This is the same when editing what is shown in the pop-up for the marker. Index values need to be adjusted according to the spreadsheet.</li>
</ul>

All of the paths to stylesheet and images to next webpage reflect the paths for GitHub same as the Consent Form.

<b>Google Apps Script</b>
<br>
This file contains the Apps Script connected to the Google Spreadsheet that is used to send the data from the html form to the spreadsheet (jamiewilson, 2018). It is in the form of a txt file. 

Jamiewilson (2018). Form-to-google-sheets. GitHub. Retrieved November 18, 2024, from 
https://github.com/jamiewilson/form-to-google-sheets

<b>Map For Staff</b>
<br>
This folder contains an html file that shows the open source version of the mapbox map for staff to use. It can simply be opened by itself. It is currently filtered to only show incompleted issues but this can be changed by editing lines 48 and 49. The pop-up can also be edited to show different things.

<b>Analysis</b>
<br>
This file contains the interactive maps used for completeing analyisis on the submissions to the reporting tool. These can be opened as is. 







