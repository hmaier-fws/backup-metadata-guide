# Product Metadata Tab

Record Metadata allows you to describe your record's metadata, including a description that outlines the process of metadata creation, contributors to the creation of the metadata, and repositories and catalogs where the metadata should be included.

## Basic Information

### Metadata Status (Required)

Select the appropriate status of the creation of your metadata from the drop-down menu. For example, if you have added all of your metadata, select "completed." If you still have metadata to add, select "onGoing."

### Dates (Required)

Add at least one date is required. The recommended date type are "creation" (when you first created your metadata) and "lastUpdate" (when you most recently updated the metadata).&#x20;

## Metadata Contacts (Required)

**Metadata Contacts** are required and selected from your list of contacts. Adding a metadata contact will provide a contact point should someone have any questions about the metadata.



| Role           | Description               | Required?     |
| -------------- | ------------------------- | ------------- |
| author         | person who wrote metadata | Required      |
| publisher      | default is USFWS          | Best Practice |
| pointOfContact | Data Steward              | Required      |

**Metadata Contact Notes:**

* The author should be the individual who wrote the metadata record, but could be a generic position.
* In most cases, the author will be the data steward, but could be anyone, including a person from outside FWS  For example, imported FGDC metadata may list the original author from the data source.
* Publisher by default should be 'U.S. Fish and Wildlife Service, Alaska Region'  +/- program or unit.
* The point of contact may be the project manager, principal investigator, data steward, or other project staff personnel.

![Example metadata contact entry](<../.gitbook/assets/image (13).png>)

## Metadata Identifier (Required, Auto-generated)



The **Metadata Identifier** is automatically populated by mdEditor. The metadata identifier gives each of your projects and products a unique ID and differentiates them from other similar projects and products.  Note this is difference from a Digital Object Identifier which is linked directly to a project or dataset.

* If the record was created in mdEditor, it will generate a universally unique identifier (UUID).
* If the record was imported from ScienceBase, the Metadata Identifier will be auto-populated with the ScienceBase ID (SBID).

{% hint style="danger" %}
Once a Metadata Identifier is created in the metadata, do not change it. mdEditor uses the Metadata Identifier to connect records and changing the Metadata Identifier can break those connections. If there are additional identifiers you want to include in your metadata record, include them in [Main/Citation/Identifier](broken-reference).
{% endhint %}

![Example UUID metadata identifier entry](<../.gitbook/assets/image (30).png>)

![Example identifier entry](<../.gitbook/assets/image (37).png>)

## Parent Metadata

Parent Metadata is used for data products that are created in a series.  The parent metadata describes the dataset as a whole, while the product metadata describes the instance.  For example, the same survey may be completed annually.  The parent metadata may describe the data collected and the instance metadata may contain the start and end dates, environmental conditions, surveyors, or anything else specific to the data for that particular year.&#x20;

## Metadata Repositories

Currently, the Alaska region is not using the metadata repository fields.  The Alaska Regional Data Repository is not currently an option in mdEditor.
