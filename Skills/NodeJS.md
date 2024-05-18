## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js
  - Stateful and stateless servers
  - Nonblocking I/O and blocking code
  - Event loop phases
  - Event loop microtasks and macrotasks
  - Garbage collection
  - Node.js LTS schedule
  - I/O-bound, CPU-bound, memory-bound tasks 👂 heard
  - Interactive applications (close to real-time)
- Modularity, layers and dependencies
  - CommonJS modules
  - ECMAScript modules
  - Module `node:module`
  - Caching in CJS and ESM
  - Modules as singletons
  - Contexts and scripts module `node:vm`
  - Dependencies: `npm`, `node_modules`
  - Files `package.json`, `package-lock.json`
  - Module-based permissions model
  - Isolation with modularity 👂 heard
  - Dependency injection 👂 heard
  - DI containers
  - Coupling and cohesion 🙋 explained
  - Framework agnostic approach 👂 heard
- Environment
  - Command line arguments
  - Node.js CLI
  - Process-based permissions
  - Graceful shutdown 👂 heard
  - Clustering
  - Watch filesystem changes with --watch 👂 heard
- Internal API
  - Streams API 👂 heard
  - Web Streams API
  - Crypto API
  - Password hashing with crypto.scrypt
  - Web Crypto API
<<<<<<< HEAD
  - File system API (sync and async) 👂 heard
=======
  - File system API (sync and async)
>>>>>>> 8765fa8111bfce69fb089873333d15ce57078733
  - Copy folder recursively
  - Worker threads 👂 heard
  - Performance hooks
  - Native fetch and nodejs/undici
  - async_hooks
<<<<<<< HEAD
  - AsyncLocalStorage 👂 heard
  - AsyncResource 👂 heard
=======
  - AsyncLocalStorage
  - AsyncResource
>>>>>>> 8765fa8111bfce69fb089873333d15ce57078733
  - Deprecated domain API
  - Node.js single executable
  - SharedArrayBuffer
  - Module `node:worker_threads`
  - Module `node:child_process`
  - MessageChannel, MessagePort
  - BroadcastChannel
  - Generating crypto random UUID
  - Module `node:url` vs `new URL`
  - Module `node:assert`
  - Internationalization
  - Blob, File, Buffer, module `node:buffer`
  - Module `node:zlib`
- Network
  - Endpoint throttling
  - ALPN
  - SNI callback
<<<<<<< HEAD
  - SSL certificates  heard
  - Protocol agnostic approach 👂 heard
  - Fetch API 🖐️ used
  - IncomingMessage
  - HTTP(S) 🎓 known
  - TCP/SSL 🎓 known
  - UDP 🎓 known
  - TLS 🎓 known
  - Websocket 👂 heard
=======
  - SSL certificates
  - Protocol agnostic approach
  - Fetch API
  - IncomingMessage
  - HTTP(S)
  - TCP/SSL
  - UDP
  - TLS
  - Websocket
>>>>>>> 8765fa8111bfce69fb089873333d15ce57078733
  - SSE
  - HTTP/3 (QUIC)
  - Long polling
  - REST 👂 heard
  - RPC 🎓 known
  - Routing 👂 heard
  - DoS 👂 heard
  - DDoS 👂 heard
  - XSS 👂 heard
  - Path traversal 👂 heard
  - CSRF
<<<<<<< HEAD
  - DNS 🎓 known
  - SQL injection 👂 heard
  - noDelay
  - keep-alive 👂 heard
=======
  - DNS
  - SQL injection
  - noDelay
  - keep-alive
>>>>>>> 8765fa8111bfce69fb089873333d15ce57078733
  - IP sticky sessions
- Technique and tools
  - Native test runner
  - Logging 👂 heard
  - Application configuring 👂 heard
  - Testing 👂 heard
  - CI/CD
<<<<<<< HEAD
  - Readable 👂 heard
  - Writable 👂 heard
  - Transform 👂 heard
  - Back pressure 👂 heard
=======
  - Readable
  - Writable
  - Transform
  - Back pressure
>>>>>>> 8765fa8111bfce69fb089873333d15ce57078733
  - Buffer
  - Console 👂 heard
  - Inspector
- Data access
  - Data access layer 🎓 known
  - Repository 🎓 known
  - Active record
<<<<<<< HEAD
  - Query builder 👂 heard
  - Object-Relational Mapping 🎓 known
  - CRUD
  - DTO
- Error handling and debugging
  - `Error` 🎓 known
  - `error.cause`
  - `error.code`
  - `error.message` 🎓 known
  - `error.stack` 🎓 known
  - `Error.captureStackTrace`
  - How to avoid mixins
  - Uncaught exceptions 🎓 known
=======
  - Query builder
  - Object-Relational Mapping
  - CRUD
  - DTO
- Error handling and debugging
  - `Error`
  - `error.cause`
  - `error.code`
  - `error.message`
  - `error.stack`
  - `Error.captureStackTrace`
  - How to avoid mixins
  - Uncaught exceptions
>>>>>>> 8765fa8111bfce69fb089873333d15ce57078733
  - Heap dump
  - Debugging tools
  - Flame graph
  - Memory leaks 👂 heard
  - Resource leaks 👂 heard
  - Data race 👂 heard
- Integrations and bindings
  - Native addons
  - `C` and `C++` addons
  - `Rust` addons
  - `Zig` addons
  - NAN (Native Abstractions for Node.js)
  - Node-API (formerly N-API)
  - NAPI `C` and `C++`
  - NAPI `Rust`
  - NAPI `Zig`
  - Webassembly `WAT`
  - Webassembly `C` and `C++`
  - Webassembly `Rust`
  - Webassembly `Zig`
  - Webassembly `AssemblyScript`
  - Shared memory
  - V8 binary serialization
