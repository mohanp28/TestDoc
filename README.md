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
Wave uses the JSON metadata uploaded to InsightExternalData to format/classify the raw data. SOQL Wave  provides an UI based configuration to create these complex JSON behind the sceen.

These are the highlights:
1. Auto classify metadata field types based on the  actual salesforce field data type.
   FieldType of INTEGER/DOUBLE/CURRENCY are classified to Numeric.
   FieldType of DATE/DATETIME are classified to Date.
   All other FieldType as Text
2. Change facts to dimension.
   By default metadata detection classifies INTEGER/DOUBLE/CURRENCY dataTypes as Numeric. If the use case requires a specifc filed to be classifed as dimension, then user can edit the data type from Numeric to Text. The same applies for the datatype "Date"
3. 
