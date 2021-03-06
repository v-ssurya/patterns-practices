---
TOCTitle: IRegionManager Methods
Title: 'IRegionManager Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.IRegionManager'
ms:mtpsurl: 'iregionmanager-methods-mspp-regions.md'
---


# IRegionManager Methods

The [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) type exposes the following members.

## Methods


<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CreateRegionManager](/patterns-practices/reference/iregionmanager-createregionmanager-method-mspp-regions)</td>
<td><div class="summary">
Creates a new region manager.
</div></td>
</tr>
</tbody>
</table>

## Extension Methods


<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[AddToRegion](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-mspp-regions)</td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RegisterViewWithRegion(String, Type)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RegisterViewWithRegion(String, Func(Of Object))](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Uri)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, String)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Uri, Action(Of NavigationResult))](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, String, Action(Of NavigationResult))](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Uri, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, String, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Uri, Action(Of NavigationResult), NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, String, Action(Of NavigationResult), NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
</tbody>
</table>

## See Also

[IRegionManager Interface](/patterns-practices/reference/iregionmanager-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  