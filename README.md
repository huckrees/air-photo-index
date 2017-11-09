# air-photo-index
Special Collections is developing digital air photo indexes for air photo collections held in the Map Collection.  The purpose of this project is to locate individual photos in space to assist patrons in finding photos that relate to a particular location.

# Attribute Data Definitions
Attribute data is data about each photo whose footprint is added to a photoset.

identifier | type | description | example
---| --- | --- | ---
Author | text | The code indicating the Author-Creator for the photos | USCE
FlightID | text | The code assigned by the aerial photography company to identify the set of photos take on a particular flight | AM
FlightNumber | integer | | 1
FrameNumber | integer | A number identifying a single photo in a given flight | 12
Date | date | Date in YYYY-MM-DD format | 2017-01-30
Time | time | Time in 24 hour format; HH:MM:SS | 15:34:00
Scale | integer | the denominator of the scale fraction | 24000
Used_Maps | text | A description of the maps used as a reference when digitizing the photo corners | USGS Topo Quad “San Francisco, Cal.”, scaled 1:250,000, edition of 1956, revised 1980; Google Satellite accessed 2017-11-08

# Metadata
Metadata is data about an entire photoset.

identifier | type | description | example
---| --- | --- | ---
UC Davis Library Call Number | text | the call number for the photo set found in the UC Davis Library catalog | G4362.A42A4 1986 .U6
Description | text | a brief description of the location of the photo set | American River and Basin
