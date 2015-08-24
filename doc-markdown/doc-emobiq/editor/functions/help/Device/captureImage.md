# captureImage

	captureImage > (callback = $success, errorCallback = $error)

## Description

Activates the camera of the mobile phone to be able to capture image.

## Parameters

**$success** (Object)

This is where the following flows / steps are described when this function succeed.

To access the captured image details just use the 'input' (Object).
![](captureImage1.png?raw=true)

**$error** (Object)

This is where the following flows / steps are described when this function failed.

## Return Value

N/A - This function captures an image then details that can be accessed in 'callback / $success', it always return 'undefined'.

## Examples

![](captureImage2.png?raw=true)

### Notes
> None

