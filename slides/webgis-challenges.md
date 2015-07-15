# Challenges for clients

There are a bunch of limitations for working properly from web mapping clients with the history of layers:

- A client API does know just the last version of a layer. Actually GeoServer WxS **won't serve** any *previous version*
- Clients **don't distinguish** *versioned* from *unversioned* data. Actually they don't know the datastore type behind each layer (unless parsing the __*getCapabilities*__)
- **Not able** to display a *layer* and to retrieve specific *information* for a *feature in the past*
