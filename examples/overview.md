# Examples

The examples below are examples of GeoPackage files that are currently provided. Note: they don't comply to any official encoding rule as we do not yet have such a rule.

| Country | Theme | Comment |
| --- | --- | --- |
| DK | Addresses | THe Danish Agency for Data Supply has published a first draft of a GeoPackage file with all Danish addresses (11 GB). See the metadata at https://geodata-info.dk/srv/eng/catalog.search#/metadata/50b921ea-935e-d605-2287-4ee364046795, and see some background information in [the (updated) presentation from the 62nd MIG-T meeting](https://webgate.ec.europa.eu/fpfis/wikis/display/InspireMIG/62nd+MIG-T+meeting+2020-07-02?preview=/527439698/580880283/20201012%20MIG-T%20GeoPackage%20-%20updated.pptx). See also https://github.com/INSPIRE-MIF/gp-geopackage-encodings/issues/5 |
| FI | topographic themes | Finnish topographic database is a geopackage, which consists of 120+ feature types (database layers). The size of geopackage is 73 GB (zipped 26 GB). All geometry columns are spatially indexed. Finnish topographic database is downloadable here: https://tiedostopalvelu.maanmittauslaitos.fi/tp/kartta?lang=en . See also https://github.com/INSPIRE-MIF/gp-geopackage-encodings/issues/7|
| FI | topographic themes | NLSFI has implemented experimental prototype serving topographic database content as Geopackage using OGC API Features. An example: http://xxxxx/mtkgml/collections/rakennus/**items?f=gpkg&limit=1000**&crs=http://www.opengis.net/def/crs/EPSG/0/3067 . Output: items.gpkg (attached): > [items.zip](https://github.com/INSPIRE-MIF/gp-geopackage-encodings/files/5499679/items.zip). See also https://github.com/INSPIRE-MIF/gp-geopackage-encodings/issues/8 |
