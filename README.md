# UFOs

### Overview of Project
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, table filters for the city, state, country, and shape were added as well to create a more user friendly environment. 

### Results

#### Search Criteria Procedure
##### Index Page
This is the initial page. The user can re-initialize the page by clicking on the navbar at the top.

##### Filtering by Event Date
The user enters the desired date, the change is detected and the table is updated accordingly.

##### Filtering by City
The user enters the desired city, the change is detected and the table is updated accordingly.

##### Filtering by Country
The user enters the desired country, the change is detected and the table is updated accordingly.

##### Filtering by State and Shape
The user enters the desired state and shape observed, the changes are detected and the table is updated accordingly.

### Summary
- One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis.
- A way to address this would be to present drop-down lists including all filter values in place of the input fields.
- Each list would need to update after a parameter is selected in any filter.
Including a button to clear the filters is also needed. The button would be located below the last filter.
