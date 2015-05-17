#### convert from shapefile to geojson 
all files are projected CAPE EPSG:4222

	ogr2ogr -f 'GeoJSON' -s_srs EPSG:4222 -t_srs EPSG:4326 geojson/villages.geojson "SHAPEFILES/villages.shp"