# Project Main Tab

The **Main** tab allows for the creation and/or editing of primary metadata fields for a project.

## Basic Information <a href="#basic-information" id="basic-information"></a>

### Record ID <a href="#record-id" id="record-id"></a>

Record ID will be auto-generated. It can be edited, but it should only done so if absolutely necessary and ideally edited as soon as the record is created in mdEditor.&#x20;

{% hint style="info" %}
It's a good practice when coping a metadata record to confirm that mdEditor created a new Record ID for the copy.  The record Id is viewable in the 'Copy' screen, 'View' screen or in  the 'Edit' full profile screen. &#x20;
{% endhint %}

### Title (Required) <a href="#title" id="title"></a>

Enter a concise, yet informative title. Good titles, when they appear in a search, will be informative and understandable.  Consider adding location, species, season, survey type or method, and dates.  For example:  Japanese Mutant Ninja Turtle spring hatchling North Bay survey 1985-1991

The National MBM Data Management team created some [guidelines for creating good titles.](guide-to-good-titles.md)

### Status (Required) <a href="#status" id="status"></a>

The **Status** drop-down menu allows you to select the status of your project. Choose status ONLY from the four following options: _completed, ongoing, proposed, or accepted._

{% hint style="warning" %}
This refers to the condition of your project.  This is NOT the same as your metadata status.&#x20;
{% endhint %}

![](../../.gitbook/assets/ProjectMainBasicInformation.PNG)

## Default Locale (Required, Auto-generated) <a href="#default-locale" id="default-locale"></a>

**Default Locale** allows for the selection of **Language**, **Character Set**, and **Country**. English, UTF-8, and USA will be selected by default, but you may change them if necessary. See [Settings](https://app.gitbook.com/s/-MW-Wv1z7-vUYrz5cHwE/settings) for instruction.

![Example of default locale](<../../.gitbook/assets/image (33).png>)

## Resource Type (Required) <a href="#resource-types" id="resource-types"></a>

The Resource Type should be automatically filled in with the resource type you selected when you created your record.  For project metadata, the resource type is "project". Name is optional - you can leave this blank or enter your shorten project name.

{% hint style="info" %}
If the project has a Regional Data Repository folder, a best practice is to use the same shortened project name as that used for the Regional Data Repository.
{% endhint %}

![Example of resource type](../../.gitbook/assets/resource\_types.png)

## Point of Contacts (Required) <a href="#point-of-contacts" id="point-of-contacts"></a>

Adding a point of contact gives users information on who to contact should they have a question regarding your project. To add contacts to a metadata record, you must first create/upload the contacts into mdEditor. See the [Contact](https://github.com/tpatterson1996/lcc-metadata-manual/tree/287090b07635d0e76a714278ce1f6c4aac3594cc/product-entry-guidance/contact-entry-guidance.md) Section for more information.

{% hint style="info" %}
A Master contacts list is maintained in the top level 'contacts' folder of the RDR.  This is maintained by the Alaska program managers and contains staff contacts and common organizational contacts. Before starting and editing metadata records in mdEditor, import the mdJSON contacts file.

If you need to add a contact to this master list, please contact your data manager.&#x20;

In case where the project includes external investigators, use 'coPrincipalInvestigator' for these contacts.
{% endhint %}



| Role                  | Description                                                       | Required?     |
| --------------------- | ----------------------------------------------------------------- | ------------- |
| pointOfContact        | Data Steward                                                      | Required      |
| principalInvestigator | The Project PI or Project Manager                                 | Best Practice |
| custodian             | Data Custodian (often a data manager)                             | Required      |
| owner                 | Data Trustee                                                      | Required      |
| administrator         | FWS Region +/- FWS Program or unit                                | Best Practice |
| contributor           | partnership organizations and/or other Service program or regions | Best Practice |

{% hint style="warning" %}
In cases where project include external investigators, use 'coPrincipalInvestigator' for these contacts.  \
In cases where the lead PI is the not also the Project Manager, use PI for the 'principalInvestigator' and 'pointOfContact' for the Project Manager.
{% endhint %}

![Example Point of Contact entries for a project](<../../.gitbook/assets/image (70).png>)

**NOTE:**  **Migratory Bird Management** should also include the subprogram as an administrator contact.  These options include: Migratory Birds and State Programs, Eagle Raptor Management Program, Shorebird Program, Waterfowl Program, Seabirds Program, and Land Bird Program.

## Citation <a href="#citation" id="citation"></a>

The **Citation** describes pertinent information about your project such as: responsible parties, identifiers, and any online resources that may be used to reference your project.  The citation much like a peer-reviewed publication citation, provides credit and serves as a reference citation.  Adding information in the citation will also improve users' ability to find your project metadata.

### Citation Required Fields <a href="#citation-required-fields" id="citation-required-fields"></a>

#### Title (Required) <a href="#title-1" id="title-1"></a>

The title of your record is stored in the citation tab.

#### Alternate Title <a href="#alternate-title" id="alternate-title"></a>

You can add an alternate title if desired - generally these should be shorter than the full Title.

#### Dates (Required) <a href="#dates" id="dates"></a>

At least one date is required for projects.  The date type may be the 'start', 'creation', or 'lastUpdate' date.  If a 'start' date is used, an 'end' date should be included in the final metadata record. Ongoing projects may have 'lastUpdate' dates. This exact calendar date associated with the date type may vary from the date of a proposal to the date that funding was approved, or date that the project work began.

#### Responsible Parties (Required) <a href="#responsible-parties" id="responsible-parties"></a>

At least one responsible party must be assigned in the citation section.  A best practice is to include contacts and their roles who should be recognized for their contribution to the project.  This section is very much like a citation for a peer-reviewed publication.  The identified responsible party will likely be the principal investigator of the project, but may optionally include others like the Project Manager, co-principal investigators, data producers, and contributors, or even administrative organizations like your region and program.

{% hint style="info" %}
To add contacts to a metadata record, you must first create/upload the contacts in mdEditor. See the [Contacts](https://app.gitbook.com/s/-MW-Wv1z7-vUYrz5cHwE/contacts) section for more information.&#x20;

Note that the Alaska region maintains a master contacts list for staff use that is housed in a top level 'contacts' folder in the [RDR](broken-reference). Your program may also maintain a programmatic master contact file. This is derived from a subset of the regional contact file.  Check with your program data manager.
{% endhint %}



| Role                  | Contact                                             | Required?                    |
| --------------------- | --------------------------------------------------- | ---------------------------- |
| principalInvestigator | The Project PI                                      | Best Practice                |
| administrator         | FWS Region +/- FWS Program or unit                  | Best Practice                |
| contributor           | partnership organizations and/or other FWS programs | Best Practice, if applicable |

#### Online Resource (Best Practice) <a href="#online-resource" id="online-resource"></a>

Enter the Name and URL for the project homepage website, if available. &#x20;

#### Identifier (Best Practice) <a href="#identifier" id="identifier"></a>

Projects maybe assigned a[ Digital Object Identifier](broken-reference) (DOI) and if so, this should be entered in the citation identifiers.  If you have other internal IDs for projects, enter them here as well.&#x20;

{% hint style="info" %}
**Best Practice**: Internal project tracking codes such as a PRIMR code may be entered as an identifier.  In the case where the namespace is absent from the dropdown options in mdEditor, manually enter the namespace.  This will be the case for PRIMR project codes.
{% endhint %}

![](<../../.gitbook/assets/image (16).png>)

## Description <a href="#description" id="description"></a>

**Description** section contains fields including the Abstract, **** Short Abstract, Purpose, and Supplemental Information.

### Abstract (Required) <a href="#abstract" id="abstract"></a>

Enter an abstract that succinctly describes the project's purpose and goals. Include key species or habitats types, as applicable.

### Short Abstract <a href="#short-abstract" id="short-abstract"></a>

Enter a short description, limited to 300 characters, if desired.  Best practice is a public outreach abstract for pubic affairs purposes.

### Purpose <a href="#purpose" id="purpose"></a>

Enter a short narrative about the purpose of the project such as the issue or problem that the project is designed to address and anticipated results or benefits. This aligns with SA Internal Tracking metadata.

### Supplemental Information <a href="#supplemental-information" id="supplemental-information"></a>

Enter comments, if desired.

## Time Period (Required) <a href="#time-period" id="time-period"></a>

**Time Period** refers to project start and end date. This set of dates is distinct from the fiscal year of funding. The start date indicates the overall project start.  Ongoing projects may not have end dates.  'End date' should be added when the project is completed.  This exact calendar date associated with the date type may vary from the date of a proposal to the date that funding was approved, or date that the project work began.

![Example Project Start and End Dates entry in mdEditor](<../../.gitbook/assets/main-time-period (1).PNG>)

### Maintenance

Maintenance refers to the scheduled interval for updating or reviewing the data and metadata.  Select the option from the dropdown list that is most appropriate.  If there is not a need for future updates, select 'asNeeded'.
