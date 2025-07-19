(metadata)=
# Adding Metadata

The HTMDEC DMS has a flexible metadata system. Folders and files can be
annotated with simple key-value pairs or arbitrary JSON-based metadata
structures. 

* Metadata is used for annotation, discovery, and identification of related items
in the DMS.
* Metadata can be added manually or programmatically, via the REST API


To add metadata to an item manually in the DMS, select the **plus** button on the
metadata panel. Select **Simple** for simple key value pairs and **JSON** for
arbitrary JSON-based metadata.

```{figure} images/htmdec-metadata-simple.png
---
name: dms-metadata-simple
---
```

For JSON, specify the **key** name and JSON value:

```{figure} images/htmdec-metadata-json.png
---
name: dms-metadata-json
---
```

(related-identifiers)=
## Related Data

Adding metadata to items in the DMS enables the **Related Data** feature through
which related items in any collection can be easily connected.

```{figure} images/htmdec-metadata-related-data.png
---
name: dms-metadata-related-data
---
```
