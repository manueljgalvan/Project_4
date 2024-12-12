# Project_4

### This project is looking that a live dataset from the FDA Recall catalog and conducted analysis on the Process for classification of Recalls, the selected model should predict the duration between the Center Classification Date vs Recall Initiation Date; basically predicting how long a recall is outstanding

### Team 3 Members
- Manuel Galvan
- Natalia Galvan
- Joe Almendarez
- Teddy Song
- Lynn Foster

### Tools Used for this Project
- Pandas
- MongoDB Database
- ML Library ???
- Tableau

### ETL 
- API Integration
- Data Cleaning
  - Status (Remove anything not "Terminated"
  - Country (Remove anything not "United States"
  - Drop "Open FDA", "Event", "Product Type", "Address 2"
  - Keep "Status, City, State, Classification, Recalling Firm, Address 1, Postal Code, Recall Initiation Date, Center Classification Date, Termination Date 
- Date Formatting - since the orginal format limited the calucations needed for a new column value "Days to Classify"
- Derived Metrics
- Database Integration using MongoDB
- Post Processing - Pulling from a Database into a new Pandas DataFrame

### ML Method
- Supervised Learning

### Cleaning options
- Status (Remove anything not "Terminated"
- Country (Remove anything not "United States"
- Drop "Open FDA", "Event", "Product Type", "Address 2"
- Keep "Status, City, State, Classification, Recalling Firm, Address 1, Postal Code, Recall Initiation Date, Center Classification Date, Termination Date 
