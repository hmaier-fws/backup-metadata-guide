# Dictionary Entities Tab

## Creating an Entity

Click the **Add Entity** button to open the entity editing window. Optionally, you can create an Entity with **Import CSV** to auto-generate attributes and domains based on a dataset. See [Generate Entity from CSV](entities-tab.md#generate-entity-from-csv) for more information.

## Entity Information

### Entity Identifier (Required, auto-generated)

Entity Identifier will be auto-generated. It can be edited, but only if absolutely necessary and ideally as soon as the Entity is created in mdEditor.&#x20;

### Entity Code Name (Required)

Assign a concise name to the Entity.

### Entity Definition (Required)

Provide a brief definition for the Entity and the type of datasets it characterizes.

### Common Name

A conversational name for the Entity.

### Title (Required)

Self-populated from the main tab.

![](<../.gitbook/assets/image (29).png>)

## Attributes (Required)

Click the **Add Attribute** button to create an attribute. Add additional attributes for each variable in the relevant dataset by clicking the **Add** button in the upper right corner of the Attributes window.

Complete the following (required) information for each attribute:

* Provide the **Attribute Name**. This is usually the variable name.&#x20;
* Select the **Data Type.** Refer to the [mADIwg mdCodes Viewer](https://adiwg.github.io/mdTools/#codes-page) for more information on each data type option.
* Add a **Definition** for the attribute. These should be informative enough for someone to interpret variables in the relevant datasets.
* Select **Allow Null** to indicate whether null values are allowed for the attribute. If the checkbox is selected, the attribute can be left empty; if the checkbox is unselected, a value for the attribute is required.&#x20;

![](<../.gitbook/assets/image (61).png>)

### **Attribute Information**

Select the **More** button next to each attribute to open the attributes editing window. If applicable, associate domains with attributes using the **Domain** drop down. The other fields are optional, but are recommended if they are informative for data users. Refer to the [mdJSON Data Dictionary](https://mdbook.adiwg.org/appendix/mdjson\_data\_dictionary.html) for more information on these fields.

![](<../.gitbook/assets/image (75).png>)

## Generate Entity from CSV

To create an Entity, click **Import CSV** and drag and drop the relevant dataset in csv format. This will auto-generate a list of attributes based on the variables in your dataset.

Prepare the Entity for import:

* Edit **Entity Code Name** and **Entity Definition** as described in **** [Entity Information](entities-tab.md#entity-information).
* Uncheck the **Import** box next to any attributes you do not want to import. All attributes will be auto-selected for import.
* If desired, change the **Name** designated for each attribute. By default, the attribute name is the same as the variable name.
* Verify the **Data Type** for each attribute. mdEditor will attempt to detect the data types; change the selection with the drop down as needed. Refer to the [mADIwg mdCodes Viewer](https://adiwg.github.io/mdTools/#codes-page) for more information on each data type option.
* Select the **Domain** box to indicate an attribute has a defined domain. This will auto-generate domains and under the [Domains Tab](broken-reference).&#x20;

{% hint style="info" %}
In general, attributes with coded terms will have a defined domain (e.g. the domain for gender might be "F","M"). Attributes with unlimited possible values will not have a defined domain (e.g. Year).
{% endhint %}

* Verify the **Allow Null** selection for each attribute. mdEditor will attempt to detect whether null values are allowed for an attribute. If the checkbox is selected, the attribute can be left empty; if the checkbox is unselected, a value for the attribute is required.&#x20;
* Select the **Max/Min** checkbox if the adjacent values represent valid maximum and minimum constraints for the attribute. mdEditor will auto-detect these values for relevant attributes, though the checkbox will be unselected by default.&#x20;

When you have finished, click the **Do Import** button to commit the new Entity, Attributes, and any Domains to the Dictionary Record.

![](<../.gitbook/assets/image (80).png>)

