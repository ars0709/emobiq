# captureAudio

	captureAudio > (callback = $success, errorCallback = $error)

## Description

Activates the voice recording of the mobile phone to be able to capture audio.

## Parameters

**$success** (Object)

This is where the following flows / steps are described when this function succeed.

To access the captured audio details just use the 'input' (Object).
![](captureAudio1.png?raw=true)

**$error** (Object)

This is where the following flows / steps are described when this function failed.

## Return Value

N/A - This function captures an audio then the details can be accessed in 'callback / $success', it always return 'undefined'.

## Examples

![](captureAudio2.png?raw=true)

### Notes
> None

