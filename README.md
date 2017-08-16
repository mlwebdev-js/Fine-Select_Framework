# Fine-Select_Framework

This is framework is small but ever increasing. Features allow for selectiong elements, 
creating elements, appending elements to other elements and setting multiple attributes to any element.

### Set multiple attributes to an HTML element 

##### Set attribute to element by tagname
setAttributes(getTag("p"), 
    { "id" : "newAttr", "class" : "newClass" }
);

##### Set attribute to element by id 
setAttributes(getId("app_main"), 
    { "class" : "newClass" }
);
