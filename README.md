# QR-Code-Scanner

## Steps it follows to Scan QR Codes :
1. Initiallize Camera ( Either default camera[0] or external camera ).
2. Detect QR Code or Barcode, its type, shape, polynomial points and Data.
3. Matches QR Code or Barcode data from data list given in myDataFile.text
4. Print True or False on behalf of data detected. If Detected Data is Present in myDataFile.text, function will print "True" on Display with Polylines, else it will display "False" on screen with polylines.
