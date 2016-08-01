Here are the types of requests:
| Types |
| ----- |
| SRV REQ: Server response. |
| SRV ERR: Server error response. |
| CLNT REQ: Client request. |
| CLNT ERR: Client error. |


Status codes are as follows:

Code | Argument
---- | --------
SRV REQ: 100 - Document transmission | STRING body
SRV REQ: 101 - Download file | STRING location
CLNT REQ: 102 - Document request | STRING location
CLNT REQ: 103 - Submit data | STRING data
SRV REQ: 200 - Redirect | STRING location
SRV ERR: 201 - Not found | 
CLNT ERR: 202 - Document Parsing Error |
SRV ERR: 203 - Max resource usage |
SRV ERR: 300 - Bad Request |
SRV ERR: 301 - Server unavailable. |




