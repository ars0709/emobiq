# updateData

	updateData > (	dataset = ($string),
	_id = $integer,
	param =$object,
	callBack =success,
	errCallback=err 
	)

## Description

update Data to emobiq staging database 

## Parameters

**dataset** = name of dataset (set on global services component)
**_id** = default id from staging data , default field is _id
**param** = use object type 
			<name field>=<value>,
			<name field>=<value>
**callBack** = event when success insert 


		
## Return Value

**boolean**

## Examples

![](insertData.png?raw=true)
![](insertData2.png?raw=true)

### Notes
> only work on staging data