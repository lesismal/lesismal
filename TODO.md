### arpc
1. ~~release stream feature~~

### nbio
1. add comments
2. ~~http: handle request before whole body received~~ - blocking body reading will block goroutine for long, give up
3. blog
4. ~~rewrite ws parser logic, rename nbhttp.ReaderCloser to ParserCloser~~
5. ~~nbio.Conn write cache use body allocator~~
6. ~~update go-websocket-benchmark nbio version, wsconn.Parse~~
7. ~~aligned append free old~~
8. async dial, onConnected, MTCP, PROXY

### sqlw
1. ~~fix lower case~~
