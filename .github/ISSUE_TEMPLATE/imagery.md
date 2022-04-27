---
name: Imagery
about: Incoming Imagery Dataset Collection
title: "[Imagery Dataset Collection]"
labels: Imagery, new dataset
assignees: ThorTheDestroyer

---

The owner of this issue (person who opened it) is responsible for ensuring each task is completed. 
Please reassign issues when work is complete. The owner of this issue is responsible for checking in with workmates on progress of each task.

**Data**
- [ ] Enter dataset on StratMap Incoming data xlsx sheet @ThorTheDestroyer 
- [ ] Route Data Shipment (copy data to TNRIS Projects share) @ThorTheDestroyer 
- [ ] Data Processing (renaming file, data organization) @mitchellryant
- [ ] Creation of derivative products [compressed images] @ThorTheDestroyer 
- [ ] Quality Assurance @ThorTheDestroyer

**API\data.tnris.org**
- [ ] Create API collection @mitchellryant
- [ ] Complete API console collection form including metadata and description @LaurenKirk 
- [ ] Upload supplemental info (breaklines, reports, index) @LaurenKirk

`If zip file is too large (more than 75MB) please let` @mitchellryant `know and the file can be loaded in another way.`
- [ ] Crop & Upload Images @LaurenKirk
- [ ] Review Description and Formatting @pwblanton https://api.tnris.org/admin/lcd/collection/
- [ ] Add resources  @mitchellryant 
- [ ] Create Single polygon coverage, by merging all polygons together. @ThorTheDestroyer
	1. If your area is county based please use the TxDOT Generalized Boundaries.
	2. Use Editing Merge, not Merge Tool.    
	3. No Vertices, holes, or donuts (unless to directly shows in the data)
	4. Projected shape to 4326
	5. Generalized shape by 10m
	6. Convert shape file to json using Feature to JSON tool. Use Formatted and Geo Options
	7. Load JSON into API console. https://api.tnris.org/admin/lcd/collectionfootprint/

**Download\Prod**
- [ ] Move data to production shares @mitchellryant
- [ ] Make collection public @mitchellryant
- [ ] WMS Link @mitchellryant 
- [ ] Inform TNRIS staff of data availability @ThorTheDestroyer

**Twitter**
- [ ] Draft Tweet content, link, and image in Comment @ThorTheDestroyer 
- [ ] Post Tweet @geochik
