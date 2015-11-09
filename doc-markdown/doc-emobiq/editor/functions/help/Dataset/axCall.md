# axCall

	axCall > (	connector = ($string),
	ent = $string,
	data = $object,
	callBack =success,	
	errCallback=err 
	)

## Description

Post data to dynamics ax with emobiq connector

## Parameters

**connector** = name of connector (set on global services component)
**ent** = name of page on navision services
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
### Notes
> only work microsoft dynamics ax
> 