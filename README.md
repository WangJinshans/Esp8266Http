# Esp8266Http
This is a demo for Esp8266 WiFi chip which could send a simple Get or Post request with data you want to send to your server.The server you 
can build with PHP or ASP or JSP and so on.Get the data and do what you want.
I hava build my server with JSP,only one jsp and one Servlet which can handle the request.
Anyone who refer to my demo 
need to change this "GET /EspTestServlet?name=yourData HTTP/1.1\r\nUser-Agent: curl/7.37.0\r\nHost: 192.168.1.117:8088\r\nAccept: */*\r\n\r\n"" phrase
and build your own server.
