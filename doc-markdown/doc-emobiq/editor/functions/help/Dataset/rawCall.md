# rawCall

	navCall > (	connector = ($string),
	path = $string,
	method = $string,
	data = $object,
	callBack =success,	
	errCallback=err 
	)

## Description

Post data to restApi with json format

## Parameters

**connector** = name of connector (set on global services component)
**path** = name path 
**method** = get, post, put
**data** = object  (default : null)
use object type 
			<name field>=<value>,
			<name field>=<value>
**callBack** = event when success insert 
**errCallback** = event when failed post 


		
## Return Value

**object**

## Examples

![](rawCall.png?raw=true)
![](rawCall1.png?raw=true)
### Notes
> 
> 