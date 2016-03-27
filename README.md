# Payment
A payment server for testing using Ping++ SDK.

How to run this payment server:
1. Install Node.js on your machine.
2. Launch command window.
3. Go into the directory "\Server\pingpp-nodejs".
4. Run "npm install".
5. Go into the directory "\Server\pingpp-nodejs\example".
6. Run "node server.js".
7. You can connect to the payment server just using Fiddler for test: 
   url: http://127.0.0.1:8010/pay
   request body: {"channel":"alipay_wap", "amount":20}
8. You can also use other clients such as iOS, Android, html and etc.to connect to the server.
