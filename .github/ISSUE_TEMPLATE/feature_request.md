---
name: Building Footprints
about: New Building Footprints for lidar collection or Update complete collection
title: "[Building Footprints]"
labels: Building Footprints, new dataset
assignees: 'mapvon'

---

# ***The owner of this issue (person who opened it) is responsible for ensuring each task is completed.***
## ***Please reassign issues when work is complete. The owner of this issue is responsible for checking in with workmates on progress of each task.***

**Data**
- [ ] Quality Assurance @mpavon
- [ ] Data Processing [renaming file, data organization]  @mpavon
```
naming convention for shape and fgdb.
stratmap_2020_balmorhea_davis_mountains_building_footprint.shp
stratmap-2020-balmorhea-davis-mountains_3d-buildings.gdb
```

**API\data.tnris.org**
- [ ] Upload zipped footprints (breaklines, reports, index) @mpavon

`If zip file is too large (more than 75MB) please let` @mitchellryant `know and the file can be loaded in another way.`
- [ ] Crop & Upload Images @mpavon
- [ ] Review Description and Formatting @pwblanton https://api.tnris.org/admin/lcd/collection/
- [ ] Add resources  @mitchellryant 
- [ ] Create Single polygon coverage, by merging all polygons together. @mpavon
	1. If your area is county based please use the TxDOT Generalized Boundaries.
	2. Use Editing Merge, not Merge Tool.    
	3. No Vertices, holes, or donuts (unless to directly shows in the data)
	4. Projected shape to 4326
	5. Generalized shape by 10m
	6. Convert shape file to json using Feature to JSON tool. Use Formatted and Geo Options
	7. Load JSON into API console. https://api.tnris.org/admin/lcd/collectionfootprint/'
	
**Download\Prod**
- [ ] Move data to production shares @mitchellryant 
- [ ] Make collection public  @mitchellryant 
- [ ] Inform TNRIS staff of data availability @mpavon
- [ ] Update AGO Map to reflect update @mpavon

**Twitter**
- [ ] Draft Tweet content, link, and image in Comment @mpavon
- [ ] Post Tweet @lebell @space-longoria
