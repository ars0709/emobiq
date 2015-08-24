# renderTemplate

	renderTemplate > 
	(template = $template,
	data > ($data),
	strip > ($trim))

## Description

Create a template with dynamic values.

## Parameters

**$template** (String)

The main template this will contain the temporary variables for the dynamic values.

> Here are the available options:
>
> **Looping** example = {{~'detail':v:idx}} ... {{~}} <br>
> **Variable** example = {{=v.'No'}}

**$data** (Object)

The temporary variables in '$template' will be assigned or set up here.

**$trim** (Boolean)

Indicates whether to trim the template. <br>
Default value is 'true'.

## Return Value

**Any**

## Examples

![](renderTemplate.png?raw=true)

### Notes
> If there is valid template then it will return a string of the template.
> If there is no valid template then it will return a boolean false.

