# fileUpload

	fileUpload > 
	(file = $file_path,
	callback = $success,
	errorCallback = $error)

## Description

Uploads a file in the eMobiQ server.

## Parameters

**$file_path** (Object)

The file details / file path of the file to be stored in the server.

**$success** (Object)

This is where the following flows / steps are described when this function succeed.

To access the uploaded file details just use the 'input' (Object).
![](fileUpload1.png?raw=true)

**$error** (Object)

This is where the following flows / steps are described when this function failed.

## Return Value

N/A - This function uploads a file to the server the details can be accessed inside the 'callback / $success', it always return 'undefined'.

## Examples

![](fileUpload2.png?raw=true)
![](fileUpload3.png?raw=true)

### Notes
> None

