pythonGeocodeWithGeopy

Sample geocoding trials and scripts using Geopy geocoders.
Use xxxxxxApi.py version only if one has the necessary API key from each of the services

xxxx_GeocodedAll.csv files are the results from geocodeBatchApi.py - usages were:
- python geocodeBatchApi.py test7.csv StreetAddress City State ZipCode
- python geocodeBatchApi.py rural7.csv address city state zip
- python geocodeBatchApi.py japan7.csv address country
- python geocodeBatchApi.py england7.csv address country

where:
- test7.csv : seven random Chicago addresses
- rural7.csv : seven rural addresses in Kentucky - harder to geocode, open source geocoder wouldn't geocode the area
- japan7.csv : seven addresses of selected hostels in a popular old town in Japan - testing unicode input
- england7.csv : seven addresses of hostels in Oxford, England - curious how well we can geocode England address
