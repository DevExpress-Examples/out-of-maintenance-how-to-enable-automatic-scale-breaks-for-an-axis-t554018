<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128569871/17.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T554018)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/ScaleBreaks/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/ScaleBreaks/MainWindow.xaml))
<!-- default file list end -->
# How to: Enable Automatic Scale Breaks for an Axis


This example shows how to automatically split an axis by scale breaks.


<h3>Description</h3>

To do this, assign an <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.AutoScaleBreaks.class">AutoScaleBreaks</a>&nbsp;object to the <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.Axis2D.AutoScaleBreaks.property">Axis2D.AutoScaleBreaks</a>&nbsp;property. Then, set the <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.AutoScaleBreaks.Enabled.property">AutoScaleBreaks.Enabled</a>&nbsp;property to <strong>true&nbsp;</strong>to automatically create scale breaks for an axis. Limit the maximum possible number of auto-created scale breaks using the&nbsp;<a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.AutoScaleBreaks.MaxCount.property">AutoScaleBreaks.MaxCount</a><strong>&nbsp;</strong>property.

<br/>


