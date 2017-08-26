# Cro documentation

## Introductory Material

The essentials you need to know to get building with Cro.

* [Creating HTTP Services](intro/http-server)
* [Making HTTP Requests](intro/http-client)

## Beyond The Basics

Ready to dig a deeper? These articles explain the Cro design and structure,
as well as covering some more advanced topics.

* [The Cro Approach](approach)
* [Module Structure](module-structure)
* [The cro Development Tool](cro-tool)
* [The .cro.yml File](cro-yml)

## Reference

The full details, organized by module.

### Cro::Core

* [Cro::Uri](reference/cro-uri)

### Cro::SSL

* [Cro::SSL](reference/cro-ssl)

### Cro::HTTP

* [Cro::HTTP::Client](reference/cro-http-client)
* [Cro::HTTP::Client::CookieJar](reference/cro-http-client-cookiejar)
* [Cro::HTTP::Cookie](reference/cro-http-cookie)
* [Cro::HTTP::DateTime](reference/cro-http-datetime)
* [Cro::HTTP::Message](reference/cro-http-message)
* [Cro::HTTP::Request](reference/cro-http-request)
* [Cro::HTTP::Response](reference/cro-http-response)
* [Cro::HTTP::Router](reference/cro-http-router)
* [Cro::HTTP::Server](reference/cro-http-server)

### Cro::WebSocket

* [Cro::HTTP::Router::WebSocket](reference/cro-http-router-websocket)
* [Cro::WebSocket::Client](reference/cro-websocket-client)
* [Cro::WebSocket::Frame](reference/cro-websocket-frame)
* [Cro::WebSocket::FrameParser](reference/cro-websocket-frameparser)
* [Cro::WebSocket::FrameSerializer](reference/cro-websocket-frameserializer)
* [Cro::WebSocket::Handler](reference/cro-websocket-handler)
* [Cro::WebSocket::Message](reference/cro-websocket-message)
* [Cro::WebSocket::MessageParser](reference/cro-websocket-messageparser)
* [Cro::WebSocket::MessageSerializer](reference/cro-websocket-messageserializer)

### Cro::ZeroMQ

* [Cro::ZeroMQ](reference/cro-zeromq)

### Cro::Tools

The development tools are mostly without API docs, as they are mostly not
expected to be extended from the outside at this point. However, the following
parts have stable APIs for the sake of extending the tools.

* [Cro::Tools::Template](reference/cro-tools-template)

---
