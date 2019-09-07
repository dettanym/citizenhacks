# citizenhacks
FOR ISSUANCE: 
1. Download the IRMA app (on Play store)
2. Go here: https://privacybydesign.foundation/attribute-index/en/irma-demo.RU.studentCard.html 
3. Put in (random) details here to get a credential - scan the QR code with the app. 
FOR VERIFICATION: 
1. Set up verification server: https://irma.app/docs/getting-started/#installing-and-running-irma-server 
2. Set up the requester proxy to talk with the verification server: https://irma.app/docs/getting-started/#perform-a-command-line-irma-session
You will get a QR code if the proxy can talk to the server. 
3. Scan the QR code with your app to see what attributes are being asked for and to choose which ones to reveal. 
