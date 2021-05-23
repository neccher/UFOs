# UFOs

## Overview
The date filter worked great but we wanted our users to be able to filter the UFO data with multiple criteria. This way they could pinpoint the exact encounter they had in mind and learn more about it.

## Analysis
When a user visits our website and scrolls down to the table, it is presented completely unfiltered with the filtering fields on the left.
(Unfiltered)![image](https://user-images.githubusercontent.com/79211628/119201656-f677d600-ba54-11eb-8355-f63314bd520f.png)

The user can then narrow down the results by entering one or more criteria in the filters.  For example, say a user wanted to see all UFO sightings in El Cajon.  They would simply type El Cajon where it says, "Enter City."
(El Cajon)![image](https://user-images.githubusercontent.com/79211628/119202022-99c8eb00-ba55-11eb-9910-091b97cba6a1.png)

That same user can keep filtering until they get the exact scenario they are looking for.  For example, a UFO sighting in El Cajon on 1/1/2010, where the shape was a light.
(Completely filtered)![image](https://user-images.githubusercontent.com/79211628/119202230-f75d3780-ba55-11eb-896b-46fe009cde4c.png)

## Summary
Unfortunately, not all websites are perfect.  I think taking the search button made the filtering process a little less intuitive.  The user may not know they have to hit enter after typing their desired search criteria.

A few recommendations to make the website easier to use would be to make the date filter accept multiple date formats.  I assume that would require changing the actual data from a string to a datetime.  Finally, I would like to add an option for a user to record their own UFO sighting so that we could keep growing our data table.
