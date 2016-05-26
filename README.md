# sqrCsvParse
PeopleSoft SQR to read/pre-process csv files with embedded CRLFs, double quotes

When your csv file is more complicated that Unstring can handle, this SQC may help.  It will read, and optional re-format, a csv file that utilizes double quote to enclose fields with commmas, quoted fields with embedded CRLFs, and quote fields with embedded quotes.

Also, instead of reformatting the file, this can be used to process the file either 1 row at a time, or even by each field.  See attached sample SQR and sample csv file to get started.
