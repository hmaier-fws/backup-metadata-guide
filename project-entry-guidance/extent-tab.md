# Project Extent Tab

**Extent** refers to geographic boundaries for your project. Spatial extents lets users see at a glance the geographic footprint of your project and allows searching for projects within specific geographic areas.

## Extent (Required, where applicable) <a href="#creating-extents" id="creating-extents"></a>

**Extent** refers to geographic context for your project.  This may be a simple description or place name or a simplified geospatial boundary.  Spatial extents allow users to see at a glance the geographic context of your project and if a geospatial boundary is included enables geographic search functions.  Extent are best practices where applicable.&#x20;

{% hint style="info" %}
An extent may be simply a text description or may be a simplified geographic representation.  It is a reference for search and discovery; NOT a GIS dataset.&#x20;
{% endhint %}

## Creating Extents

First, open the **Extent** tab.

![Extent Tab](<../.gitbook/assets/image (60).png>)

Click on the **Add Extent** button to open and extent editing window.  The extent description box can be used to enter a simple text description.

To add a geographic extent, click the **Add Features** button opens a geographic extent editing window.  You can import features (option 1 below) or draw features (option 2 below) to represent the spatial extent of the project.  These feature extents can be re-used for other records using the **Export Features** button.

![](<../.gitbook/assets/image (76).png>)

{% hint style="warning" %}
Extents are limited to 5000 vertices.  Extent need only to be accurate enough for searching and discovery purposes.  They are metadata, and not a dataset.  A high-definition shapefile of a geographic area is a dataset.
{% endhint %}

#### Option 1: Import Spatial Features

Spatial features such as geoJSON, shapefiles, and kml files, in latitude and longitude coordinates only, can be imported.  Clink on **Import** **Features** and select the desired file for import.  Alternatively, drag and drop the desired file into the map display.  File attributes such as name and description in these files will not be imported and are added manually in the feature properties table below the map. &#x20;

{% hint style="warning" %}
Imported file coordinates must be geographic coordinates i.e. latitude and longitude, not projected coordinates.
{% endhint %}

![Drag and Drop or click Import Features button are both options to upload extent files in mdEditor.](<../.gitbook/assets/image (31).png>)

#### Option 2: Draw Spatial Features

The geographic extent editing window map interface includes function buttons to draw a line, polygon, square, or a point.  These buttons are located along the left side of the map view.  Choose the shape button desired and click a starting point on the map to begin.  For polygons, click the **Finish** button to close the polygon.

![](<../.gitbook/assets/image (64).png>)

#### Calculate a Bounding Box

Once a geographic extent is present, simply click on the calculate button under the Bounding Box coordinates in the Edit Extent window.  This will populate the bounding box coordinates.&#x20;

![Example Geographic Extent entry and bounding box for the State of Alaska](<../.gitbook/assets/image (32).png>)

{% hint style="danger" %}
Bounding boxes will not work across the dateline, but you can have more than one extent per project. If your project area crosses the dateline, split the area into multiple extents and create separate bounding boxes.
{% endhint %}

## Saving and Exporting Extents

Extent features may be exported as JSON files with the **Export Features** button.

![Open Extent editor window; note the Import and Export Features buttons in the right margin.](<../.gitbook/assets/image (59).png>)
