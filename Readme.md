<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
* [Program.cs](./CS/Program.cs) (VB: [Program.vb](./VB/Program.vb))
* [XtraReport1.cs](./CS/XtraReport1.cs) (VB: [XtraReport1.vb](./VB/XtraReport1.vb))
<!-- default file list end -->
# How to print a report in dot matrix printer


<p>This example demonstrates how to print a report in a dot matrix printer. First, a report is exported to the CSV format and saved to a temporary file in the current application directory. Then the Process.Start() method initiates the printing process. Note that the "Print" verb is assigned to the ProcessStartInfo.Verb property of the ProcessStartInfo instance passed to the Process.Start() method.</p>

<br/>


