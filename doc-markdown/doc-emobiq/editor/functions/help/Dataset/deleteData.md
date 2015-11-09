# deleteData

	deleteData > (	dataset = ($string),
	_id = $integer,
	callBack =success,
	errCallback=err 
	)

## Description

delete Data to emobiq staging database 

## Parameters

**dataset** = name of dataset (set on global services component)
**_id** = default id from staging data , default field is _id

**callBack** = event when success insert 


		
## Return Value

**boolean**

## Examples

![](deleteData.png?raw=true)
![](deleteData2.png?raw=true)

### Notes
> only work on staging data