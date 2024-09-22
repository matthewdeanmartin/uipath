# UI Path Examples

These are examples I created while learning about UI Path.

## HTML Screen Scraper

This scrapes a copyright right engine for a simple search then puts the results from the table into an Excel file.

- Opens browser
- Fills in simple search, clicks button
- Clicks "table view" on results
- Uses scaper activity to download all records to

Opportunities for improvement:

- implement components for simple search and advanced search
- feed search criteria from an input file

## PDF Scraper

This downloads a PDF and extracts text, then writes it to a file.

- Downloads file
- Uses text scraping to extract text from PDF to text file.

Opportunities for improvement:

- Use regex or the like to extract numbered lists.

## TODO: Microservice and API Status Page

It would be useful to have an API status page. Many 3rd party products exist, but they're usually hosted, only have
access to public sites and are not going to get through purchasing.

- Get service endpoints list from file
- Call each endpoint, use error handling to record either success or failure.
- Call python script to convert the data to a stop-light dashboard.

## TODO: Send PDF

A government website has the ability to send HTML emails. If it didn't, then the download button could be used to
simulate such a feature

- Search for a set of records.
- Download multiple files in PDF format
- Zip them
- Send them in a single email