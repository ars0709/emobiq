# captureVideo

	captureVideo > (callback = $success, errorCallback = $error)

## Description

Activates the video recording of the mobile phone to be able to capture video.

## Parameters

**$success** (Object)

This is where the following flows / steps are described when this function succeed.

To access the captured video details just use the 'input' (Object).
![](captureVideo1.png?raw=true)

**$error** (Object)

This is where the following flows / steps are described when this function failed.

## Return Value

N/A - This function captures a video then the details can be accessed in 'callback / $success', it always return 'undefined'.

## Examples

![](captureVideo2.png?raw=true)

### Notes
> None

