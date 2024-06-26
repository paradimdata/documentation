## Metadata Upload Forms

PARADIM's data portal provides automated file format conversion and metadata extraction from instruments files to make FAIR as seamless as possible.  In some instances, however, metadata must be manually entered. This is accomplished by schema controlled forms for validated entry in a central location. The ["schema" folder in the documentation repo of PARADIM's GitHub organization](https://github.com/paradimdata/documentation/tree/main/form%20schemas) shares these `json` schema files defining those metadata uploads.

The files programmatically define each metadata field collected for a particular aspect of the project, possibly including bounds on allowed values. The data portal renders the schema defined in the files as "Forms" that users can access to add new entries of a particular type into the data system. New entries are validated against their defined schema in real time. Users should contact members of the data handling team if a particular option needed for an upload is missing, or if validation bounds or other aspects of the schema need to be updated to allow a new upload.

From the ["Forms" tab](https://portal.data.paradim.org/#forms) on the data portal website, users can click on a specific Form, which will take them to a listing of all of their existing entries for that Form (you'll need to be logged into your data portal account to see any Forms listed). New entries can be added by clicking the green "plus sign" button in the upper right corner of the page.

Completed entries are stored in the data portal, as are any files that are uploaded using the forms. Users can view and edit form entries in the data portal after they've been initially created, or access them programmatically as structured JSON objects using the RESTful API.

### "EDS and EBSD Characterization" form

The [EDS and EBSD upload form](https://portal.data.paradim.org/#form/663e6d21b18fa1c426e939ab) is used to collect and validate details about EDS and EBSD characterizations of PARADIM samples.

Some details about specific fields are (in progress):
