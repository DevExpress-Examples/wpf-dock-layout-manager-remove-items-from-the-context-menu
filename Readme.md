<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/DXDockingSample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXDockingSample/MainWindow.xaml))**
* [MainWindow.xaml.cs](./CS/DXDockingSample/MainWindow.xaml.cs) (VB: [MainWindow.xaml](./VB/DXDockingSample/MainWindow.xaml))
<!-- default file list end -->
# How to: Remove Items from the Context Menu


<p>This example shows how to remove items from the LayoutPanel context menu.</p>
<p>In this sample, the 'Dock', 'Float', and 'Auto Hide' items are removed from the LayoutPanel context menu. For this purpose, three RemoveBarItemAction objects are added to the DockLayoutManager's ContextMenuCustomizations collection. Their ItemName properties are set to DefaultMenuItemNames.Dockable, DefaultMenuItemNames.Floating, and DefaultMenuItemNames.AutoHide, respectively.</p>

<br/>


