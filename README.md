# bikesharing

[link to dashboard](https://public.tableau.com/app/profile/rahul.raveendran6270/viz/NYCBikesharingStory_16489150847350/BikesharingNYCStory)


### Overview
For this analysis, we have been tasked with creating visualizations for investors for our Bikesharing Service aimed to launch in Des Moines, Iowa. Through the use of a dataset from CitiBike, we imported the data into Tableau, an interactive data visualization software and created visualizations that would aid in our presentation of our proposal for the Bikesharing service. The dataset used is of CitiBike data from August 2019- a time of year in which ridership is undoubtedly high, especially in New York City and will provide a copious amount of beneficial data.

Before certain analyses could be performed, we first had to convert our CSV file's "tripduration" column from an integer to a datetime datatype. Through the use of Jupyter Notebook and Pandas, we created an updated CSV file and imported it to our Tableau workbook to create an imporved visualization.

![Screen Shot 2022-04-02 at 12 19 37 PM](https://user-images.githubusercontent.com/95504135/161391894-e2413b36-3c58-49a0-84be-6e1509fbc8fd.png)

### Reults
![Screen Shot 2022-04-02 at 12 21 35 PM](https://user-images.githubusercontent.com/95504135/161391952-c11f5d4f-f591-4404-9384-233e3c7fbbd8.png)
These graphs show the top locations that rides begin and end. As shown by the shade of the color (darker shades indicating a higher rate of start and stop locations) we can see what locations may need more bikes to keep up with the demand of the location.

![Screen Shot 2022-04-02 at 12 35 05 PM](https://user-images.githubusercontent.com/95504135/161392538-42921274-56ba-4a07-bade-08db8bc3abe8.png)

This heatmap visualization shows the days and times that the service is mostly used. Indicated by the darker shades, we can see that throughout the weekdays, between the hours of 7am to 9am and 5pm to 7pm, the service is heavily used, likely by commuters going to and from work.

![Screen Shot 2022-04-02 at 12 35 24 PM](https://user-images.githubusercontent.com/95504135/161392542-8d4fbf68-d109-418a-9700-5e6800bd0cf7.png)
Building on the previous heatmap, this visualization adds Gender as a filter showing the usage of the service across genders. We can see that between males and females the service is used around the same times but the males using the service significantly more.

![Screen Shot 2022-04-02 at 12 35 41 PM](https://user-images.githubusercontent.com/95504135/161392546-81afccd5-fb01-496f-a939-5709cedd0f8a.png)

This heatmap shows the user trips by gender and weekday. Here we see that the largest demographic of users are male subscribers.

![Screen Shot 2022-04-02 at 12 39 33 PM](https://user-images.githubusercontent.com/95504135/161392604-4f4081a7-e316-4278-ae7d-89df06911f06.png)

![Screen Shot 2022-04-02 at 12 39 49 PM](https://user-images.githubusercontent.com/95504135/161392609-8250467c-2e1a-4f46-a0ae-4f55fbd01639.png)


### Summary
Tableau is a great program primarily because of its simplicity and ease of use, because of this there are numerous amounts of visualizations that could be made - additional visualizations could also be made that would be beneficial for this project:
- A visulizaton that would show the correlation between Gender and Usertype could give insight as to what amount of Bikeshare users are customers or subscribers. This visualization could give insight to what demographic we could potentially advertize to, to come aboard as subscribers and not just customers.
- We can also create a visualization that combines Gender, Birth Year, and Trip Duration to gain insight on the demographic of high and low use of the service based on age and gender.
