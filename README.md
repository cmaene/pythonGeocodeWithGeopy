pythonGeocodeWithGeopy

Sample geocoding trials and scripts using Geopy geocoders. 

xxxx_GeocodedAll.csv files are the results from geocodeBatch.py - usages were:
- python geocodeBatch.py test7.csv StreetAddress City State ZipCode
- python geocodeBatch.py rural7.csv address city state zip
- python geocodeBatch.py japan7.csv address country
- python geocodeBatch.py england7.csv address country

where:
- test7.csv : seven random Chicago addresses
- rural7.csv : seven rural addresses in Kentucky - harder to geocode, open source geocoder wouldn't geocode the area
- japan7.csv : seven addresses of selected hostels in a popular old town in Japan - testing unicode input
- england7.csv : seven addresses of hostels in Oxford, England - curious how well we can geocode England address
