# padString

	length > 
	(string = $value,
	len = $length,
	type = $type,
	char = $pad_string)

## Description

Pad a string to a certain length with another string.

## Parameters

**$value** (String)

The string value to be padded.

**$length** (Integer)

The number of character length to be padded along with the string value.

**$type** (String)

The location of the string value in the newly padded string.

> **Options** <br>
> - center <br>
> - right <br>
> - left

**$pad_string** (String)

The string to be used for the additional characters to the string value.

## Return Value

**String**

## Examples

![](padString.png?raw=true)

### Notes
> This functions returns the '$value' string padded on the left, the right, or both sides to the specified padding length '$length'. If the optional argument '$pad_string' is not supplied, the '$value' is padded with spaces, otherwise it is padded with characters from '$pad_string' up to the limit.

