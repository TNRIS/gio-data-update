---
name: Bathymetry
about: Incoming Bathymetry Dataset Collection
title: "[Dataset Collection Name]"
labels: Bathymetry, new dataset
assignees: @birdladyellen

---

# ***The owner of this issue (person who opened it) is responsible for ensuring each task is completed.***
## ***Please reassign issues when work is complete. The owner of this issue is responsible for checking in with workmates on progress of each task.***
## ***Please remove any task(s) that do not apply***

**Data**
- [ ] Add data to measures spreadsheet @birdladyellen
- [ ] Route Data Shipment [copy data to TNRIS Projects share] @birdladyellen
- [ ] Data Processing [renaming file, data organization, data conversion]  @birdladyellen 
- [ ] Creation of derivative products [hypso and metadata] @birdladyellen
- [ ] Quality Assurance @birdladyellen

**API\data.tnris.org**
- [ ] Create API collection @TNRIS/git-sba
- [ ] Complete API console collection form including metadata and description @birdladyellen 
- [ ] Upload supplemental info (breaklines, reports, index) @birdladyellen

`If zip file is too large (more than 75MB) please let` @TNRIS/git-sba `know and the file can be loaded in another way.`
- [ ] Crop & Upload Images @birdladyellen
- [ ] Review Description and Formatting @birdladyellen
- [ ] Add resources  @TNRIS/git-sba 
- [ ] Create Single polygon coverage, by merging all polygons together. @birdladyellen
	1. If your area is county based please use the TxDOT Generalized Boundaries.
	2. Use Editing Merge, not Merge Tool.    
	3. No Vertices, holes, or donuts (unless to directly shows in the data)
	4. Projected shape to 4326
	5. Generalized shape by 10m
	6. Convert shape file to json using Feature to JSON tool. Use Formatted and Geo Options
	7. Load JSON into API console. https://api.tnris.org/admin/lcd/collectionfootprint/

**Download\Prod**
- [ ] Move data to production shares @TNRIS/git-sba
- [ ] Make collection public  @TNRIS/git-sba
- [ ] Inform GIO staff of data availability @birdladyellen

**QA|QC** 
 **(if collection is made public before 10am you can check after views are refreshed that day)**
 **(if collection is made public after 10am you can check after views are refreshed the next day)**
- [ ] Review new collection card after it appears on data.tnris.org @TNRIS/stratmap 
    1. Visually review text wording & formatting
    2. All metadata complete and correct
    3. Collection Footprint drawing properly

**Twitter**
- [ ] Draft X content, link, and image in Comment @birdladyellen
- [ ] Post X @gwenkruse
