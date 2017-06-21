Symphony Stylesheets
====================

Stylesheets used for report exports in Symphony

What this is
------------

Our LMS, Symphony, has a reporting system that exports data in XML.  These exports can be transformed using XSLT (eXtensible Stylesheet Language Transformations).

This repository holds XSLT files for different types of data exports from Symphony.  Each folder represents a export type.  That folder may then include one or many different transformations.

Install
-------

These stylesheets could be run automatically against a Symphony XML export using an XSLT processor.  What Symphony allows for is for these to be installed on the Symphony server.  Then when exporting the data from a report, the relevant transformation can be selected and will automatically be downloaded along with the XML, and referenced within the XML.  When opening in a program such as Excel it then automatically applies.

To install on the server:

- Copy the XSLT files into the folders held at 'Unicorn/Rpt'
