# webproxy

# python Proxy.py localhost 8080

# curl -iS http://localhost:8080/http://http.badssl.com/

# curl -iS http://http.badssl.com/

# curl -iS http://localhost:8080/http://http.badssl.com/fakefile.html

# curl -iS "http://localhost:8080/http://httpbin.org/redirect-to?url=http://http.badssl.com&status_code=301"

# curl -iS "http://localhost:8080/http://httpbin.org/redirect-to?url=http://http.badssl.com&status_code=302"

# curl -iS "http://httpbin.org/redirect-to?url=http://http.badssl.com&status_code=301"

# curl -iS "http://httpbin.org/redirect-to?url=http://http.badssl.com&status_code=302"

# curl -iS "http://localhost:8080/http://httpbin.org/cache/0"

# curl -iS "http://localhost:8080/http://httpbin.org/cache/3600"
