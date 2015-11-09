# httpdStart

	httpdStart -> (
	www_root = $string
	port = integer
	localhost_only = true /false
	callback = success
	)

## Description

create localhost on device that can be access through browse
## Parameters

www_root = folder on device storage 
port = port to access
localhost_only = true => only can access by device self
callback when success 



## Return Value

**boolean** => check on browser 

## Examples

![](httpdStart1.png?raw=true)

### Notes
> Work on android devices