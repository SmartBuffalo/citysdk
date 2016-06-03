# CitySDK Socrata Module





* * *

### CitySDK Socrata Module.enable(apiKey) 

Enable function. Stores the API key for this module and sets it as enabled.  The API Key is optional for the socrata module but if supplied it will be used as an application Token.  It will also compare the CitySDK core's version number to the minimum number required as specified for this module.

**Parameters**

**apiKey**: `string`, The census API key.

**Returns**: `boolean`, True if enabled, false if not enabled.


### CitySDK Socrata Module.request(request, callback) 

Makes a request to the specified Socrata server and resource. You will need the "SODA API" export URL for the resource

**Parameters**

**request**: , Makes a request to the specified Socrata server and resource. You will need the "SODA API" export URL for the resource

**callback**: , Makes a request to the specified Socrata server and resource. You will need the "SODA API" export URL for the resource



### CitySDK Socrata Module.setApplicationToken(token) 

This function accepts a Socrata Application token, and will then append it to every future request

**Parameters**

**token**: , This function accepts a Socrata Application token, and will then append it to every future request




* * *









