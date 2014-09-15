The datasets in this collection contain all the data available from (WikiLeaks' Spy Files releases)[https://wikileaks.org/the-spyfiles.html], up to the latest SpyFile 4 released on September 15th 2014.
The spreadsheets in the collection are:

1. Leaked Company Documents
Is the main spreadsheet, containing all the 632 leaked company documents. Documents have information on: 
  - Document Name
  - Company
  - Document Type	
  - Year
  - Countries
  - Tags
  - Target System	
  - Product	
  - Document Page	
  - Download Link	
  - Spy FIles Release
  
2. Companies mentioned in Spy Files
Is a list of all the companies who authored the leaked documents of Spy Files 1-4. It can be used to create a relational databse by connecting the other .CSV files that contain the variable "Company".

3. Customers of FinFisher
Contains the data published in Spy Files 4, which exposes the customers of the FinFisher software developed by the German company Gamma.
Variables include:
  - Username	
  - ID	
  - Country Attribution	
  - Number of Licenses	
  - Current Customer?	
  - Total Costs	
  - Total Costs (with "deleted" licences)
  - Software Purchased
  
4. FinFisher Software
Contains the data published in Spy Files 4.
It is a list of all software developed by Gamma's FinFisher. Contains also a brief description. Can be used to create a relational database by connecting the other .CSV files that contain the variable "Product"

5. Subjects Tracked by WLCIU
Containes the data published in Spy Files 3, exposing the localization and travels of businessmen affiliated with the surveillance companies.
It includes the following variables:
  - Name of Tracked Subject
  - WikiLeaks Page
  - Company
  - Year
  - Countries
