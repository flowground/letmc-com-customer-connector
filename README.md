# ![LOGO](logo.png) LetMC Api V2, Customer Login **flow**ground Connector

## Description

A generated **flow**ground connector for the LetMC Api V2, Customer Login API (version v2-customer).

Generated from: https://api.apis.guru/v2/specs/letmc.com/customer/v2-customer/swagger.json<br/>
Generated at: 2019-06-06T16:12:24+03:00

## API Description



## Authorization

Supported authorization schemes:
- API Key- Basic Authentication

## Actions

### Get the accounting details for the landlord.

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call

### Download a Document

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call
* `ID` - _required_ - The Document ID

### Generate a Inventory PDF for a tenancy

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call
* `tenancyID` - _required_ - The Tenancy ID

### Get an invoice pdf belonging to the landlord.

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call
* `invoiceID` - _required_ - The invoice ID to load.

### Get Active maintenance jobs.

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call

### Generate a Profit and Loss Report

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call

### Rent Arrears

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call

### Generate a Self Assessment Tax Report

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call
* `yearEnd` - _required_ - The Tax Year End.

### Get contact details of all linked landlords.

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call

### Get the summary details for the landlord.

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call

### Get tenancy details.

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call
* `tenancyID` - _required_ - The Tenancy ID

### Generate a Tenancy Agreement Copy (PDF)

*Tags:* `LandlordController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call
* `tenancyID` - _required_ - The Tenancy ID

### Downloads the photo of a property given the photo ID.

*Tags:* `PhotoController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call
* `photoID` - _required_ - The unique ID of the photo on the property
* `width` - _optional_ - An optional parameter specifying the image width
* `height` - _optional_ - An optional parameter specifying the image height

### A collection showing all the photos linked to a specific block, property or room

*Tags:* `PropertyController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call
* `propertyID` - _required_ - The unique ID of the Property
* `offset` - _required_ - The index of the first item to return
* `count` - _required_ - The maximum number of items to return (up to 1000 per request)

### Logout a customer previously logged in via the Login endpoint.

*Tags:* `SessionController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call

### Gets information about the currently logged on customer.

*Tags:* `SessionController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call

### Login as a customer given their username and password.

*Tags:* `SessionController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `username` - _required_ - The user's username.
* `password` - _required_ - The user's password.

### Send a request to the in-tray to create a landlord login.

*Tags:* `SessionController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `email` - _required_ - The email address of the landlord
* `title` - _required_ - The title of the landlord
* `forename` - _required_ - The forename of the landlord
* `surname` - _required_ - The surname of the landlord
* `propertyAdresss` - _required_ - Address of the property linked to the landlord
* `contactDetails` - _required_ - Contact details of the landlord
* `branchID` - _optional_ - (Optional) The branch ID linked to the login. This will determine which in tray the request display in

### Change the password of a customer given their existing and new password.

*Tags:* `SessionController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `token` - _required_ - The login token returned from the /session POST call
* `oldPassword` - _required_ - The customer's existing password.
* `newPassword` - _required_ - The customer's new password.

### Reset the customer's password. An email will be sent out to reset.

*Tags:* `SessionController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `email` - _required_ - The login Email Address.

## License

**flow**ground :- Telekom iPaaS / letmc-com-customer-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
