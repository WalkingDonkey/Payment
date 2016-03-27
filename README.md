# Payment
A payment server for testing using Ping++ SDK.

## How to run this payment server:
* Install Node.js on your machine.
* Launch command window.
* Go into the directory "\Server\pingpp-nodejs".
* Run "npm install".
* Go into the directory "\Server\pingpp-nodejs\example".
* Run "node server.js".
* You can connect to the payment server just using Fiddler for test:   
   url: http://127.0.0.1:8010/pay    
   request body: {"channel":"alipay_wap", "amount":20}    
* You can also use other clients such as iOS, Android, html and etc.to connect to the server.
