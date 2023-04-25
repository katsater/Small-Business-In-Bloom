---
layout: page
title: Reuse the Collection
permalink: /reuse/
collection: qatar
---

Wax is inspired by [FAIR data principles](https://journal.code4lib.org/articles/13427), and as such strives to make its collections findable, accessible, interoperable and reusable.

The metadata record houses all of the information regarding the photos used in this project. The available information on the metadata record can be used for future projects regarding small businesses in Bloomington or added onto for further elaboration into the topic. The “pid” is the picture ID. The pid and the label are used to identify each individual photo. The date column displays the date in which the photo was taken. The “object_type” column displays the location that each photo depicts, followed by the address of the location. Finally, the description column provides a short description of each location that is pictured in each photo. With this information being accessible, the audience may choose to visit and support the featured small businesses in the Bloomington area. 

The demo site comes with a specific `_include` called `interactive_metadata_table` to help you make pages like this one complete with interactive [DataTables](https://datatables.net/) and downloadable CSVs of collection metadata.

{% include interactive_metadata_table.html collection=page.collection %}
