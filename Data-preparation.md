#	CRS and Data preparation 
## CRS
- All source layers arrived in EPSG 4326
- Reprojected to EPSG 32622, UTM Zone 32N
- Ezinihitte LGA boundary: Extracted from Grid3 wards version v3.0
- All layers clipped to Ezinihitte LGA boundary and exported as geopackages
- Area check: 112.818 square kilometers. Matches published figures which states that Ezinihitte has an area of 113 square kilometers
-  Working files in data/processed/, raw files untouched and not pushed to GitHub due to large file sizes. Only the processed files were pushed because they have manageable file sizes.
- completeness: Sufficient coverage from my observation
- currency: November, 2024
- positional: roads align well with satellite imagery, no systematic offset is visible.
