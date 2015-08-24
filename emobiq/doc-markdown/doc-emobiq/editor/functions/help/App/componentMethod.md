# componentMethod

	componentMethod > 
	(component = $component_name,
	componentId = $component_id,
	method = $method,
	arguments > ($arguments)
	)

## Description

Execute the method / function for a specific component.

## Parameters

**$component_name** (Any)

The name of the component where the method / funtion will be executed.

**$component_id** (Any)

The id of the component where the method / funtion will be executed.

**$method** (Any)

The method name to be executed.

**$arguments** (Object)

The arguments / details needed for the method specified.

## Return Value

**Any**

## Examples

![](componentMethod1.png?raw=true)

![](componentMethod2.png?raw=true)

### Notes
> If method for the component is existing it returns an object. <br>
> If method for the component is not existing then it returns a boolean value false.
>
> Available Methods: <br>
> 
> ** Local Table ** <br>
> clear -> (arguments = []) <br>
> 
> ** Data List ** <br>
> refreshListener -> (arguments = [])
> setItems -> (arguments = object)

