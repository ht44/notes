# cURL Notes

* [home page](https://curl.haxx.se/)
* [manual page](https://curl.haxx.se/docs/manpage.html)

#### Utility Flags
###### (format example: "-flag argument")

* -h                  List commands
* --manual            Full manual
* bx curl -h          Short list of common flags


#### Common Flags

* -i                  Include response headers in the output
* -v                  Enable trace output for all requests and responses
* -X value            HTTP method (GET, POST, PUT, DELETE, etc, default is GET) (default: "GET")
* -H value            Custom headers to include in the request, flag can be specified multiple times
* -d value            HTTP data to include in the request body (POST / PUT)
* -o value            Write curl body to file instead of stdout


#### Other Important Flags

* -I                  Output response headers but not response content
* -T file             Transfers the specified local file to the remote URL
* -u name:password    Specify the user name and password to use for server auth
* -b value            Pass the data to the HTTP server in the Cookie header                 
* -c file             Specify to which file you want curl to write all cookies after a completed operation

#### Watchlist

* -K                  Specify which config file to read curl arguments from
* -E certificate      Tells curl to use the specified client certificate
