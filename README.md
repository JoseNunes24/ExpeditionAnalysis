# Expedition Analysis

Note: In the day to day, the import process is not the same, as I use a Google Drive Folder where I upload the files to, and when the script is running, it gerenates a Google OAuth 2.0 Token to access the csv's, so the user only has to insert this key and the files then are uploaded directly to the folder/downloaded. 

Some code is also slightly different, so as to mask the data, and some is also slighty optimized currently, which I have to adapt to this code.

This script serves as a Pipeline to speed up the modelling of the data. The reason I felt the need to build this script was that the dimension of the data was getting too big, and while Excel is a great tool, with such data it was too slow for the analysis I needed. Something that would take more than half a day now takes 5 minutes.

After this data is processed, a report is generated in Excel (DadosReport.xlsx), which then goes to a folder where various files are gathered (from SAP and Access Data) and where another Excel File, usng Power Query, transforms all this data in a single file, combining it to improve the analysis and report creaiton in POwer BI, the final destination of these files.
