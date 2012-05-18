Tsk Summary Report Module
Sleuth Kit Framework C++ Module
May 2012

This module is for the C++ Sleuth Kit Framework.

C++ module that makes a generic summary output report

DESCRIPTION

This module is a reporting module that gets all data from the blackboard and 
uses it to populate a set of tables as follows: one table for each artifact type
in use. For each of those tables there will be a column for each attribute type
that appears in at least one artfiact. The rows of the table will be the individual
artifacts, with the columns for its attributes filled in. If an attribute is not
present for a column it is left blank. The report is created as an .htm file and 
can be viewed from a web browser.

TODO:
 - Add parameters to allow for selective artifact/attribute lookup for more custom
   reports.
 - Add a table of contents showing the artifact types and the counts of artifacts
   with links to the tables for easier navigation.

USAGE

Configure the reporting pipeline to include this module.

