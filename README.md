# RestAPI-Status-codes
here you can get all the status codes of Rest Api.

.

📘 REST API Status Codes

HTTP status codes are grouped into 5 categories:

🔹 1xx – Informational

100 Continue → Request received, continue sending body.

101 Switching Protocols → Server agrees to switch protocol (e.g., WebSocket).

102 Processing → Request received, still processing (WebDAV).

103 Early Hints → Used to preload resources while server prepares response.

🔹 2xx – Success

200 OK → Request successful.

201 Created → Resource successfully created.

202 Accepted → Request accepted, processing later.

203 Non-Authoritative Information → Response modified by a proxy.

204 No Content → Request succeeded, no response body.

205 Reset Content → Tell client to reset the form/view.

206 Partial Content → Partial response (range requests).

207 Multi-Status → Multiple statuses (WebDAV).

208 Already Reported → Element already reported (WebDAV).

226 IM Used → Server fulfilled request using instance manipulation (rare).

🔹 3xx – Redirection

300 Multiple Choices → Several possible responses.

301 Moved Permanently → Resource permanently moved.

302 Found → Temporary redirection.

303 See Other → Redirect to another URI (GET).

304 Not Modified → Cached version still valid.

305 Use Proxy → Must access through proxy (deprecated).

306 (Unused) → Reserved.

307 Temporary Redirect → Resource temporarily moved, method preserved.

308 Permanent Redirect → Resource permanently moved, method preserved.

🔹 4xx – Client Errors

400 Bad Request → Invalid request syntax.

401 Unauthorized → Authentication required.

402 Payment Required → Reserved (sometimes used in APIs).

403 Forbidden → Authenticated but not allowed.

404 Not Found → Resource not found.

405 Method Not Allowed → HTTP method not supported.

406 Not Acceptable → Cannot return content in requested format.

407 Proxy Authentication Required → Need proxy authentication.

408 Request Timeout → Client took too long.

409 Conflict → Request conflicts with current state.

410 Gone → Resource permanently removed.

411 Length Required → Missing Content-Length.

412 Precondition Failed → One or more preconditions failed.

413 Payload Too Large → Request body too big.

414 URI Too Long → Request URL too long.

415 Unsupported Media Type → Server doesn’t support format.

416 Range Not Satisfiable → Invalid range request.

417 Expectation Failed → Expect header not fulfilled.

418 I’m a Teapot → Joke status (RFC 2324 😂).

421 Misdirected Request → Request sent to wrong server.

422 Unprocessable Entity → Semantic errors (WebDAV, APIs).

423 Locked → Resource locked (WebDAV).

424 Failed Dependency → Dependency request failed.

425 Too Early → Request replay risk.

426 Upgrade Required → Must upgrade to another protocol.

428 Precondition Required → Server requires conditions.

429 Too Many Requests → Rate limiting.

431 Request Header Fields Too Large → Headers too large.

451 Unavailable For Legal Reasons → Blocked for legal reasons.

🔹 5xx – Server Errors

500 Internal Server Error → Generic error.

501 Not Implemented → Method not supported.

502 Bad Gateway → Invalid response from upstream server.

503 Service Unavailable → Server overloaded or down.

504 Gateway Timeout → Upstream server took too long.

505 HTTP Version Not Supported → Unsupported HTTP version.

506 Variant Also Negotiates → Negotiation error.

507 Insufficient Storage → Not enough space (WebDAV).

508 Loop Detected → Infinite loop detected (WebDAV).

510 Not Extended → Further extensions required.

511 Network Authentication Required → Network login/auth required.

✅ Quick Memory Hack:

1xx = Info

2xx = Success

3xx = Redirect

4xx = Client error

5xx = Server error
