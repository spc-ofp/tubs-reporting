TUBS Reporting sub-project
===

In general, reports use the following naming conventions:

* "PS-" Report covers purse seine fishing.
* "LL-"  Report covers longline fishing
* "Global" Report covers all programs, flag states, and years.  Report accepts values for these parameters to filter results.

This project contains the following report definitions:

* CoverPage:  Printable cover page for report.  SPC uses the cover-page in the workflow of entering printed reports.
* FfaProgramSummary:  A report of the number of observers, trips, and sea days for FFA member observer programs.
* GlobalTripMonitoring:  Breaks down the number of GEN-3 incidents by observer program, flag state and vessel.  NOTE:  This report is written against the pre-2009 revisions of the GEN-3 form.
* GlobalTripMonitoringVR09:  Breaks down the number of GEN-3 incidents by observer program, flag state, and vessel.  NOTE:  This report is written against the 2009 revision of the GEN-3 form.
* LL-GlobalCatchAndEffort:  Regional longline catch and effort report.
* LL-TripSummary: Summary of a single longline trip.
* PS-GlobalCatchAndEffort:  Regional purse seine catch and effort report.
* PS-TripSummary:  Summary of a single purse seine trip.

Use the following naming conventions for data text fields within a tablix:

* All fields within a tablix should have the same prefix
* The prefix should relate to the data in the table (e.g. "Target Catch by Association" is "TCA_")
* A field representing the same concept should have the same suffix across each table (e.g. total weight in each table should end with "totalWeight")

At some point in the future I may create some actual rules for field names.  This document would be intended not only for report writers, but also anyone who needs to extract data from a CSV export.