<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128602332/22.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1467)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->


# Reporting for WinForms - How to Print a Report on a Dot Matrix Printer


This example shows how to print a report on a dot matrix printer. First, the report is exported to CSV format and saved to a temporary file in the current application directory. Then the [Process.Start](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.process.start) method initiates the printing process. In this example, the verb "Print" is assigned to the `ProcessStartInfo.Verb` property of the [ProcessStartInfo](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.processstartinfo) instance passed to the [Process.Start](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.process.start) method.

## Files to Review

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))

## Documentation

- [Print Reports](https://docs.devexpress.com/XtraReports/15797/detailed-guide-to-devexpress-reporting/store-and-distribute-reports/print-reports)
- [Export Reports](https://docs.devexpress.com/XtraReports/1302/detailed-guide-to-devexpress-reporting/store-and-distribute-reports/export-reports)

