# WPF Dock Layout Manager - Remove Items from the Context Menu

This example removes items from the LayoutPanel context menu.

<img src="https://user-images.githubusercontent.com/12169834/175367325-d408182e-9765-4674-9493-5a6c067ee745.png" width=620px/>

In this sample, the 'Dock', 'Float', and 'Auto Hide' items are removed from the [LayoutPanel](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutPanel) context menu. To do this, three [RemoveBarItemAction](https://docs.devexpress.com/WPF/DevExpress.Xpf.Bars.RemoveBarItemAction) objects are added to the [DockLayoutManager](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DockLayoutManager)'s [ContextMenuCustomizations](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DockLayoutManager.ContextMenuCustomizations) collection. Their ItemName properties are set to [DefaultMenuItemNames.Dockable](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DefaultMenuItemNames.Dockable), [DefaultMenuItemNames.Floating](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DefaultMenuItemNames.Floating), and [DefaultMenuItemNames.AutoHide](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DefaultMenuItemNames.AutoHide).

<!-- default file list -->
## Files to Look At

* [MainWindow.xaml](./CS/DXDockingSample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXDockingSample/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/DXDockingSample/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/DXDockingSample/MainWindow.xaml.vb))
<!-- default file list end -->

## Documentation

* [Visual Elements: Context Menus](http://docs.devexpress.com/WPF/6827/controls-and-libraries/layout-management/dock-windows/visual-elements)
