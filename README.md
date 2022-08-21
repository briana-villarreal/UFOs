# UFOs
## Overview of the Project
### Purpose
My client, Dana, desires to utilize data of UFO sightings to build an interactive webpage that allows users to parse information. To help her do this, I created a webpage and dynamic table that allows users to filter their search criteria for a given UFO sighting contained within the data source based on the following: date, city, state, country, and shape.
## Results
### Utilizing the Search Criteria on the Webpage
* Users can re-initialize their search by clicking on the navigation bar at the top left, which reads "UFO Sightings".  
![initial page](https://user-images.githubusercontent.com/106560739/185807632-beefd890-8e66-4807-9da2-63ab1a0bfd76.png)
* To filter the UFO data based on sighting date, the user can input their date of interest in the "Enter Date" area of the table. Their change of date is detected and the table is adjusted accordingly. In the image below, the date "1/6/2010" was entered and the table only displays this sighting date.
![date](https://user-images.githubusercontent.com/106560739/185807747-e9eacfe2-adbe-4d19-bdf9-4c522916f663.png)
* To filter the UFO data based on sighting city, the user can input their city of interest in the "Enter City" area of the table. Their change of city is detected and the table is adjusted accordingly. In the image below, the city "san diego" was entered and the table only displays this sighting city.
![city](https://user-images.githubusercontent.com/106560739/185807807-1ab6e37b-d767-4f66-b1b2-246971203e5a.png)
* To filter the UFO data based on sighting state, the user can input their state of interest in the "Enter State" area of the table. Their change of state is detected and the table is adjusted accordingly. In the image below, the state "tx" was entered and the table only displays this sighting state.
![state](https://user-images.githubusercontent.com/106560739/185807843-0e2b3a78-71ae-4af9-8751-380381cb0c74.png)
* To filter the UFO data based on sighting country, the user can input their country of interest in the "Enter Country" area of the table. Their change of country is detected and the table is adjusted accordingly. In the image below, the country "ca" was entered and the table only displays this sighting country.
![country](https://user-images.githubusercontent.com/106560739/185807865-1eb92e38-7072-4ca8-8409-586dea927539.png)
* To filter the UFO data based on sighting shape, the user can input their shape of interest in the "Enter Shape" area of the table. Their change of shape is detected and the table is adjusted accordingly. In the image below, the shape "triangle" was entered and the table only displays this sighting shape.
![shape](https://user-images.githubusercontent.com/106560739/185807903-452002a1-7561-4ae7-bbbd-d4f544103a83.png)
* All filters can be entered simultaneously by the user to obtain specific UFO data. In the image below the following was entered: "1/1/2010" for date, "la mesa" for city, "ca" for state, "us" for country, and "triangle" for shape. These changes are detected and the table is adjusted accordingly.
![all filters](https://user-images.githubusercontent.com/106560739/185808113-80095ed1-79dc-4f92-9710-29c43b2b151c.png)
## Summary
### Drawbacks
The current webpage design has one notable drawback: the strict filter parameters increase user difficulty in searching for certain UFO sightings. The user is unable to enter filtering criteria when employing text formats that are different than the ones specified by the placeholders. This means that users cannot use different capitalization nor a different number of spaces between letters when searching for specific sightings. Furthermore, the user must enter the date in only one particular format, as displayed by the placeholder, in order to obtain results. This drawback ultimately does not permit a high level of user-friendliness and makes for a less intuitive website.  
### Recommendations
There are two specific recommendations I believe should be enacted. The first suggestion is to use regex within the code to allow the user to enter text in different formats. This would allow for users to obtain results for sightings regardless of the capitalization, spaces, and date format. For example, using regex in the code would allow the user to enter "CA" or "ca" for the state of California in the "Enter State" filter. This should be applied to all filters. The second suggestion to enhance this website is to include a drop down menu of options for the filter criteria. This menu would display the possible dates, cities, states, countries, and shapes a user can choose to obtain UFO data from. Such an action further develops this website in a positive manner. 
