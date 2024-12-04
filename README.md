### Mindex Data & Analytics Code Challenge
## Project Purpose
This project demonstrates an ETL pipeline by:
- Extracting data files from AWS.
- Transforming and joining the data to prepare it for analysis.
- Loading the cleaned data into a Postgres database.
- Writing and executing queries against the database.

## File Structure
/notebook/bengels_etl.ipynb - notebook that holds etl code
- /data - file that holds the extracted data and combined data in .csv

  
## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repo-name.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a `.env` file and add your environment variables:

ACCESS_KEY_ID=your-accesskey
SECRET_ACCESS_KEY=secret-key
DB_HOST=db-host
USERNAME=user-name
PASSWORD=password
DB_NAME=db-name
TABLE_NAME=table-name
ADDRESS=address


*note I got the address from running in my terminal

nslookup host-url-given

## A Note of Thanks

Thank you for providing this opportunity to do this assignment. It was fun! :)  
_Go Bengals! (just kidding, I am a Steelers fan)_
