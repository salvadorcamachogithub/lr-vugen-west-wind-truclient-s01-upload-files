Updated: 04.2025  
Script created by Salvador Camacho

This script was created with best practices, so it is more resilient, such as:
* Transaction naming
* No add cookies
* No third party
* One validation per transaction
* Think times at the end of each transaction to better simulate user behavior

This script shows TruClient ability to upload files when needed. The script goes to https://west-wind.com/wconnect/wcscripts/fileupload.wwd and does three different kinds of uploads:  
* Upload File Standard HTML Form Upload
* Ajax File Upload
* Uppy UI
	
Runtime Settings were set to log only on errors and generate snapshot on errors, think times random from 15 seconds to 25 seconds

There is a Web - HTTP/HTML script that does the same steps

This script has 3 transactions:  
West Wind-TruClient-S01-01 Homepage
West Wind-TruClient-S01-02 Upload File Standard HTML Form Upload
West Wind-TruClient-S01-03 Ajax File Upload
West Wind-TruClient-S01-04 Uppy UI