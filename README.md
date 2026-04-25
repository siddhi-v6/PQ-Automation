# PQ-Automation
Browser-based tool to verify Process Qualification reports — upload an Excel file to validate measurements against USL/LSL limits, analyse SPC callouts by Cpk, and visualise part distributions with box plots.


What it does

Reads the Data Sheet tab from any PQ Excel report
Flags out-of-range measurements — cells turn red where a part's value falls outside its USL/LSL tolerance, with a collapsible summary panel listing every failed callout and the exact parts that failed
SPC Analysis — filters all SPC callouts and buckets them into three Cpk categories (capable / marginal / not capable)
Box plots — one per SPC callout showing measurement spread, individual part values, and USL/LSL reference lines
How to use

Open the link
Upload your .xlsx PQ report
Review flagged callouts and SPC analysis
Notes

Works entirely in the browser — no data is sent to any server
No installation or internet connection required after the page loads
Compatible with Chrome, Safari, Firefox, and Edge
