# getLocation

	getLocation > 
	(timeout = $timeout,
	enableHighAccuracy = $accuracy,
	callback = $success,
	errorCallback = $error)

## Description

Get the current location details of the device using GPS.

## Parameters

**$timeout** (Integer)

The millisecond time before this functions timeout.

**$accuracy** (Boolean)

Indicates wether to activate high accuracy location search or not.

**$success** (Object)

This is where the following flows / steps are described when this function succeed.

To access the location details just use the 'input' (Object).
![](getLocation1.png?raw=true)

**$error** (Object)

This is where the following flows / steps are described when this function failed.

## Return Value

N/A - This function retrieves the location details that can be accessed in 'callback / $success', it always return 'undefined'.

## Examples

![](getLocation2.png?raw=true)

### Notes
> None

