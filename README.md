# uvcc-webserver
A webserver to change camera settings that supports multiple cameras and different operating systems.


## Examples

* Get device list `http://localhost:3456/devices`
* Get supported controls, values, and ranges `http://localhost:3456/controls/4057`
  * This is for the elgato camera whose vendorID is 4057. It may be different for different cameras.
* Get the brightness `http://localhost:3456/get/4057/brightness`.
* Set the brightness `http://localhost:3456/set/4057/brightness/10`.
  * TODO turn this into a post request.


## Installation:
* Linux: `ypm install`
* Mac: `npm install`
* Windows: 
  * Install [https://zadig.akeo.ie/](https://zadig.akeo.ie/)
  * `npm install`

  
