# How to create custom timescale rulers with captions that depend on the current zoom level


**GanttView** provides the [RequestTimescaleRulers](https://docs.devexpress.com/WPF/DevExpress.Xpf.Gantt.GanttView.RequestTimescaleRulers) event where you can specify custom timescale rulers. In this example, we used a custom [IFormatProvider](https://docs.microsoft.com/en-us/dotnet/api/system.iformatprovider) implementation to format captions depending on the current zoom level.