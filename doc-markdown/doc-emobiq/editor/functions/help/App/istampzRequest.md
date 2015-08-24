# istampzRequest

	istampzRequest > 
	(istampz = $istampz_connector,
	tag = ($tag),
	pin = ($pin),
	callback = ($success),
	errorCallback = ($error))

## Description

Get the istampz data by requesting from the istampz server.

## Parameters

**$istampz_connector** (String)

The name of the istampz connector to be used, created in 'Services and Global Components'.

**$tag** (String)

The id of the istampz data to be retrieved.

**$pin** (String)

The password of the istampz data to be retrieved, password of the id '$tag'.

**$success** (Object)

This is where the following flows / steps are described when the istampz data is successfully retreived.

To access istampz data just use the 'input' (Object).
![](istampzRequest1.png?raw=true)

**$error** (Object)

This is where the following flows / steps are described when this function failed.

## Return Value

N/A - It will just retrieve the istampz data from the istampz server.

## Examples

![](istampzRequest2.png?raw=true)

### Notes
> None

