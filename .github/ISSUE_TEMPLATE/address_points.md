---
name: Address Points
about: Incoming Address Points Dataset Collection
title: "[Address Points Dataset Collection]"
labels: Address Points, new dataset
assignees: LaurenKirk

---

# ***The owner of this issue (person who opened it) is responsible for ensuring each task is completed.***
## ***Please reassign issues when work is complete. The owner of this issue is responsible for checking in with workmates on progress of each task.***
## ***Please remove any task(s) that do not apply***

**Data**
- [ ] Add data to measures spreadsheet @LaurenKirk 
- [ ] Route Data Shipment [copy data to TNRIS Projects share] @LaurenKirk
- [ ] Data Processing [renaming file, data organization]  @LaurenKirk
```
naming convention for shape and fgdb.
stratmap19-addresspoints_fipscode_countyname_date.extension
stratmap19-addresspoints_48001_anderson_201904.shp
stratmap19-addresspoints_48001_anderson_201904.gdb

```
- [ ] Quality Assurance @LaurenKirk

**API\data.tnris.org**
- [ ] Create API collection @TNRIS/git-sba
- [ ] Complete API console collection form including metadata and description @LaurenKirk 
- [ ] Upload supplemental info (breaklines, reports, index) @LaurenKirk

`If zip file is too large (more than 75MB) please let` @TNRIS/git-sba `know and the file can be loaded in another way.`
- [ ] Crop & Upload Images @LaurenKirk
- [ ] Review Description and Formatting @LaurenKirk
- [ ] Add resources  @TNRIS/git-sba
- [ ] Create Single polygon coverage, by merging all polygons together. @LaurenKirk
	1. If your area is county based please use the TxDOT Generalized Boundaries.
	2. Use Editing Merge, not Merge Tool.    
	3. No Vertices, holes, or donuts (unless to directly shows in the data)
	4. Projected shape to 4326
	5. Generalized shape by 10m
	6. Convert shape file to json using Feature to JSON tool. Use Formatted and Geo Options
	7. Load JSON into API console. https://api.tnris.org/admin/lcd/collectionfootprint/'
	
**Download\Prod**
- [ ] Move data to production shares @TNRIS/git-sba
- [ ] Make collection public  @TNRIS/git-sba
- [ ] Inform GIO staff of data availability @LaurenKirk

**QA|QC** 
 **(if collection is made public before 10am you can check after views are refreshed that day)**
 **(if collection is made public after 10am you can check after views are refreshed the next day)**
- [ ] Review new collection card after it appears on data.tnris.org @TNRIS/stratmap 
    1. Visually review text wording & formatting
    2. All metadata complete and correct
    3. Collection Footprint drawing properly

**Twitter**
- [ ] Draft X content, link, and image in Comment @LaurenKirk
- [ ] Post X @lebell @space-longoria
