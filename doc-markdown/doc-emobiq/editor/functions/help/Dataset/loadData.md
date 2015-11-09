# loadData

	loadData > (	dataset = ($string),
	limit = $integer,
	page = $integer
	Filter = $array-object,
	orFilter = $array-object
	order= $array-object	callBack, success retrieve data
		)

## Description

Load data from local storage, staging database 3rd party connector

## Parameters

**dataset** = name of dataset (set on global services component)

**limit** = limit row data per request (default 25/depend 
setting on global services)

**page** = page want to retrieve

**filter** =filter data want to retrive 
use function toArray -> toObject with format 
f : name of field
v : value 
o : operator (=,<>,like,iLike) with and
		
**orFilter** =filter data want to retrive 
use function toArray -> toObject with format 
f : name of field
v : value 
o : operator (=,<>,like,iLike) with or 

**order** =order data want to retrive 
use function toArray -> toObject with format 
f : name of field
v : desc / asc

callback = event want to use if retrive data success
errCallback = event when error

		
		
## Return Value

**array object**

## Examples

![](loadData.png?raw=true)
![](loadData2.png?raw=true)


### Notes
> None.