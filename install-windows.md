https://adoptium.net/temurin/archive/

https://www.zaproxy.org/download/


$ zap.bat -config api.addrs.addr.name=.* -config api.addrs.addr.regex=true


$ curl "http://localhost:8080/OTHER/core/other/htmlreport/?apikey=ds8f9sit2vhdkcpc5v9a087plt" -o ZAP_Report.html


- With $Build.Number

$ $ Invoke-WebRequest -Uri "http://localhost:8080/OTHER/core/other/htmlreport/?apikey=ds8f9sit2vhdkcpc5v9a087plt" -OutFile OWASP-ZAP-Report-20241107.6.html
