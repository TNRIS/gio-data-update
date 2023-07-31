---
name: Parcels
about: Incoming Parcel Dataset Collection
title: "[Parcel Dataset Collection]"
labels: new dataset, Parcels
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
stratmap19-landparcels_fipscode_countyname_date.extension
stratmap19-landparcels_48001_anderson_201904.shp
stratmap19-landparcels_48001_anderson_201904.gdb
```
- [ ] Quality Assurance @LaurenKirk

**API\data.tnris.org**
- [ ] Create API collection @csidenblad
- [ ] Complete API console collection form including metadata and description @LaurenKirk 
- [ ] Upload supplemental info (breaklines, reports, index) @LaurenKirk

`If zip file is too large (more than 75MB) please let` @csidenblad `know and the file can be loaded in another way.`
- [ ] Crop & Upload Images @LaurenKirk
- [ ] Review Description and Formatting @LaurenKirk
- [ ] Add resources  @csidenblad 
- [ ] Create Single polygon coverage, by merging all polygons together. @LaurenKirk
	1. If your area is county based please use the TxDOT Generalized Boundaries.
	2. Use Editing Merge, not Merge Tool.    
	3. No Vertices, holes, or donuts (unless to directly shows in the data)
	4. Projected shape to 4326
	5. Generalized shape by 10m
	6. Convert shape file to json using Feature to JSON tool. Use Formatted and Geo Options
	7. Load JSON into API console. https://api.tnris.org/admin/lcd/collectionfootprint/

**Download\Prod**
- [ ] Move data to production shares @csidenblad 
- [ ] Make collection public  @csidenblad 
- [ ] Inform TNRIS staff of data availability @LaurenKirk
- [ ] Update AGO Map to reflect update @LaurenKirk

**Twitter**
- [ ] Draft Tweet content, link, and image in Comment @LaurenKirk
- [ ] Post Tweet @lebell @space-longoria
