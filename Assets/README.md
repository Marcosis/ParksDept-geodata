# Philadelphia Parks and Recreation Assets

### Summary  

PPR Assets are Philadelphia Parks and Recreation owned buildings and facilities  that can be used for programming and inventory purposes. Several buildings that are within Philadelphia parks are included only if they are owned by Parks and Recreation. Facilities are primarily owned by Philadelphia Parks and Recreation but there is instances were a property may be owned by a school district, the city, or an unknown source.  
  
-Features updated: 12/19/2012  
-Attributes updated: 12/19/2012  
-Metadata updated: 12/20/2012

### Description  

Created from the original PPR_Buildings, PPR_Assets, PPR_Boundaries shapefiles (Philadelphia Parks and Recreation). Through meetings and outside sources, this layer was updated manually. Some sources include: Philadelphia Parks and Recreation, Philadelphia Water Department (shapefiles provided), OPA Web Source, and CPO ownership tables. The layer includes all properties and buildings owned and/or managed by Philadelphia Parks and Recreation. Several Fields below are classified as domains. Please see additional content below for this information.-Data Development:Polygons from both PPR_Buildings, PPR_Boundaries, and PPR_Assets were mergedCreated new attribute fields in order to include the ones listed in "key attributes"Several meetings with Philadelphia Parks and Recreation staff occured in order to create a more readable and clear system for all usersManual data entry occured frequentlyEdited several polygons to ensure the most up to date property linesData sources include: Philadelphia Parks and Recreation, Philadelphia Water Department (shapefiles provided), OPA Web Source, and CPO ownership tables-Key Attributes:DOMAIN FIELDS ARE WRITTEN IN BOLDAsset Name: Name of building, structure, or land asset. All records have an entry.Site Name: Name in which multiple asset names at a single facility may be grouped. This field could also be seen as the polygon which lies inside of a facility polygon. For example, the Vogt recreation center building falls within the Vogt Recreation Center land area. All records have an entry.Child Of: Site in which the "Site Name" Field record lies within. Not all records have this entry.Address: The address of the park or recreation center. Not all records have this entry.Type: Classification of Asset by land, building, or structure. All records have an entry.Use: The primary use of the Asset. All records have an entry.Description: Further description of use of the Asset. Not all fields have a description.Sq Feet: Sq foot of a building or structure Asset. Only building or structure records have this entry.Acreage:Acreage of a land Asset. Only land (facility) Assets records have this entry.Fields: The number of athletic fields on an asset. Categorized as single, multiple, or none. Does not include Ice Rinks. All records have an entry.Courts: The number of athletic courts on an asset. Categorized as single, multiple, or none. Does not include Ice Rinks. All records have an entry.Play Equipment: Classified by 2-5, 5-12, Both or none if the asset has playground equipment. The numbers are representing the age groups which the equipment is desired for. All records have an entry.Ice Rinks: Classified by single or none, This field represents if an asset contains a ice rink or not. Ice rink records are applied to either the building or the land asset, not both. All records have an entry. Spray Grounds: Classified by single or none, This field represents if an asset contains a spray ground or not. All records have an entry.Pool: Classified by indoor, outdoor, or none. This field represents if an asset contains a pool or not. All records have an entry.Former Dept: The former department of Philadelphia Parks and Recreation, Dept of Recreation or Fairmount Park, who handled the Asset before the merge of the departments. Entries include Fairmount Park, Dept of Recreation, or Both-PPR. Both-PPR states that the property was aquired during or after the merge. All records have an entry.Main By: The department principally responsible for building or land structural maintenance. All records have an entry.Owner: Owner of the Asset. Classified as PPR, City, Other, ?, or School District. Other is a category that is not recommended for use. All records have an entry.CPO Owner: Additional owner information provided from a CPO table. Not all records have this entry.OPA Owner: Additional owner information provided from the OPA web source. http://opa.phila.gov/opa.apps/Search/SearchForm.aspx?url=search Not all records have this entry.PWD Owner: Additional owner information provided from the PWD Parcels layer. Not all records have this entry.Other Owner: Additional owner information. Not all records have this entry.OPM:Council Dist: Council district which the Asset lies within. All records have an entry.District: Philadelphia Parks and Recreation district which the Asset lies within. All records have an entry.Zipcodes: Philadelphia Zipcode which the Asset falls within. All records have an entry.Allias: Another name that an Asset my be refered to. Not all records have this entry.Chronology: Year in which Asset was built or founded.Notes: Additional field to apply any notes about asset that can not be categorized in any other field.Date Edited: Date in which the Asset was last edited. This field was created to ensure data accruacy and updates needed or varified. All records have an entry.Edited By: Data editor name from Philadelphia Parks and Recreation. Domains include: Vanessa Miller, Regina Stine, Nora Dougherty, and Andy Viren. All records have an entry.-Domains: The domain information can be found within the geodatabase of the PPR_Assets_2012 feature class.Use:B1 Athletic, B2 Barn, B3 Batting Cage, B52 Boathouse, B4 Community Park, B6 Concessiongs\Retal\Cafe, B47 Dugout, B8 Environmental Education Center, B53 Farm, B10 Garage\Maintenance\Storage, B56 Gardens, B46 Golf, B11 Greenhouse\Nursary, B51 Guard Box, B13 Historic House, B14 Ice Rink, B15 Linear Park\Parkway, B16 Lot\Breezeway\Island, B17 Metropolitan Park, B18 Mini Park, B55 Multi-Use Area, B38 Multi-Use Bldg, B20 Museum, B21 Neighborhood Park, B22 Older Adult Center, B23 Other (Not Recommended), B25 Pavilion\Shelter, B27 Pool, B49 Pumping Station, B28 Recreation Bldg, B29 Recreation Center, B30 Recreation Site, B32 Regional\Watershed Park, B33 Restrooms, B34 Shed, B37 Square\Plaza, B38 Stables, B39 Stage\Stands, B40 Statue\Monument\Sculpture, B43 Watershed\Conservation Park, B54 Weigh Station, B44 Youth &amp; Tot\Play Areas, B45 Zoo HabitatDescription: C7 Baseball Field, C11 Bocce Courts, C10 Disc Golf, C1 Golf Course, C2 Golf Driving Range, C3 Historic Building, C6 Historic Structure, C9 Hockey Rink, C4 Multi-Use Bldg, C8 Multi-Use Sports Field, C14 Performance Venue, C12 Recycling Center, C5 Regional\Watershed, C13 Tennis CourtsType: G1 Building, G2 Land, G3 StructureFormer Department: J1 Fairmount Park, J2 Dept of Recreation, J3 Both - PPROwner: I1 PPR, I2 City, I3 Other (Not Recommended), I4 ?, I5 School DistrictCourts: D1 Multiple, D2 Single, D3 NoneFields: A1 Multiple, A2 Single, A3 NonePlay Equipment: E1 2-5, E2 5-12, E3 Both, E4 NoneIce Rinks: M1 None, M2 SinglePool: F2 Indoor, F3 Outdoor, F4 NoneSpray Grounds: L1 Single, L2 NoneEdited By: K1 Nora Dougherty, K2 Vanessa Miller, K3 Regina Stine, K4 Andy Viren-Coordinate System:Lambert Conformal Conic, NAD83, PA South Stateplane coordinates, US Foot.-Thematic Mapping:If necessary use the Asset Name field for mapping and labeling  

### Data Dictionary

| Field | Description  
| ----- | :----------:  
| ASSET_NAME | Name of building, structure, or land asset. All records have an entry. 
| SITE_NAME | Name in which multiple asset names at a single facility may be grouped. This field could also be seen as the polygon which lies inside of a facility polygon. For example, the Vogt recreation center building falls within the Vogt Recreation Center land area. All records have an entry. 
| CHILD_OF | Site in which the "Site Name" Field record lies within. Not all records have this entry. 
| ADDRESS | The address of the park or recreation center. Not all records have this entry. 
| TYPE | Classification of Asset by land, building, or structure. All records have an entry. 
| USE | The primary use of the Asset. All records have an entry. 
| DESCRIPTIO | Further description of use of the Asset. Not all fields have a description. 
| SQ_FEET | Sq foot of a building or structure Asset. Only building or structure records have this entry. 
| ACREAGE | Acreage of a land Asset. Only land (facility) Assets records have this entry. 
| FIELDS | The number of athletic fields on an asset. Categorized as single, multiple, or none. Does not include Ice Rinks. All records have an entry. 
| COURTS | The number of athletic courts on an asset. Categorized as single, multiple, or none. Does not include Ice Rinks. All records have an entry. 
| PLAY_EQUIP | Classified by 2-5, 5-12, Both or none if the asset has playground equipment. The numbers are representing the age groups which the equipment is desired for. All records have an entry. 
| SPRAY_GROU | Classified by single or none, This field represents if an asset contains a spray ground or not. All records have an entry. 
| POOL | Classified by indoor, outdoor, or none. This field represents if an asset contains a pool or not. All records have an entry. 
| FORMER_DEP | The former department of Philadelphia Parks and Recreation, Dept of Recreation or Fairmount Park, who handled the Asset before the merge of the departments. Entries include Fairmount Park, Dept of Recreation, or Both-PPR. Both-PPR states that the property was aquired during or after the merge. All records have an entry. 
| MAIN_BY | The department principally responsible for building or land structural maintenance. All records have an entry. 
| OWNER | Owner of the Asset. Classified as PPR, City, Other, ?, or School District. Other is a category that is not recommended for use. All records have an entry. 
| CPO_OWNER | Additional owner information provided from a CPO table. Not all records have this entry. 
| OPA_OWNER | Additional owner information provided from the OPA web source. http://opa.phila.gov/opa.apps/Search/SearchForm.aspx?url=search Not all records have this entry. 
| PWD_OWNER | Additional owner information provided from the PWD Parcels layer. Not all records have this entry. 
| OTHER_OWNE | Additional owner information. Not all records have this entry.  
| COUNCIL_DI | Council district which the Asset lies within. All records have an entry. 
| DISTRICT | Philadelphia Parks and Recreation district which the Asset lies within. All records have an entry. 
| ZIPCODE | Philadelphia Zipcode which the Asset falls within. All records have an entry. 
| ALLIAS | Another name that an Asset my be refered to. Not all records have this entry. 
| CHRONOLOGY | Year in which Asset was built or founded. 
| NOTES | Additional field to apply any notes about asset that can not be categorized in any other field. 
| DATE_EDITE | Date in which the Asset was last edited. This field was created to ensure data accruacy and updates needed or varified. All records have an entry. 
| EDITED_BY | Data editor name from Philadelphia Parks and Recreation. Domains include: Vanessa Miller, Regina Stine, Nora Dougherty, and Andy Viren. All records have an entry. 
| ICE_RINKS |  
| SHAPE_AREA |  
| SHAPE_LEN |  


Domains: The domain information can be found within the geodatabase of the PPR_Assets_2012 feature class.

Use:B1 Athletic, B2 Barn, B3 Batting Cage, B52 Boathouse, B4 Community Park, B6 Concessiongs\Retal\Cafe, B47 Dugout, B8 Environmental Education Center, B53 Farm, B10 Garage\Maintenance\Storage, B56 Gardens, B46 Golf, B11 Greenhouse\Nursary, B51 Guard Box, B13 Historic House, B14 Ice Rink, B15 Linear Park\Parkway, B16 Lot\Breezeway\Island, B17 Metropolitan Park, B18 Mini Park, B55 Multi-Use Area, B38 Multi-Use Bldg, B20 Museum, B21 Neighborhood Park, B22 Older Adult Center, B23 Other (Not Recommended), B25 Pavilion\Shelter, B27 Pool, B49 Pumping Station, B28 Recreation Bldg, B29 Recreation Center, B30 Recreation Site, B32 Regional\Watershed Park, B33 Restrooms, B34 Shed, B37 Square\Plaza, B38 Stables, B39 Stage\Stands, B40 Statue\Monument\Sculpture, B43 Watershed\Conservation Park, B54 Weigh Station, B44 Youth & Tot\Play Areas, B45 Zoo Habitat

Description: C7 Baseball Field, C11 Bocce Courts, C10 Disc Golf, C1 Golf Course, C2 Golf Driving Range, C3 Historic Building, C6 Historic Structure, C9 Hockey Rink, C4 Multi-Use Bldg, C8 Multi-Use Sports Field, C14 Performance Venue, C12 Recycling Center, C5 Regional\Watershed, C13 Tennis Courts

Type: G1 Building, G2 Land, G3 Structure

Former Department: J1 Fairmount Park, J2 Dept of Recreation, J3 Both - PPR

Owner: I1 PPR, I2 City, I3 Other (Not Recommended), I4 ?, I5 School District

Courts: D1 Multiple, D2 Single, D3 None

Fields: A1 Multiple, A2 Single, A3 None

Play Equipment: E1 2-5, E2 5-12, E3 Both, E4 None

Ice Rinks: M1 None, M2 Single

Pool: F2 Indoor, F3 Outdoor, F4 None

Spray Grounds: L1 Single, L2 None

Edited By: K1 Nora Dougherty, K2 Vanessa Miller, K3 Regina Stine, K4 Andy Viren





### Credits  

Nora K. Dougherty, Geospatial Analyst, nora.dougherty@phila.gov
Philadelphia Parks and Recreation  
1515 Arch Street, 10 Fl, Philadelphia, PA  19102-1583  
215.683.0235
  

### Use Limitations  

The City of Philadelphia makes no representation about the accuracy of any specific information in this GIS data and is provided as is and without Warranty of any kind. The user of this data will assume complete responsibility for any and all occurrences resulting from its use or display and will hold the City of Philadelphia harmless from any and all claims, demands, liabilities, obligations, damages, suits, judgments or settlements, including reasonable costs and attorneys' fees, that arise from use of this data.