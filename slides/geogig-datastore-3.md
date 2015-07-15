#  GeoGig datastore

Once you have published layers from a GeoGig repository then:

- Use OGC standard web services like **WMS** and **WFS** for exploiting such layers
- Start to track changes and edits to the features from WebGIS clients through **WFS-T** calls:
    - each call, properly HTTP POST, is a different GeoGig commit in the repository
    - both geometry and alfanumeric properties can be changed as normally for unversioned data
