# DATA NOTES

## GRID3 Nigeria operation Wards v1.0
DOWNLOADED: 13-09-2026
- 16 features, Polygons
SOURCE:Http//data.grid3.org
-COLUMNS: globalid(number),uniqueid(number),timestamp(date),editor(text),wardename(text),wardcode(text)LGANAME(text), LGACODE(number),statename(text),statecode(text),Amapcode(text),status(text),source(text),Urban(text)

-No nulls in ward_name
-covers my L.G.A fully

## GRID3 Nigeria health facilities v3.0
DOWNLOADED: 13-09-2026
- 51022 features, Polygons
SOURCE:Http//data.grid3.org
-COLUMNS: globalid(number),nhfr_uid(number),nhfr_facil(date),country(text),iso(text),state(text)LGA(text), LGA_name_d(number),ward(text),facility_n(text),facility_1(number),ownership(text),ownership_(text),facility_1(text)facility_2(text),
latitude(number)longitude(number),Geocoordin(text),Last_updat(number)
-No nulls in ward_name
-covers my L.G.A fully

## OSM ROADS, Extracted Via QuickOSM
- Query: highway=*within ibadan North Extent
- Extracted: 13-09-2026
- many have no surface tag, so paved and unpaved cannot be separated everwhere
- coverage looks good in the built-up area, sparse at the edges

## https://hub.worldpop.org/geodata/summary?id=74733&utm_source
DOWNLOADED: 13-09-2026
this is a raster dataset
-covers my L.G.A fully
