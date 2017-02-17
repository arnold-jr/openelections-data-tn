# Use pandas and sklearn to ETL election data.

Election results are present in Excel spreadsheet format on 
the Tennessee Secretary of State website. Here, we use pandas to 
read the data directly from the URL. Then, we create an sklearn pipeline
to transform the data in a pipeline; this just makes it easier to read
and understand the steps in the transformation process.

## TODO:
- Unit testing for accuracy
- Comparison to PDF for accuracy
- Generalization to other TN election spreadsheet data

