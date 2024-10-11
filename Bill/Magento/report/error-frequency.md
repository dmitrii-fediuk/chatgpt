<!-- 2024-10-08 Dmitrii Fediuk https://upwork.com/fl/mage2pro
«Document the rules for generating statistics based on `mage2pro/core` reports about Magento 2 errors»:
https://github.com/dmitrii-fediuk/chatgpt/issues/7 -->
1. **Data source**  
   1.1. The source file must contain a list of log filenames.  
   1.2. Each filename corresponds to an error report in Magento 2.  
   1.3. The content of the table summarizes the error frequencies based on the filenames.
2. **Purpose of the table**  
   2.1. The table summarizes the most common errors by module, based on the filenames extracted from the log files.  
   2.2. It shows the percentage of cases for each error type.
3. **Table structure**  
   3.1. The table consists of two columns.  
   3.2. **First column**: Contains the error type (module name) in bold, followed by an example filename on the next line within the same cell.  
   3.3. **Second column**: Displays the percentage of cases corresponding to each module.
4. **Content rules**  
   4.1. Only the module name, example filename, and percentage of cases should be included.  
   4.2. No extra lines or columns should be added.