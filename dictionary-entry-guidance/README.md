---
description: Details on how to create a dictionary entry in mdEditor
---

# Product Dictionary Entry Guidance

Data dictionaries define the characteristics of attributes (also called variables or column names) that make up an entity (also called a table). A single data dictionary can describe the attributes of a single table or a collection of tables, like a database.&#x20;

Like Contacts, data dictionaries are created separately from Product records in mdEditor. The **Dictionaries** tab links the product metadata record to a data dictionary that has been previously created.   &#x20;

{% hint style="info" %}
A data dictionary is required for a tabular dataset (a single table or a database) and for geospatial shapefile attributes.
{% endhint %}

### Options for creating a data dictionary in mdEditor:

#### 1: Import an existing data dictionary

If you are updating an existing metadata record, you should import the mdEditor mdJSON file from the project's folder in the Regional Data Repository. Learn how to import files into mdEditor on the [Import ](../alaska-region-tools/mdeditor-basics/import.md)page.&#x20;

{% hint style="info" %}
The **** [**mdJSONdictio R package**](https://hdvincelette.github.io/mdJSONdictio/) **** is available to help build and translate an exel data dictionary into a mdEditor Dictionary record. This tool utilizes a [tabular data dictionary template](https://hdvincelette.github.io/mdJSONdictio/articles/02\_Dictionary\_Template.html) which can serve as a human-readable reference while creating Dictionary records. The mdJSONdictio function`build.mdJSON()`will translate these tabular data dictionaries to mdJSON format which can be imported to mdEditor. The newly imported Dictionary record will be defined with data table attributes. To learn more, see [Introduction to mdJSONdictio](https://hdvincelette.github.io/mdJSONdictio/articles/01\_Intro\_mdJSONdictio.html) and the associated articles.
{% endhint %}

#### 2: Manually create a new data dictionary

1. Click the plus (**+**) sign by **Dictionaries** in the left-hand menu to open a new dictionary entry window.
2. Give the dictionary a **Title**.  Meaningful titles help link a data dictionary to its product(s). Choose "tabularDataset" as the **Dictionary Subject.** Click Save.
3. Fill out the metadata information for the following tabs.
   * [Dictionary Main Tab](main-tab.md)
   * [Dictionary Citation Tab](broken-reference)
   * [Dictionary Domains Tab](domain-tab.md)
   * [Dictionary Entities Tab](entities-tab.md)
4. Associate the dictionary with applicable product(s) in the Product Dictionaries Tab
5. Save your work.

![Click the plus sign to create a new record ](<../.gitbook/assets/CreateNewDictionary (1).png>)

##
