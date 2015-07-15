# GeoGigTools

- OpenLayers 2.13 plugin that calls GeoGig webapi
- Functions with callback using **OpenLayers.Request.GET**

```js
function(input1, input2, callback) {
    OpenLayers.Request.GET({
        url: <GeoGig api call>,
        success: function(results) {
        //do something with results & response
            callback(null, JSON.stringify({
                        success: 'true',
                        output: response
            }));
        }
        failure: function() {
            //throw errors
            call(true, null);
        }
    })
}
```




