Requires the following dependencies:

Upgraded R to version 4.1.2+
Install the following R packages (libraries): openxlsx, DDIwR

About:

The following branch is feature that integrates new download options for datafiles. This is done with DDIwR, that allows datafile conversion while maintaining
metadata in R. The following datafile options are excel, stata, spss and sas.

Note:
Downloads can fail based on original data and its incompatibility to be represented in the converted download,  This will give generic api error or empty file

For more information, see #3728 

