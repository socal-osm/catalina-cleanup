# Catalina Island data cleanup
In preparation for a trip to Catalina Island, let's arm-chair map as much as we can.

![catalina-osm](https://cloud.githubusercontent.com/assets/695934/17864843/999f94ba-6854-11e6-8712-23ef87b2e4a9.png)


## Tasks
- Import [176 fire hydrants](https://github.com/socal-osm/catalina-cleanup/blob/master/data/fire-hydrants.geojson) to OpenStreetMap
- Clean up roads
- Import addresses for the island
- ..and more..

## Address data attributes
per the [county's description](http://egis3.lacounty.gov/dataportal/2012/06/19/la-county-address-points/):

- AIN - Parcel this address falls inside
- Numprefix - Number prefix
- Number - House Number
- NumSuffix - House Number Suffix (1/2, 3/4 etc)
- PreMod - Prefix Modifier
- PreDir - Prefix Direction (E, S, W, N)
- PreType - Prefix Type (Ave, Avenida, etc)
- STArticle - Street Article (de la, les, etc)
- StreetName - Street Name
- PostType - Post Type (Ave, St, Dr, Blvd, etc)
- PostDir - Post Direction (N, S, E, W)
- PostMod - Post Modifier (OLD, etc)
- A series of building and floor information fields - not currently filled out
- UnitType - Unit Type (#, Apt, etc) - where these are known
- UnitName - Unit Name (A, 1, 100, etc)
- Zipcode - Zipcode
- Zip4 - Not currently filled out
- LegalComm - Legal City or primary postal city in Unincorporated Areas
- PostComm1 - Primary Postal Community
- PostComm2 - Secondary Postal Community
- PostComm3- Third Postal Community
- Source - source of the address point, including
- Assessor - LA County Assessor parcel centroid with the Situs Address - primary address only
- LACity - City of Los Angeles - primary and secondary with unit numbers
- Regional Planning - source is the LA County House Numbering Maps - primary and secondary addresses
- other agencies - will provide more details soon.
- SourceID - ID of the Address in the source system
- MADrank - Method Accuracy Description (MAD) provides a number between 1 and 100 detailing the accuracy of the location.
- PCITY1 - 1st postal city (from the USPS)
- PCITY2 - 2nd postal city (from the USPS)
- PCITY3 - 3rd postal city (from the USPS)
- 

## More resources
- [Catalina Island Co. maps](http://www.visitcatalinaisland.com/island-info/maps) could be used for reference, but not to copy directly into OSM
- [Catalina Conservancy maps](https://www.catalinaconservancy.org/index.php?s=general&p=map_island) again, not to copy but could be used for place names or feature help
