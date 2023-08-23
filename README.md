# ngrok-broadband-access
This is for accessing RDK-B webUI from internet

Steps to follow:
1.go to https://ngrok.com/download and go to linux section and download the bin which ever you want(ARM/ARM64)

2.Copy the binary to rdk-b device

3.ngrok config add-authtoken  <token>

  

Add authtoken
$
ngrok config add-authtoken <token>

Don’t have an authtoken?
get it from here https://dashboard.ngrok.com/get-started/setup




3.ngrok http 8080

   when you run above command below data will be populated and you can pick https url

  Note: 8080 is the port where lighttpd running(webUI)










