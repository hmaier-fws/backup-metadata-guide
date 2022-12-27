# Settings

The settings menu allows for the configuring of user-specific options. Settings should be configured before you create metadata.

## General Settings

**mdEditor Version**: The mdEditor version notes the current version of mdEditor. Use this when reporting errors. Errors can be reported at [https://github.com/adiwg/mdEditor/issues](https://github.com/adiwg/mdEditor/issues). You must have a github account in order to post.

**Auto-Save**: The Auto-Save option will write all changes to local storage when you exit a data entry field. Changes must be manually saved if the Auto-Save feature is turned off.

{% hint style="info" %}
Auto-Save allows you to save less frequently, but it makes it harder to undo changes that you make to your records. If you stay on the same record, you can cancel changes. But once you leave the record, the record is saved and you can’t cancel the change except by manually re-editing the record.
{% endhint %}

**Copy in Edit Mode:** All&#x20;

**Delete in Edit Mode:** Allow users to delete a record while in edit

**Clear All Records**: All records can be cleared by clicking the "Clear Storage Cache."

{% hint style="danger" %}
**Warning**: Clearing all records will delete all of the records currently loaded in mdEditor. Before doing so, use the Export function to make a backup of your records. Otherwise, the records will be permanently lost (unless you previously made a backup copy).
{% endhint %}

## Defaults

**Defaults** include settings for **Language**, **Character Set**, **Country**, and the _\*Import URL_ \*(used for defining the default URL for importing).

The following defaults will be pre-loaded:

* default language: English
* default character set: UTF-8
* default location: USA

Also included in **Defaults** are the **Metadata Repositories** (online databases for storing metadata). Once entered in **Settings** these can then be selected for projects and products so that they are flagged to a metadata repository of your choice. See SA Specific Settings for Metadata Repository information above.

## Publishing Settings

SA metadata will be published directly to ScienceBase (and from there be sent to the Science Catalog and data.gov).

In the **Default Parent Identifier**, enter your LCC's ScienceBase project folder's ScienceBase ID (SBID). **Default Community** and **Default Organization** are free text fields to describe where your Default Parent Identifier is located.

## Export Settings

See the [Export section](broken-reference) for information about the options available for Exporting.

## Profile and Validation Settings

Allows a user to import a custom metadata profile and/or a custom validation schema.
