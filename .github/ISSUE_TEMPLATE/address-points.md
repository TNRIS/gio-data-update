---
name: Address Points
about: Incoming Address Points Dataset Collection
title: "[Address Points Dataset Collection]"
labels: Address Points, new dataset
assignees: ''

---

The owner of this issue (person who opened it) is responsible for ensuring each task is completed. 
Please reassign issues when work is complete. The owner of this issue is responsible for checking in with workmates on progress of each task.

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
- [ ] Create API collection @mitchellryant
- [ ] Complete API console collection form including metadata and description @LaurenKirk 
- [ ] Upload supplemental info (breaklines, reports, index) @LaurenKirk

`If zip file is too large (more than 75MB) please let` @mitchellryant `know and the file can be loaded in another way.`
- [ ] Crop & Upload Images @LaurenKirk
- [ ] Review Description and Formatting @pwblanton https://api.tnris.org/admin/lcd/collection/
- [ ] Add resources  @mitchellryant 

**data.tnris.org v2** @LaurenKirk
- [ ] Create Single polygon coverage, by mergeing all polygons together.
	If your area is county based please use the TxDOT Generalized Boundaries.
	Use Editing Merge, not Merge Tool.    
- [ ] No Vertices, holes, or donuts (unless to directly shows in the data)
- [ ] Projected shape to 4326
- [ ] Generalized shape by 10m
- [ ] Create 50 Char Text field clalled "cllct_id"
- [ ] Populate field to be Collection ID, you can get this from the API console.
- [ ] Convert shape file to json using Feature to JSON tool.
- [ ] Load JSON into API console.


**Download\Prod**
- [ ] Move data to production shares @mitchellryant 
- [ ] Make collection public  @mitchellryant 
- [ ] Inform TNRIS staff of data availability @LaurenKirk
- [ ] Update AGO Map to reflect update @LaurenKirk

**Twitter**
- [ ] Draft Tweet content, link, and image in Comment @LaurenKirk
- [ ] Post Tweet @geochik
