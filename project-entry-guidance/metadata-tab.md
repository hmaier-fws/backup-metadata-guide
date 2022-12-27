# Project Metadata Tab

The Metadata tab describes your project's metadata, included in these fields are metadata status and relevant dates, contributors to the metadata, and metadata repositories.

## Basic Information

### Metadata Status (Required)

Select the appropriate status of the creation of your metadata from the drop down menu. For example, if you have added all of your metadata, select _"completed."_ If you still have metadata to add, select _"onGoing."_

### Date (Required)

Add at least one date is required. The recommended date type are "creation" (when you first created your metadata) and "lastUpdate" (when you most recently updated the metadata).&#x20;

## Metadata Contacts (Required)

**Metadata Contacts** are required. Adding a metadata contact will give users a contact point should they have any questions about the metadata. __&#x20;

| Role           | Description                | Required?     |
| -------------- | -------------------------- | ------------- |
| author         | person who wrote metadata  | Required      |
| publisher      | default is USFWS-AK region | Best Practice |
| pointOfContact | Data Steward               | Required      |

#### Metadata Contact Notes:

* The author should be the individual who wrote the metadata record and could be a generic position.
* In most cases, the author will be the data steward, but could be anyone, including a person from outside FWS  For example, imported FGDC metadata may list the original author from the data source.
* Publisher by default should be 'U.S. Fish and Wildlife Service, Alaska Region'  +/- program or unit.
* The point of contact may be the project manager, principal investigator, data steward, or other project staff personnel.

![Example metadata contact entry](<../.gitbook/assets/image (81).png>)

## Metadata Identifier (Required, Auto-generated)

The **Metadata Identifier** is automatically populated by mdEditor. The metadata identifier gives each of your projects and products a unique ID that differentiates them from other similar projects and products.

* If the record was imported from ScienceBase, the Metadata Identifier will be auto-populated with the ScienceBase ID (SBID).
* If the record was created in mdEditor, it will generate a universally unique identifier (UUID).

{% hint style="danger" %}
Once a Metadata Identifier is created in the metadata, do NOT change it. mdEditor uses the Metadata Identifier for record associations and changing the Metadata Identifier can break those links. If there are additional identifiers you want to include in your metadata record, include them in the Main tab under Citation as an identifier (Main/Citation/Identifier).
{% endhint %}

![Example mdEditor generated metadata identifier](<../.gitbook/assets/image (62).png>)

****
