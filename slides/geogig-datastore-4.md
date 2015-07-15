# GeoGig datastore

Example request

```xml
<wfs:Transaction service="WFS" version="1.1.0" xmlns:wfs="http://www.opengis.net/wfs" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://www.opengis.net/wfs http://schemas.opengis.net/wfs/1.1.0/wfs.xsd">
    <wfs:Insert>
        <feature:grid xmlns:feature="http://localhost:8080/">
            <feature:the_geom>
                <gml:Polygon srsName="EPSG:4326" xmlns:gml="http://www.opengis.net/gml">
                    <gml:exterior>
                        <gml:LinearRing>
                            <gml:posList>10.44454512201291 43.79402900656421 10.455324905423845 43.79402900656421 10.455324905423845 43.78624730353676 10.44454512201291 43.78624730353676 10.44454512201291 43.79402900656421</gml:posList>
                        </gml:LinearRing>
                    </gml:exterior>
                </gml:Polygon>
            </feature:the_geom>
        </feature:grid>
    </wfs:Insert>
</wfs:Transaction>
```
