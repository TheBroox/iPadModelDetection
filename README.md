# iPadModelDetection
Detect what model of iPad your end user is on.

The `getiPadModel()` function creates a canvas object and from that is able to determine the device's GPU. This bit of information in conjunction with the device's screen size and pixel ratio determines the list of possible iPads your end user is on. The list is returned as a comma seperated string. An empty string is returned if the device is not an iPad.
