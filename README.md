# MSDS692-Final-Project
Online presence for MSDS 692 Final Project, Automated Rail Inclusion Application

Desciptions of included files:

RailUT.ipynb
  This is the notebook code for the main application. This notebook connects to data servers, runs SQL queries, gathers the data, cleans the data, and exports the data to a central excel workbook for use in PowerBI Visualizations. The connections to the data serves and the path for the excel workbook were removed for confidentiality reasons. This code will not run; it is only to show and descibe how the application works.

GUI.ipynb
  This is the notebook code for the GUI interaction used in the application. It references and executes .Py version of the previously described file. Once the file is executed, the window automatically closes.
  
PowerBI Dashboard
  The final build to visualize the data collected and display in graphs.
  
DataCopy.xlsx
  A dummy version of the collected data, for use with the PowerBI Dashboard. Allows user to view graphs and the established connections/interactions. The file is data that was randomly generated, and does not represent accurate data collection. The real process data was removed for confidentiality reasons.  

Pyinstalled executed code.txt
  This is a txt file showing the output from the generation of a packaged .Py file. The final file is an executable that runs the .py files for both the GUI and RailUT notebooks. This file was packaged in such a way that any computer or user could use the file to execute the code; no python installation or code knowledge was needed. The actual file was too large to upload to Github, so I included the code for generating the file instead. Because some code was removed from RailUT for confidentiality, this application would not run either if it were included.
