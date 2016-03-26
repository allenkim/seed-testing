# Testing Template to Read and Write from Excel Sheets

Change the parameters in spreadsheetInfo.js found in the js folder to change Excel parameters.

Instructions for Input and Output

For input:

In Google Docs, go to File menu and then, Publish to the web. Adjust options however and then click Start publishing. A URL will appear, something like https://docs.google.com/spreadsheet/pub?key=0Arenb9rAosmbdG5GWHFXbWJlN1hTR2ZmN3lZMVZkOHc&output=html

Use the unique key in the quiz input in index.html.

For output:

Go to Tools and then Script Editor. Use the Google App Script found here: https://gist.github.com/mhawksey/1276293

The usage is from the link provided.

// Usage
//  1. Enter sheet name where data is to be written below
        var SHEET_NAME = "Sheet1";
        
//  2. Run > setup
//
//  3. Publish > Deploy as web app 
//    - enter Project Version name and click 'Save New Version' 
//    - set security level and enable service (most likely execute as 'me' and access 'anyone, even anonymously) 
//
//  4. Copy the 'Current web app URL' and post this in your form/script action 
//
//  5. Insert column names on your destination sheet matching the parameter names of the data you are passing in (exactly matching case)

You want to insert this into the AJAX request in index.html as well.