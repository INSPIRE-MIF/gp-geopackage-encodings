# Examples

The examples below are examples of GeoPackage files that are currently provided. Note: they don't comply to any official encoding rule as we do not yet have such a rule.

<table>
    <tr>
        <th>Country</th>
        <th>Theme</th>
        <th>Comment</th>
    </tr>
    <tr>
        <td>DK</td>
        <td>Addresses</td>
        <td>The Danish Agency for Data Supply has published a first draft of a GeoPackage file with all Danish addresses (11 GB). See the metadata at https://geodata-info.dk/srv/eng/catalog.search#/metadata/50b921ea-935e-d605-2287-4ee364046795, and see some background information in [the (updated) presentation from the 62nd MIG-T meeting](https://webgate.ec.europa.eu/fpfis/wikis/display/InspireMIG/62nd+MIG-T+meeting+2020-07-02?preview=/527439698/580880283/20201012%20MIG-T%20GeoPackage%20-%20updated.pptx). See also https://github.com/INSPIRE-MIF/gp-geopackage-encodings/issues/5</td>
    </tr>
    <tr>
        <td>FI</td>
        <td>topographic themes</td>
        <td>Finnish topographic database is a geopackage, which consists of 120+ feature types (database layers). The size of geopackage is 73 GB (zipped 26 GB). All geometry columns are spatially indexed. Finnish topographic database is downloadable here: https://tiedostopalvelu.maanmittauslaitos.fi/tp/kartta?lang=en . See also https://github.com/INSPIRE-MIF/gp-geopackage-encodings/issues/7</td>
    </tr>
    <tr>
        <td>FI</td>
        <td>topographic themes</td>
        <td>NLSFI has implemented experimental prototype serving topographic database content as Geopackage using OGC API Features. An example: http://xxxxx/mtkgml/collections/rakennus/**items?f=gpkg&amp;limit=1000**&amp;crs=http://www.opengis.net/def/crs/EPSG/0/3067 . Output: items.gpkg (attached): &gt; [items.zip](https://github.com/INSPIRE-MIF/gp-geopackage-encodings/files/5499679/items.zip). See also https://github.com/INSPIRE-MIF/gp-geopackage-encodings/issues/8</td>
    </tr>
    <tr>
        <td>EEA</td>
        <td>Transport networks (roads, railways, airports), Area management, Human Health</td>
        <td>The new Environmental Noise Directive (END) reporting mechanism includes alignment between the END reporting obligations and INSPIRE data specifications (INSPIRE Directive). The selected format for spatial data exchange is GeoPackage. In the scope of the END reporting, we developed encoding rules for GeoPackage format based on the previous work on INSPIRE alternative encodings and simplification. This would allow a transformation between GeoPackage and GML (INSPIRE) formats. The predesigned GeoPackage templates for the END reporting have been developed to facilitate the reporting data flows in Reportnet 3.0, data transformation and creation of GeoPackage files. More information is published at https://www.eionet.europa.eu/reportnet/docs/noise , including GeoPackage templates and data samples (mostly simulated data based on previously reported noise data) in GeoPackage format. <br/><br/> END GeoPackage encoding guidelines: https://www.eionet.europa.eu/reportnet/docs/noise/guidelines/geopackage-encoding-rule-end.pdf <br/> GeoPackage templates: https://www.eionet.europa.eu/reportnet/docs/noise/templates</td>
    </tr>
    <tr>
        <td>IT</td>
        <td>Geology</td>
        <td>In the context of the GO-PEG EU project (https://www.go-peg.eu/), the Italian Institute for Environmental Protection and Research (ISPRA) - Department for The Geological Survey of Italy, has produced the Italian Geological Map 1:100k in Geopackage encoding. The map contains geological units, faults, folds, caves, landslides. This file can be downloaded at http://www.epsilon-italia.it/public/GO-PEG/GE-map-100k-full.gpkg. The related geopackage template can be downloaded at http://www.epsilon-italia.it/public/GO-PEG/GE-gpkg-template.gpkg </td>
    </tr>
</table>
