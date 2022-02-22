# Hazus Building Inventory Google Collab
A jupyter notebook with the implementation of the Hazus Building Inventory Technical Manual

Implemented by Rodrigo Costa (rccosta@stanford.edu), February, 2022. This notebook implements the algorithms in the Hazus Building Inventory Technical Manual and can be used to generate synthetic building inventories for communities. It requires two files:

A text file containing the location of each building (Example_Inventory.txt)
A shapefile containing the borders of the Census Tracts in the community (Alameda_census_blockgroups_mini.geojson)
A file containing minimum information about the demographics in each Census Tract (Alameda_Block_Group_IR.txt)
Note: the outputs from this file must not be used to draw conclusions about any building in Alameda (CA) the community used as example in this notebook.
