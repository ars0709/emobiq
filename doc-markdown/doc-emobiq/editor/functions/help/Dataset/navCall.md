# navCall

	navCall > (	connector = ($string),
	ent = $string,
	function = $string,
	subFunction = $object,
	data = $object,
	callBack =success,	
	errCallback=err 
	)

## Description

Post data to dynamics navision with emobiq connector

## Parameters

**connector** = name of connector (set on global services component)
**ent** = name of page on navision services
**function** = name of function (default : create)
**subfunction** = object  (default : null)
**data** = object  (default : null)
use object type 
			<name field>=<value>,
			<name field>=<value>
**callBack** = event when success insert 
**errCallback** = event when failed post 


		
## Return Value

**string**

## Examples

![](navCall1.png?raw=true)
![](navCall2.png?raw=true)
![](navCall3.png?raw=true)
![](navCall4.png?raw=true)
![](navCall5.png?raw=true)
### Notes
> only work microsoft dynamics nav
> 