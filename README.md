This is an app that shows a map centered on downtown Toronto, and an input
search box for the user.
When the user enters a search, the “term” and “geo” query params are used to query 500px endpoint API and only
return photos within 50 km of downtown Toronto.
For each photo returned, a marker on the maps is placed. Added an info window to
the marker that shows the photo and some information about the photo when
the user clicks on the marker.
