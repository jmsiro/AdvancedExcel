



# Excel Advanced Options
  
Módulo con opciones avanzadas para Excel  

## How to install this module
  
__Download__ and __install__ the content in 'modules' folder in Rocketbot path  


## How to use
To use this module, you must have Microsoft Excel.


## Descripción de los comandos

### Abrir sin alertas

  
Open a file without displaying alert banners.
|Parameters|Description|example|
| 
## Overview


1. Open Without Alerts  
Open a file preventing MS Excel alerts.

2. Find and Connect  
Search a Excel Book opened and connect it

3. Count columns  
Count the columns or return the last column name. It's necessary that the excel is saved to get the last changes

4. Count Rows  
Counts all the rows or from a range.

5. Cell color  
Change color of a cell or range of cells. Can be a default color or custom 

6. Insert Formula  
Insert formula into cell

7. Insert Macro  
Insert Macro in Excel

8. Select Cells  
Select cells in Excel

9. Get Cell With Currency Format  
Get cells with currency format

10. Get Cell With Date Format  
Get cells with date format

11. Copy-Paste  
Copy range cell to another sheet

12. Format Cell  
Format Cell

13. Create Sheet  
Create sheet in the end

14. Delete Sheet  
Delete sheet

15. Copy to another excel  
Copy range to another Excel in the background

16. Add/Delete Row  
Add or Delete a Row

17. Add/Delete Column  
Add or Delete a Column

18. Convert CSV to XLSX  
Convert a csv document to xlsx

19. Convert XLSX to CSV  
Convert a xlsx document to csv

20. Convert XLS to XLSX  
Convert a xls document to xlsx

21. Get active cell  
Get row and column of active cell

22. Refresh Pivot table  
Refresh a pivot table. Deprecated! Use PivotTableExcel module

23. Fit cells  
Adjusts, groups and ungroups a range of cells. You can group/ungroup by rows or columns

24. Get Formula  
Get the formula into cell

25. Add Auto Filter  
Add auto filter to excel table

26. Filter  
Add filter to excel table

27. Rename sheet  
Change name to excel sheet

28. Cell Style  
This command modifies the formatting of the selected cell or range of cells. You can change the font and borders

29. Paste in Cells  
Paste data to cells in Excel

30. Remove Duplicates  
Execute the remove duplicates command of Excel

31. Save Excel  
Save a Excel file in the indicated path

32. Export to advanced PDF  
Export to PDF with options

33. Copy-Move Sheet  
Copy or move a sheet

34. Insert Form  
Insert Form in Excel

35. Read Filtered Cells  
Allow read only cells filters 

36. Count Filtered Cells  
Allow count only cells filters 

37. Replace  
Run replace action to excel 

38. Order  
Run replace action to excel 

39. Refresh All  
Refresh all data in Excel

40. Find  
Return de first found cell 

41. Lock Cells  
Lock or Unlock cells

42. Add Chart  
Create a new chart in an excel sheet

43. Remove Password  
Remove password and save the Excel

44. Insert image  
Insert an image

45. Export Chart  
Export a chart from index

46. Not visible mode  
Open not visible excel.

47. Write array objects  
Write array object on Excel cells.

48. Copy-Paste Format  
Copy format range cell to another sheet

49. Update links  
Changes a link from one document to another

50. Unlock sheet  
Unlock sheet

51. Convert to .txt  
Convert to .txt

52. Text to columns  
Parses a column of cells that contain text into several columns.

53. Convert Excel time to hours  
Convert Excel time to hours. Returns the format as hh: mm: ss

54. Print sheet  
Prints a sheet

55. Save Excel with password  
Save a Excel file

56. Save Excel  
Save a Excel file in the indicated path

57. Close XLSX  
Close the workbook opened by Rocketbot  

### Updates
#### 12-May-2022
- Copy to another excel: fixed command to copy from one excel to another
#### 18-Apr-2022
- Text to Column: command fixed to separate text in columns
#### 06-Apr-2022
- Fit Cells: Added merge cells, adjust rows, adjust columns functions
#### 28-Dec-2021
- Count Rows: command fixed to count all rows.
#### 9-Nov-2021
- Order command: Apply multiple orders and clean filters.
#### 13-Oct-2021
- Fix count cells filtered
#### 30-Sep-2021
- Paste command: Update compatibilities
#### 28-Sep-2021
- Fix get filtered cells command. Now returns extended data
#### 06-Jul-2021
- Fix language
#### 01-Jul-2021
- Read Filtered Cells: The command was fixed because it didn't getting all cell range
#### 27-Apr-2021
- Texto to column: Parses a column of cells that contain text into several columns.
#### 18-Mar-2021
- Unlock sheet: Convert XLSX to TXT.
#### 09-Mar-2021
- Unlock sheet: Unlock a sheet by password.
#### 09-Mar-2021
- Update links: Changes a link from one document to another
#### 17-Feb-2021
- Find and Connect: Find opened Excel file and connect it
#### 1-Feb-2021
- Add command Copy-Paste Format. You can copy format cell to another.
#### 25-Jan-2021
- Write array objects: Writes information obtained from an array of objects to excel cells
#### 21-Jan-2021
- Not visible mode: Open background Excel
#### 1-Dec-2020
- Export chart: Export a chart from index.
#### 24-Nov-2020
- Insert image in a cell.
#### 24-Sep-2020
- Open without alerts: Add field 'Password'
#### 16-Sep-2020
- Add chart: Create a new chart on excel sheet 
#### 15-Sep-2020
- Lock Cells: Lock or unlock cells 
#### 2-Sep-2020
- Find: Replicate Excel Find command 
#### 31-Jul-2020
- Order: Replicate Excel Order command 
#### 15-Jul-2020
- Read Filtered Cells: Read cell after execute Filter command
- Replace: Replicate Excel Replace command 
#### 2-Jul-2020
- Insert Form: Rocketbot can insert VBA Form to Excel
#### 30-Jun-2020
- Csv to xlsx: Checkbox header was added to decide if the csv has a header
- Export to Advanced PDF: Rocketbot export to PDF command enhancement
- Copy-Move Sheet: Replicate move/copy sheet command of Excel
#### 17-Jun-2020
- Remove duplicates: Rocketbot can now remove duplicate data on range Excel
#### 5-Jun-2020
- Focus Excel: Rocketbot can now set Excel to the foreground window

----
### OS

- windows
- mac

### Dependencies
- [**xlwings**](https://pypi.org/project/xlwings/)- [**pandas**](https://pypi.org/project/pandas/)
### License
  
![MIT](https://camo.githubusercontent.com/107590fac8cbd65071396bb4d04040f76cde5bde/687474703a2f2f696d672e736869656c64732e696f2f3a6c6963656e73652d6d69742d626c75652e7376673f7374796c653d666c61742d737175617265)  
[MIT](http://opensource.org/licenses/mit-license.ph)