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
        <td>The Danish Agency for Data Supply and Infrastructure has published all Danish addresses in a GeoPackage file. See the metadata at https://geodata-info.dk/srv/eng/catalog.search#/metadata/50b921ea-935e-d605-2287-4ee364046795, and the <a href="https://inspire.ec.europa.eu/sites/default/files/20221027_addresses_dk_gpkg.pdf">presentation</a> at the <a href="https://inspire.ec.europa.eu/events/inspire-good-practice-geopackage-and-implementation-practice-webinar">Good Practice webinar</a>. Both the <a href="./ad_template.gpkg">GeoPackage template</a> and the <a href="./ad_ogcgeopackage2gml.fmw">FME workspace to map from GeoPackage to GML</a> are available in this repo.</td>
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
        <td>In the context of the GO-PEG EU project (https://www.go-peg.eu/), the Italian Institute for Environmental Protection and Research (ISPRA) - Department for The Geological Survey of Italy, has produced the Italian Geological Map 1:100k in Geopackage encoding. The map contains geological units, faults, folds, caves, landslides. This file can be downloaded at https://www.epsilon-italia.it/public/GO-PEG/GE-map-100k-full.gpkg. The related geopackage template can be downloaded at https://www.epsilon-italia.it/public/GO-PEG/GE-gpkg-template.gpkg </td>
    </tr>
        <tr>
        <td>IT</td>
        <td>Geology</td>
        <td>The delivery of subsurface geological data deriving from geological 3D models suffers the lack of a dedicated data model and easy-to-use delivery format. In the Go-PEG project “Go-Depth use-case”, ISPRA - Geological Survey of Italy has developed an efficient approach to manage and deliver interoperable subsurface geological data using an INSPIRE-extended data model and geopackage INSPIRE alternative encoding. This approach fulfills the institutional mandates of the Geological Survey of Italy and will be the starting point for the ongoing design and implementation of the “Geological 3D subsurface models database” related to the National Geological Mapping Programme. Moreover, the model could be tested in EU initiatives (e.g. EPOS, Geological Mapping and Modeling Expert Group of EuroGeoSurveys) and furtherly implemented and extended in projects funded by NextGeneration EU national plan. The produced dataset related to Po Plain subsurface can be downloaded at https://www.epsilon-italia.it/public/GO-PEG/Po_Basin_subsurface.gpkg. The related geopackage template can be downloaded at https://www.epsilon-italia.it/public/GO-PEG/go-depth-ge-template.gpkg
 </td>
    </tr>
     <tr>
        <td>EJPSOIL</td>
        <td>Soil</td>
        <td>In the context of the H2020 European Joint Research Programme <a href="https://ejpsoil.eu">EJPSOIL</a> and in particular in the creation of a 'Software framework for a common agricultural soil information system', a GeoPackage model has been developed by <a href="https://www.crea.gov.it/en/home">CREA</a> (Council for Agricultural Research and Economics of Italy) which is proposed as a specific implementation for the Soil data theme of the GP on GeoPackage encoding of INSPIRE datasets. 
        As required by the GP specification, the following evidence has been provided:
1)a description of the <a href="https://github.com/ejpsoil/inspire_soil_gpkg_template/blob/main/docs/EJP SOIL Encoding rules of the D6.4  Software framework for a shared agricultural soil information system.pdf">UML-to-Geopackage model transformation rules</a> 
2)an <a href="https://github.com/ejpsoil/inspire_soil_gpkg_template/blob/main/geopackage/INSPIRE_SO_V01.gpkg">empty geopackage template </a>acting as database schema (also provided via SQL scripts)
3)an <a href="https://github.com/ejpsoil/inspire_soil_gpkg_template/tree/main/halestudio">executable model</a> for data transformation of GeoPackage datasets into INSPIRE GML datasets. Specifically, this executable model is provided in the form of a hale studio project.
4)a <a href="https://github.com/ejpsoil/inspire_soil_gpkg_template/blob/main/docs/EJPSOIL-sample-soil-data-set.gml">sample GML dataset</a> obtained through the above-mentioned data transformation project, containing both soil spatial objects and related observations and <a href="https://github.com/ejpsoil/inspire_soil_gpkg_template/blob/main/docs/Test run on 18_37 - 24.01.2024 with test suite Annex III - Soil (SO).html">successfully validated</a> against INSPIRE Soil requirements using the INSPIRE Validator.
It is worth highlighting that, even if not strictly required by the Good Practice, this model also makes use of triggers to enforce constraints of the INSPIRE UML data model and maintain data integrity.

 </td>
    </tr> 
</table>
