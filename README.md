# These are the features provided by SOQL Wave 
1. SOQL tool.
2. Create JSON Metadata.
3. Upload data to Wave


SOQL Tool:
- It lives right inside your org - so it's really quick & easy to get to. 
- The results appear in an HTML table, where you can easily cut & paste them. 
- ID fields show up as clickable links. 
- Joins are handled in a relational-type style - joined fields simply show up as additional columns, instead of as related/embedded objects. 
- You can see the raw query result if you want it (the result of the sforce.connection.query() call). 
- It supports SELECT * syntax. 
- It supports the DESC command. 
- It supports LIST OBJECTS to see a list of all sobjects. 
- You can get output in CSV format. 

Create JSON Metadata
Wave uses the JSON metadata uploaded to InsightExternalData to format/classify the raw data.
