# IronHacks - phase 3

In this third version, the application worked with more data sets, as well as improvements in graphical implementation.

1) **Name of Application:** Knowing Chicago. 

2) **Keywords.**
      * Safety
      * Supervised
      * Affordable Rental

3) **Datasets and function design.**

For now, the data set used in the application is:

* [Police Stations] [https://catalog.data.gov/dataset/police-stations-3a3a8] [Chicago Police district station locations.]

* [Affordable Rental Housing Developments][https://catalog.data.gov/dataset/affordable-rental-housing-developments-ef5c2] [Show the affordable rental housing in the city of Chicago.]

* [Libraries] [https://data.cityofchicago.org/Education/Libraries-Locations-Hours-and-Contact-Information/x8fc-8rcq] [Libraries in the city of Chicago.]

* [Public Art] [https://data.cityofchicago.org/Parks-Recreation/Parks-Chicago-Park-District-Artworks/e9ef-hrzb] [Public Art in the parks of the city of Chicago.]

**[Y/N] Do you use the primary dataset ”online climate data” from data.gov?**  Not yet.

**[Y/N] Are all these datasets from data.gov or data.indy.gov? If not, where are they coming from (links)?**  Yes.


4) **Description.**

The application seeks to provide assistance to new students in the Department of Computer Science - University of Illinois, who have no knowledge of the city of Chicago, especially near the university. The application at this time, offers on the map police stations, libraries, public art parks and affordable rental housing in the city of Chicago, as well as giving the best guarded area, best area with library and best area of housing. rental.
 
**Map View:**

* **[Y/N] Basic Map with specific location (your map is located in a meaningful place, city of west lafayette for example)**  Yes, Department of Computer Science – University of Illinois, Chicago (41.8708° N, 87.6505° W)

* **[Y/N] [describe] Any other cover on the map (for example, cloud cover to show the weather effect)**  Yes, a circle centered on a police station, another in a library and another in a rental house. These represent the closest supervised area, the nearest library area and the nearest profitable home area, respectively.

**Data Visualization:**

* **[Y/N] [describe] Use Graph? What is the type? (bar chart, pie chart, radar chart ...)**  Not.
* **[Y/N] [List] Any interaction available on the graph? List them (enable click on numbers, drag on lines, change time/variables ...)**  Yes, at this time, in addition to having the interaction with the map with a custom button that allows the user to return to the Department of Computer Science - University of Illinois, Chicago (41.8708 ° N, 87.6505 ° W). And the "choose option" button, you can click on each police station, library, affordable rental housing and public artwork, to observe your information. In addition, when obtaining the information of a public artwork will be able to search this one in google images by means of a button.

**Interaction Form:**

* **[Y/N] [List] Any information output? list them. (text field, text area, label, plain HTML ...)**  Yes, In a paragraph of a div, information about each selection is displayed. Another div shows the conventions of the application.

* **[Y/N] [List] Any operation option (filters)? List them. (search markets, search vegetables, filter based on price, sort based on convenience ...)**  Yes, Dropdown that allows to choose the information that the user wants, for example: Search Police Stations.

* **[Y/N] [List] Any information input? List them. (comments, markers, user preference ...)**  No.

* **[Y/N] [List] Interaction with Map? List them. (filter on price will affect map markers, sort on price will affect map markers, ...)**  Yes, Click on a selection to see their information.

* **[Y/N] [List] Interaction with data visualization? List them. (filter, sort, set variables ...)**  Yes, With each data set is the monitored area closest to the university.

5) **Test Case.**

**Which browsers did you test your project on? Chrome, IE, Edge, Safari, or Firefox?**  Google Chrome and Mozilla Firefox.