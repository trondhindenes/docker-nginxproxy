Run Nginx proxy controlled by environment variables

Required vars:
- PROXYURL: full url of where to proxy traffic. Example: https://www.google.com
- PROXYHOSTHEADER: host header to pass to the destination. set to `$host` if you don't want to use it