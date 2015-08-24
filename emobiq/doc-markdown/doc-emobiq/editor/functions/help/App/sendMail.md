# sendMail

	canvasToImage > 
	(config > ($config),
	from > ($from),
	to > ($to),
	cc > ($copy),
	bcc > ($blind_copy),
	data > ($data),
	callback > ($success),
	errCallback > ($error))

## Description

Sends an email.

## Parameters

**$config** (Object)

The configurations needed in sending the email.

> Here are the available options:
> 
> **Host** (String) <br>
> The host/stmp that this function will use. <br>
> **Port** (String) <br>
> The port that this function will use. <br>
> **SMTPAuth** (Boolean) <br>
> Indicates whether the stmp will use authenthication or not. <br>
> **SMTPSecure** (String) <br>
> The smtp secure (tls, etc) that this function will use. <br>
> **Username** (String) <br>
> The username for the smtp. <br>
> **Password** (String) <br>
> The password for the smtp. <br>
> **html** (Boolean) <br>
> Indicates whether the email is html or not.

**$from** (Object)

The from details for sending the email.

> Here are the available options:
> 
> **email** (String) <br>
> The email address of the sender. <br>
> **name** (String) <br>
> The name that will displayed in the sender. <br>

**$to** (Object)

The main recipients of the email.

> Here are the available options (Create array for multiple):
> 
> **email** (String) <br>
> The email address of the recipient. <br>
> **name** (String) <br>
> The name that will displayed in the recipient. <br>

**$cc** (Object)

The copy recipients of the email.

> Here are the available options (Create array for multiple):
> 
> **email** (String) <br>
> The email address of the copy recipient. <br>
> **name** (String) <br>
> The name that will displayed in the copy recipient. <br>

**$bcc** (Object)

The blind copy recipients of the email.

> Here are the available options (Create array for multiple):
> 
> **email** (String) <br>
> The email address of the blind copy recipient. <br>
> **name** (String) <br>
> The name that will displayed in the blind copy recipient. <br>

**$data** (Object)

The contents for the email.

> Here are the available options:
> 
> **body** (String) <br>
> The main content or body of the email. <br>
> **subject** (String) <br>
> The subject of the email. <br>

**$success** (Object)

This is where the following flows / steps are described when this function succeed.

**$error** (Object)

This is where the following flows / steps are described when this function failed.

## Return Value

**Boolean**

## Examples

![](sendMail1.png?raw=true)

![](sendMail2.png?raw=true)

### Notes
> None

