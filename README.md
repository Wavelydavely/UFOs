# UFOs

Overview of Project:

Dana originally wanted to build a website where people can search for UFO sightings, using dates as a search criteria. After this site was successfully launched, she decided to expand her project to allow users to filter by city, state, country, and shape of the object.


Results:

Our website has been designed to be very user-friendly and intuitive. In order to search for any criteria, we just need to enter such criteria into the search fields. We can also filter multiple criteria simultaneously by entering into more than one field at a time.


Summary:

We have noticed that the filter does not recognize entries that do not match values in the data file verbatim. If a user wants to view events from Wisconsin, they must type 'wi'- not 'Wisconsin' or Wi, etc. This also includes date types when a single digit month uses two digits including a zero (January, for example, as 01). In order to remedy this, we will need to dig a little deeper into data types, and adjust the code accordingly. We may need to use regex.