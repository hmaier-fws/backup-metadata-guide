# Glossary

_When consistent with usage in this document, definitions have been pulled from various other resources including Wikipedia,_ [_Open Data Handbook glossary_](http://opendatahandbook.org/glossary/en/)_,_ [_Duke Law EDRM glossary_](https://www.edrm.net/collections/edrmglossary/)_, and the_ [_Open Government Data Act_](https://www.congress.gov/bill/115th-congress/house-bill/4174/text#toc-H8E449FBAEFA34E45A6F1F20EFB13ED95) _codification of act definitions_ [_44 usc 3502_](https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title44-section3502\&num=0\&edition=prelim)_. It is possible to find alternative and contradictory definitions in other data management resources resources. The definitions provided here are those implied by the term’s usage in this document._

**Accessibility**: the degree to which the resource is obtainable by an interested party. Direct access without constraint would be the most accessible (e.g. resources that may be downloaded without requiring a login), whereas resources that require third-party intervention would be less accessible.

**ADIwg**: Alaska Data Integration working group

**Archive Folder**: a consistent file structure with use constraints and backup schedule that houses the definitive record of a project’s data resources. Products in the archive folder are the subject of metadata records and are the versions intended for use and dissemination. Contrast with working folder.

**Data Catalog**: database comprised of metadata allowing for the discovery of data resources.

**Data Custodian**: individual responsible for the storage and security of a data resource.

**Data Trustee**: individual having the authority to: 1) ensure resources are available to implement the complete project and data lifecycle and 2) ensure compliance with all data governance policies.

**Data Dictionary**: provides information on the contents of a dataset to support data quality and use. Such information includes entity (i.e., variable) definitions and allowable values. In the case of databases, or a collection of datasets, relationships between tables are also defined in the data dictionary.

**Data Integrity**: property describing foundational soundness of a data resource. Data with strong integrity have undergone quality control and assurance procedures throughout their lifespan, have permanence over a reasonable timeframe and changes to the data are appropriately documented.

**Data Management**: an administrative process that includes acquiring, validating, storing, and securing data to ensure the accessibility, integrity, and timeliness of the data for its users.

**Data Management Plan**: document that describes the data expected from the project, how such data will be handled throughout the project to protect data integrity, and stored at the conclusion of the project to ensure security, discoverability, and accessibility.

**Data Resources**: data. Recorded information, regardless of form or the media on which the data is recorded. aka Products.

**Data Steward**: individual responsible for reviewing the quality and metadata of a resource.

**Discoverability**: the degree to which information about a data resource’s existence is readily obtained via searching an information system (e.g., Data.gov). Certain aspects of the metadata for the resource may be useful in enhancing discoverability, such as keywords or spatial bounds. Data catalogs can enhance discoverability by providing a standard location for searching and organizing resources. A data resource may be discoverable (e.g. found in a search result) but not accessible (see accessibility).

**FGDC**: Federal Geographic Data Committee [https://www.fgdc.gov/](https://www.fgdc.gov/)

**FGDC CSDGM**:  Federal Geographic Data Committee’s Content Standard for Digital Geospatial Metadata - FGDC-STD-001-1998 Includes Biological Data Profile\
[https://www.fgdc.gov/metadata/csdgm/](https://www.fgdc.gov/metadata/csdgm/)

**ISO**: the International Organization for Standardization. Entity that provides standards to ensure consistency in definitions, formats, and use.

**ISO 19110**: International Standards Organization Geographic Information - Feature Catalogue 19110:2005

ISO 19110 defines the methodology for cataloguing feature types. It may be used as a basis for defining the universe of discourse being modelled in a particular application, or to standardize general aspects of real world features being modelled in more than one application. (International Organization for Standardization (2016). **ISO 19110:2016**. Retrieved from: [https://www.iso.org/standard/57303.html](https://www.iso.org/standard/57303.html))

**ISO 19115-1**: defines the schema required for describing geographic information and services by means of metadata. It provides information about the identification, the extent, the quality, the spatial and temporal aspects, the content, the spatial reference, the portrayal, distribution, and other properties of digital geographic data and services. (International Organization for Standardization (2014). **ISO 19115-1:2014**. Retrieved from: [https://www.iso.org/standard/53798.html](https://www.iso.org/standard/53798.html))

**ISO 19115-2**: International Standards Organization Geographic Information - Metadata 19115-2:2009

Extends the existing geographic metadata standard by defining the schema required for describing imagery and gridded data. It provides information about the properties of the measuring equipment used to acquire the data, the geometry of the measuring process employed by the equipment, and the production process used to digitize the raw data. This extension deals with metadata needed to describe the derivation of geographic information from raw data, including the properties of the measuring system, and the numerical methods and computational procedures used in the derivation. The metadata required to address coverage data in general is addressed sufficiently in the general part of ISO 19115. (International Organization for Standardization (2009). ISO 19115-2:2009. Retrieved from: [https://www.iso.org/standard/39229.html](https://www.iso.org/standard/39229.html))

**JSON**: Javascript Object Notation, a general purpose format like CSV.

**Keywords**: words used in an information retrieval system to indicate the content of a document.

**localStorage Cache**: allows an application to store data locally, in a user's browser. Storing information on the browser's local storage cache (instead of a normal file cache) means that if you use a different browser to access the mdEditor, it will not show the data you've imported from your first browser. It also means that if you clear your browser's cache, it will generally not clear your mdEditor records. However, depending upon your browser settings (E.g., in Chrome, if the "c_ookies and other site data_" option is checked), clearing your browser cache may still clear your mdEditor data.

**mdEditor**: a web application used to write archival-quality metadata for projects and data resources. [mdeditor.org](https://www.mdeditor.org/)​

**mdEditor File**: contains all of the information contained in mdJSON, along with mdEditor settings. This can be exported and shared with collaborators, imported into another record set, or saved to a local workstation as a backup or archival copy.

**mdJSON**: ADIwg standard for encoding project and data metadata, based on JavaScript Object Notation (JSON).

**mdJSON File**: proprietary to the Metadata toolkit developed by the Alaska Data Integration Working Group (ADIWG), learn more at \[[https://adiwg.github.io/mdTools/](https://www.gitbook.com/book/adiwg/mdeditor/edit)].

**mdTranslator**: open-source Ruby software application for translating between metadata standards. Metadata is input in one of the supported ‘reader’ formats and output in one of the supported ‘writer’ formats. Available as Ruby gem or Command-Line-Interface.

**Metadata**: data that describes and provides additional information about other data to promote discoverability and proper use.

**Open Format**: data format that is platform independent, machine readable, and made available to the public without restrictions that would impede the re-use of that information.

**Project**: a discrete effort on a particular topic with defined objectives or goals.

**Project Management**: the practice of initiating, planning, executing, controlling, and closing the work of a team to achieve specific goals and meet specific success criteria at the specified time.

**Quality Assurance**: preventing errors. The maintenance of a desired level of quality in a product, by means of attention to every stage of the process of acquisition, manipulation, and use

**Quality Control**: identifying and correcting errors. Process of review to reduce or eliminate errors made during data acquisition and manipulation.

**Reproducible** (analyses, workflow, or research): structuring activities so that a product (e.g., a data set, analysis result, or report) can be repeated and the same results achieved. Replication could be achieved by either the same person or team that created the original product or a different team. Documentation and scripted work flows play a key role in reproducibility.

**sbJSON**: U.S. Geological Survey’s standard for documenting records ingested into ScienceBase Catalog. The format used to define the attributes of ScienceBase items.

**ScienceBase**: a USGS collaborative scientific data and information management platform used directly by science teams. ScienceBase provides access to aggregated information derived from many data and information domains, including feeds from existing data systems, metadata catalogs, and scientists contributing new and original content. ScienceBase architecture is designed to help science teams and data practitioners centralize their data and information resources to create a foundation needed for their work. ScienceBase, both original software and engineered components, is released as an open source project to promote involvement from the larger scientific programming community both inside and outside the USGS. (USGS (2018). _About ScienceBase._ Retrived from: [https://www.sciencebase.gov/about/content/about-sciencebase](https://www.sciencebase.gov/about/content/about-sciencebase)).

**Tidy Data**: standard way of relating the structure of a dataset to its meaning. Specifically, each row represents an observation and each column represents a variable recorded on an observation.

**URI**: Uniform Resource Identifier is a string of characters used to identify a resource. A URL is a type of URI.

**Working Folder**: a file structure used by an individual, or a group in collaboration, to store data resources under production during the course of a project’s implementation. Contrast with archive folder.
