##Featured Professors Macro for Rose-Hulman Institute of Technology

**This project was designed for Umbraco 4.x**

This macro uses a custom document type within Umbraco to determine the descendants to pull in for the feed.

This macro has three custom parameters (listed by alias and type):

* numberOfItems - number
	* How many items per page
* showPageNum - bool
	* Show page numbers (always off if p <= 1)
* featureFirst - bool
	* Full blowout of the first content node (versus only showing list of items)

We use [ImageGen](http://our.umbraco.org/projects/website-utilities/imagegen) to modify the uploads and generate the thumbnails.

Working example: [http://www.rose-hulman.edu/.../featured-professors.aspx](http://www.rose-hulman.edu/offices-services/academic-affairs/featured-professors.aspx)

###Additional Thanks
This project would not be what it is without this [pagination code](http://www.diplo.co.uk/blog/2011/6/21/creating-a-paged-list-in-umbraco-using-razor.aspx).
