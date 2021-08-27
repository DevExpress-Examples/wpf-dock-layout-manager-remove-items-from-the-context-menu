<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128643796/17.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T524294)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/DXDockingSample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXDockingSample/MainWindow.xaml))**
* [MainWindow.xaml.cs](./CS/DXDockingSample/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/DXDockingSample/MainWindow.xaml.vb))
<!-- default file list end -->
# How to: Remove Items from the Context Menu


<p>This example shows how to remove items from the LayoutPanel context menu.</p>
<p>In this sample, the 'Dock', 'Float', and 'Auto Hide' items are removed from the LayoutPanel context menu. For this purpose, three RemoveBarItemAction objects are added to the DockLayoutManager's ContextMenuCustomizations collection. Their ItemName properties are set to DefaultMenuItemNames.Dockable, DefaultMenuItemNames.Floating, and DefaultMenuItemNames.AutoHide, respectively.</p>

<br/>


