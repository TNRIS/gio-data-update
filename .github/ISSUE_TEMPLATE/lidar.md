---
name: Lidar
about: Incoming Lidar Dataset Collection
title: "[Dataset Collection Name]"
labels: Lidar, new dataset
assignees: birdladyellen

---

# ***The owner of this issue (person who opened it) is responsible for ensuring each task is completed.***
## ***Please reassign issues when work is complete. The owner of this issue is responsible for checking in with workmates on progress of each task.***
## ***Please remove any task(s) that do not apply***

**Data**
- [ ] Add data to measures spreadsheet @birdladyellen
- [ ] Route Data Shipment [copy data to TNRIS Projects share] @birdladyellen
- [ ] Data Processing [renaming file, data organization, data conversion] @birdladyellen
- [ ] Creation of derivative products [hypso and metadata] @birdladyellen
- [ ] Quality Assurance @birdladyellen

**API\data.tnris.org**
- [ ] Create API collection @csidenblad
- [ ] Complete API console collection form including metadata and description @birdladyellen 
- [ ] Upload supplemental info (breaklines, reports, index) @birdladyellen

`If zip file is too large (more than 75MB) please let` @csidenblad `know and the file can be loaded in another way.`
- [ ] Crop & Upload Images @birdladyellen
- [ ] Review Description and Formatting @birdladyellen
- [ ] Add resources  @csidenblad 
- [ ] Create Single polygon coverage, by merging all polygons together. @birdladyellen
	1. If your area is county based please use the TxDOT Generalized Boundaries.
	2. Use Editing Merge, not Merge Tool.    
	3. No Vertices, holes, or donuts (unless to directly shows in the data)
	4. Projected shape to 4326
	5. Generalized shape by 10m
	6. Convert shape file to json using Feature to JSON tool. Use Formatted and Geo Options
	7. Load JSON into API console. https://api.tnris.org/admin/lcd/collectionfootprint/

**Download\Prod**
- [ ] Move data to production shares @csidenblad
- [ ] Update Lidar Selector feature class & downloadable index @csidenblad
- [ ] Make collection public  @csidenblad
- [ ] Inform TNRIS staff of data availability @birdladyellen
- [ ] Update AGO Map to reflect new collection @birdladyellen

**Twitter**
- [ ] Draft X content, link, and image in Comment @birdladyellen
- [ ] Post X @lebell @space-longoria
