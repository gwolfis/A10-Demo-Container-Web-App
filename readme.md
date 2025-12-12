# A10 Demo Container Web App
A lightweight A10 Networks demo container running Apache 2 + PHP 8.2.
Shows live request & header info on an A10 branded diagnostics page, perfect for validating ADC behavior, VIPs, X-Forwarded-For, host headers, and now HTTPS/TLS details.

--------
Features
--------
✅ Apache 2 + PHP 8.2 runtime

✅ Displays web-server & client details

✅ Detects and shows X-Forwarded-For (incl. header value)

✅ HTTPS (443) support with self-signed fallback

✅ Diagnostics show TLS protocol & cipher (when HTTPS terminates here or via proxy headers)

✅ Dynamic background color via env var

✅ Rotating slideshow with A10-themed images

✅ Ready for labs, demos, and cloud


![screenshot](docs/images/A10-Demo-Container-Web-App.png)

-----------------
Where to Download?
-----------------
The A10 Demo Container Web App can be pulled from Docker Hub by following the link: <https://hub.docker.com/r/gwolfis/a10-aadc-demo>

-------------
Documentation
-------------
Please follow the link to get a detailed description how to use the A10 Demo Container Web App: https://a10-demo-container-web-app.readthedocs.io