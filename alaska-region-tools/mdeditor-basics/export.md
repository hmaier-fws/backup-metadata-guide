# Export Records

The export function allows the current set of metadata records to be saved as an mdEditor or mdJSON file. The saved files can be shared with collaborators, imported into another record set, or imported into another browser. Exported mdEditor files should be saved as a backup or archival copy in the project's archive folder.

## **Using Export to Backup Records** <a href="#using-export-to-backup-records" id="using-export-to-backup-records"></a>

Exporting records is the only way to save mdEditor files outside of your browser cache.&#x20;

{% hint style="warning" %}
You should backup by exporting an mdEditor JSON file each time you finish a work session in mdEditor or switch browsers.
{% endhint %}

### mdEditor files vs. mdJSON files <a href="#mdeditor-files-vs-mdjson-files" id="mdeditor-files-vs-mdjson-files"></a>

mdJSON files can be uploaded and translated to other formats via the mdTranslator application while mdEditor files are exclusive to the mdEditor application and retain all mdEditor information, including Settings.

### **Best Practices** <a href="#best-practices" id="best-practices"></a>

* Export project and product records to the project's archive folder as an mdEditor JSON file. Include Settings.
* Export the contact and data dictionary records to the program's archive folder as mdEditor JSON files. Include Settings. These records are backed up in a different location because they are reused across many projects.&#x20;
* It is particularly important that you export your records for backup before using mdEditor's **Clear Storage Cache** functionality (clearing the storage cache will delete any records or data you have entered into the mdEditor). Exporting ensures that your data is secure even after clearing the storage cache. Not exporting your data before clearing your cache will result in a permanent loss of records. Consult the [Settings](broken-reference) section of this manual to learn more.

## Export Options <a href="#export-options" id="export-options"></a>

While exporting data, there are four options available (on the right side of the export data window).

![](<../../.gitbook/assets/export\_data\_action\_menu (1).png>)

* **Export All**: will export everything currently loaded in mdEditor into a single file. Exports an mdEditor JSON file.
* **Export Selected**: will only export the items you have selected (so individual records, contacts, etc.). If nothing is selected it will be disabled (i.e., grayed out). This also exports an mdEditor JSON file.
* **Export mdJSON**: only works for metadata records (i.e., doesn't work for contacts). Exports just the mdJSON file, which is a standalone JSON file you can load into mdTranslator and have translated into other metadata formats. mdJSON files imported into mdEditor are treated as new records and will not merge/update an existing record.
* Clicking the **Include Settings** switch will also export mdEditor settings (only for mdEditor files). Consult the [Settings](broken-reference) section of this manual to learn about settings.
