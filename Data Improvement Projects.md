### Data Modelling
- The primary focus of work is adding missing roads and adjust alignment thereby enhancing the existing data of Indonesia in OSM.
In some cases, the existing road network has been mapped incorrectly, meaning that some features are missing or may be in-accurately 
mapped. We plan to use a variety of imagery sources to help map the geometry more accurately.

### Improvements that will be addressed include the following:
- Adding missing roads
- Adjusting road alignment as per imagery and GPS traces
- Validate existing tags like-  classification - Residential, Trunk, Motorway etc and attributes - Bridge, Tunnel, links etc.
- Cities might be revisited basis new improvements and or internal requirement.

### Process Flow
- Grab smoothened GPS traces(internal and non-downloadable file)
- Find best imagery properly aligned per GPS traces and ground truth
- Use JOSM with GPS traces and best imagery as reference 
- Visually identify missing roads and add them
- Correct classification and attribute errors in existing data
- Run validation and fix all errors and warnings
- Upload changeset with appropriate comments

### Data Processing
Road Extraction and Validation
We only contribute roads to OSM in areas served by Grab.  Here is an example of where we have added missing roads in Jakarta.
  
### Mapping Guidelines
 - Grab will follow [OSM] (https://wiki.openstreetmap.org/wiki/Highways)
 global and local policies, along with any other guidelines as appropriate.
 - Grab will also reach out to local OSM communities before begining work, to gather feedback, suggestions and learn more about 
 the data and tags used in that area.
 - Data sources and imagery we will use are listed here. Grab will research and use local tags and defer to local mappers, and also 
 check the JOSM history on items to see why previous edits and changes were made.
 
### Tools
- The team will use [JOSM](https://josm.openstreetmap.de/) for completing the task. JOSM has the OSM and Grab GPS traces (internal and non-downloadable file), and 
validation warnings for road networks and other possible issues that are important to prevent improper changes.
 
 ### Changeset Comments
 - The team will provide changeset comments that are in compliance with OSM changeset [guidelines]
 (https://wiki.openstreetmap.org/wiki/Good_changeset_comments).

### Error Detection
 - Grab will use various QA and data quality tools such as JOSM validation warnings and errors, as well as best practices on data quality from the [OpenstreetMap Wiki page](https://wiki.openstreetmap.org/wiki/OSM_Tasking_Manager/Validating_data) and 
 [LearnOSM](http://learnosm.org/en/coordination/review/).
