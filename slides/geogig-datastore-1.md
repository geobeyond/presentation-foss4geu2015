# GeoGig datastore

Build and install the binary as **GeoServer**'s extension (*Maven* is you friend!)

```bash
git clone https://github.com/boundlessgeo/geoserver-exts
git checkout ${your_geoserver_version} #still on master for 2.7
cd geogig
mvn clean install -Pgeogig
```

Copy the package into the library folder of GeoServer's installation

```bash
cp gs-geogig-2.7-SNAPSHOT.jar ${GEOSERVER_WAR_HOME}/WEB-INF/lib
service tomcat restart
```
