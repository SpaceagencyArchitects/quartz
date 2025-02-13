---
title: "A00 Classification and Properties"
---
- [What are Classification Systems and Properties?](https://help.graphisoft.com/AC/26/INT/index.htm?rhcsh=1&rhnewwnd=0&rhmapid=#t=_AC26_Help%2F045_PropertiesClassifications%2F045_PropertiesClassifications-1.htm%23XREF_15029_Element_Properties&rhsearch=classification&rhsyns=%20)
- [Assigning Classifications](https://help.graphisoft.com/AC/26/INT/index.htm?rhcsh=1&rhnewwnd=0&rhmapid=#t=_AC26_Help%2F045_PropertiesClassifications%2F045_PropertiesClassifications-2.htm%23XREF_55793_Assign_Property&rhsearch=classification&rhsyns=%20)

## ALL ELEMENTS:##

### Set Classification:###
Tick ‘ARCHICAD Classification - v 2.1’ and choose a classification from the dropdown list. 

### Manually Set Properties: ###
**Renovation Status:** set to New/Existing/Demolished
**Show on Renovation Filter:** if demolition is staged, this can be used to filter demolished elements, otherwise leave on ‘All Relevant Filters’
**Structural Function:** set to Load-Bearing Element or Non Load-Bearing Element (this is important to enable the 3D structural view)
**Position:** set to Interior or Exterior (this helps with sorting when using interactive schedules to list/schedule elements, eg. doors, windows, walls, ceilings)
**In Scope:** select which consultant’s scope the element falls under (if any). Default is ‘Architecture’. This can be used to override elements (eg. draw all landscape elements in light grey)
**Keynote Description:** set for each element or in interactive schedule

### Automatically Generated Properties ###
Some properties use 'expressions', i.e. they are generated by extracting information from the model. These codes can be used in schedules as well as labels in plan, section and elevations views.
The most common automatic properties include:

**KEYNOTE Code:** This property is available to all elements that have been classified under ‘ARCHICAD Classification - v 2.1’. The Code is the part of the name of the complex profile or composite attribute placed in square brackets.
Eg. the code of a wall using a composite called 'WT[E1] - External wall with timber cladding' is **E1**

For elements that don't use complex profiles or composites (eg. library parts), the Code is equal to the Element ID.

**Finishes Codes:**
![](Pasted%20image%2020230328143111.png)
These properties read the surface material associated with an element. The Code is the portion of the name of the surface attribute placed in square brackets.
Eg. the code of a wall or floor with a finish called '[TL-1] - Nice new wall tile' is **TL-1**.



## DOORS AND WINDOWS ##

### Set Classification: ###
Tick ‘ARCHICAD Classification - v 2.1’ and choose a Door or Window classification from the dropdown list. Note that a door can be classified as a window and vice versa. The classification will determine which schedule the element will appear in.

### Door/Window and Hardware Properties ###
Best set in an interactive schedule
![](Pasted%20image%2020230328143127.png)
