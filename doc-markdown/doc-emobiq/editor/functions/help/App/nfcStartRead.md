# nfcStartRead

	nfcStartRead > 
	(nfc = $nfc_connector,
	receiveHandler = ($handler),
	sCallback = ($success),
	eCallback = ($error))

## Description

Activate the nfc plugin for the application.

## Parameters

**$nfc_connector** (String)

The name of the nfc connector to be used, created in 'Services and Global Components'.

**$handler** (Object)

This is where the following flows / steps are described when this function detected a nfc card.

To access the nfc card id value just use the 'input' (String).
![](nfcStartRead1.png?raw=true)

**$success** (Object)

This is where the following flows / steps are described when this function succeed.

**$error** (Object)

This is where the following flows / steps are described when this function failed.

## Return Value

N/A - It will just activate the nfc plugin in the application.

## Examples

![](nfcStartRead2.png?raw=true)

### Notes
> The mobile phone must have a nfc functionality / capability for this to work.

