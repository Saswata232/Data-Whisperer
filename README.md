# DataWhisperer README

UPDATE --- Verified as functional as of Tableau 10.5.1

UPDATE --- Data Whisperer is now available for Python 3.x and modified for the XML schema changes in Tableau 10.4. The compiled code will be added soon.

An NLP text query visualization builder for Tableau Desktop.

The Python version requires Python 2.7 and the xml and tkFileDialog packages as well as the Personal Edition of Tableau Desktop for Excel connections or the Professional Edition for Excel and SQL Server connections. View the DataWhispererExample gif to see DataWhisperer in action!

To install Python 2.7 visit https://www.python.org/downloads/

For information on adding the required packages see: https://packaging.python.org/installing/

The .exe version of Data Whisperer was created using http://www.pyinstaller.org/

### Python Instructions:

1) Open Tableau Desktop and connect to an SINGLE Excel or SQL Server data source then save the workbook as a .twb.

2) If Python is on your system path simply set you directory in cmd to the location of of DataWhisperer.py and run 'python DataWhisperer.py'. Otherwise include the full file path location for DataWhisperer.py when running python.

3) Follow the prompts to select the source workbook. The file selection prompt may be minimized in the task bar as an iPython process.

4) Folow the prompts to select a save location for the new workbook, then view the availible data in the dimensions and measures.

5) Run a query to begin building visualizations! Queries can include 'Show me sales by region', 'Lets see average profit by order date', or 'Show me sales by sub-category as a gantt bar'.

6) Some features such as multiple dimensions and measures on rows and columns, maps and scatter plots, sorting, and calculations are not yet availible, but may be added in future releases. Support for Tableau Data Extracts is also planned.

### Common Issues:

1) Some users have encountered issues with the automatic save location setting. To fix this simply enter a desired file location rather than hitting enter for the default Desktop location.

2) You will need to reconnect the sample workbook to the sample data source after downloading it.

3) Data Whisperer is only tested on Excel and SQL Server sources.

4) Data Whisperer is designed to be used with only workbooks that have a connection to a single data source.

5) The current query system does not handle more complex visualizations like maps, scatter plots, sorting, or creating calculations though these features are planned for future releases. Support for Tableau Data Extracts is also planned.
