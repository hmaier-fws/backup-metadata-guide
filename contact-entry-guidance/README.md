# Contact Entry Guidance

**Contacts** are individuals or organizations that can be referenced in project and product metadata records and even within other contacts.  Contacts contain information such as the names of individuals or organizations, email address, physical address, website, and phone numbers so that metadata users can communicate with those affiliated with a project or data asset.  Contacts inform who is involved in projects and data products, who funded projects, and who to contact with for access or questions about a data product.



For information on determining individual data management roles: see [Establish Roles and Responsibilities](https://ak-region-dst.gitbook.io/alaska-region-interim-data-management-user-guide/four-fundamental-activities-of-data-management/establish-roles-and-responsibilities) in the [Alasak Region Interim Data Management User Guide](https://ak-region-dst.gitbook.io/alaska-region-interim-data-management-user-guide/).

## Contact Management in mdEditor

* In mdEditor, contacts are created separately from metadata records and are stored within a contact library. Once contacts have been entered or imported into mdEditor, they can be used in any metadata record.  Editing a contact in the mdEditor contact library will update the contact information included in any metadata record that uses that contact within your active files.
* Each contact in mdEditor should have only ONE contact record. Having duplicate copies of the same contact is not desirable. It can create confusion and unnecessary duplication errors.
* Contact records may be maintained between work sessions in mdEditor. This allows contacts to be readily available and re-used for new metadata records.
* When creating a backup of your active metadata records, export your contact library and settings with your metadata records.  This ensures that your work will not be lost if your browser cache is cleared accidently between work sessions.  To do this simply, go to the Export screen, select 'yes' to include settings in the export, and click **Export All**.  This will create a copy of all of your active mdEditor files with the contact information available.  If a contact record is not included in the contact library, mdEditor will display error.  Re-entering contact metadata will cause duplication errors.
* When exporting a metadata record set, i.e. when providing your metadata records for review by another,  select the desired records, contacts, and data dictionaries by checking the box in to the left of the record, and click **Export Selected**.
* When exporting a completed metadata record that will be consumed by a catalog, select the desired record and click **Export mdJSON**.  This will export the item metadata, relevant contacts, and dictionaries into a machine-readable file.&#x20;

![Export View includes 3 options on the right side:  Export all, Export Selected, and Export mdJSON](<../.gitbook/assets/image (42).png>)

## Best Practices for Contact Entry

* Make sure your contacts are loaded and accurate in mdEditor before creating or editing your metadata records.&#x20;
* Add any new contacts before you begin writing metadata records in mdEditor.
* Always spell out acronyms and organization names.

## mdEditor Regional Master Contacts File

The regional [contact master list](../alaska-region-tools/contact-master-list.md) file contains pre-filled contact information and standard naming conventions for FWS, programs, common federal agencies and partners, and regional staff. This file is imported into mdEditor and is intended to reduce staff time needed to write metadata, provide consistency for the Region's metadata contact records, and reduce the amount of post-processing needed to remove duplicate entries.

Your data managers maintain the [contact master file](../alaska-region-tools/contact-master-list.md) list.  It can be found in the 'contacts' folder in the top level directory of the [Regional Data Repository](broken-reference) titled with "AKContactsmdeditor-datetime.json"

Some programs may maintain a subset of the regional master contact file as a program master contact file.  The contact identifiers in this program master files are identical to those in the regional master file since it only include specific program relevant contacts and is smaller in size.  If your project is not cross-programmatic, the program master contact file may be easier to load and work with.

To load a master contact file into mdEditor, simply click Import tab, access the Regional Data Repository space, and drag and drop the desired file into the blue box and click import. Once contacts are imported into mdEditor, they can be used in any metadata record and left in your active contact library.

![Import screen in mdEditor](<../.gitbook/assets/image (14).png>)

{% hint style="warning" %}
If you load a Master Contacts file and see that there is no record for a person or position or organization that you need for your metadata, you may contact your program data manager to add that person to the Alaska Master Contacts file or create a new contact record and submit the record to your program data manager for review and inclusion in regional and program master contacts files.&#x20;
{% endhint %}

## Importing Contacts from ScienceBase

When you import a ScienceBase record, mdTranslator will automatically load all sbJSON contacts into Main/Citation/Responsible Parties.  This should be checked for errors and inconsistencies introduced during translation.  Delete any duplicate or extraneous contacts and correct any errors. Then add other contacts as needed, continue to edit the metadata to meet requirements, and follow best practices.

<img src="../.gitbook/assets/image (49).png" alt="" data-size="line">
