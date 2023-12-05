# HOLC_Area_Description_Data

The area descriptions are available in two formats.

`holc_ad_data.csv` contains the area descriptions in a flat format with each individual field value in its own row. Each row has `cat_id`, `subcat_id`, and `order` id values to map the datum to the form field through the files in the `Form_Schema` directory.

`ad_data.json` contains the area descriptons as a list of json objects. Each object is an single area description. The object field names have been regularized (e.g. `description_of_terrain` and `foreign_born_nationality`) to allow comparison across different area description forms.

In both files, the `area_id` field allows the area description data to be linked with spatial data available on the Mapping Inequality site.
