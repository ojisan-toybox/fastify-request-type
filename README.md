# fastify-request-type

fastify の request object の中身を見る

```js
{
  id: 'req-1',
  context: Context {
    schema: undefined,
    handler: [Function: bound ],
    Reply: [Function: _Reply] { props: [] },
    Request: [Function: _Request] { props: [] },
    contentTypeParser: ContentTypeParser {
      customParsers: [Object],
      parserList: [Array],
      parserRegExpList: [],
      cache: [LRU],
      [Symbol(fastify.defaultJSONParse)]: [Function: defaultJsonParser]
    },
    onRequest: null,
    onSend: null,
    onError: null,
    onTimeout: null,
    preHandler: null,
    onResponse: null,
    config: { url: '/ping', method: 'GET' },
    errorHandler: [Function: defaultErrorHandler],
    _middie: null,
    _parserOptions: { limit: null },
    logLevel: '',
    logSerializers: undefined,
    attachValidation: false,
    schemaErrorFormatter: [Function: defaultSchemaErrorFormatter],
    preParsing: null,
    preValidation: null,
    preSerialization: null,
    [Symbol(fastify.404ContextKey)]: {
      schema: undefined,
      handler: [Function: basic404],
      Reply: [Function],
      Request: [Function],
      contentTypeParser: [ContentTypeParser],
      onRequest: null,
      onSend: null,
      onError: null,
      onTimeout: null,
      preHandler: null,
      onResponse: null,
      config: {},
      errorHandler: [Function: defaultErrorHandler],
      _middie: null,
      _parserOptions: [Object],
      logLevel: '',
      logSerializers: undefined,
      attachValidation: undefined,
      schemaErrorFormatter: [Function: defaultSchemaErrorFormatter],
      preParsing: null,
      preValidation: null,
      preSerialization: null,
      [Symbol(fastify.404ContextKey)]: null,
      [Symbol(fastify.replySerializerDefault)]: undefined
    },
    [Symbol(fastify.replySerializerDefault)]: null
  },
  params: {},
  raw: IncomingMessage {
    _readableState: ReadableState {
      objectMode: false,
      highWaterMark: 16384,
      buffer: BufferList { head: null, tail: null, length: 0 },
      length: 0,
      pipes: null,
      pipesCount: 0,
      flowing: null,
      ended: false,
      endEmitted: false,
      reading: false,
      sync: true,
      needReadable: false,
      emittedReadable: false,
      readableListening: false,
      resumeScheduled: false,
      emitClose: true,
      autoDestroy: false,
      destroyed: false,
      defaultEncoding: 'utf8',
      awaitDrain: 0,
      readingMore: true,
      decoder: null,
      encoding: null,
      [Symbol(kPaused)]: null
    },
    readable: true,
    _events: [Object: null prototype] {
      end: [Function: resetHeadersTimeoutOnReqEnd]
    },
    _eventsCount: 1,
    _maxListeners: undefined,
    socket: Socket {
      connecting: false,
      _hadError: false,
      _parent: null,
      _host: null,
      _readableState: [ReadableState],
      readable: true,
      _events: [Object: null prototype],
      _eventsCount: 8,
      _maxListeners: undefined,
      _writableState: [WritableState],
      writable: true,
      allowHalfOpen: true,
      _sockname: null,
      _pendingData: null,
      _pendingEncoding: '',
      server: [Server],
      _server: [Server],
      parser: [HTTPParser],
      on: [Function: socketListenerWrap],
      addListener: [Function: socketListenerWrap],
      prependListener: [Function: socketListenerWrap],
      _paused: false,
      _httpMessage: [ServerResponse],
      [Symbol(asyncId)]: 21,
      [Symbol(kHandle)]: [TCP],
      [Symbol(kSetNoDelay)]: false,
      [Symbol(lastWriteQueueSize)]: 0,
      [Symbol(timeout)]: null,
      [Symbol(kBuffer)]: null,
      [Symbol(kBufferCb)]: null,
      [Symbol(kBufferGen)]: null,
      [Symbol(kCapture)]: false,
      [Symbol(kBytesRead)]: 0,
      [Symbol(kBytesWritten)]: 0
    },
    connection: Socket {
      connecting: false,
      _hadError: false,
      _parent: null,
      _host: null,
      _readableState: [ReadableState],
      readable: true,
      _events: [Object: null prototype],
      _eventsCount: 8,
      _maxListeners: undefined,
      _writableState: [WritableState],
      writable: true,
      allowHalfOpen: true,
      _sockname: null,
      _pendingData: null,
      _pendingEncoding: '',
      server: [Server],
      _server: [Server],
      parser: [HTTPParser],
      on: [Function: socketListenerWrap],
      addListener: [Function: socketListenerWrap],
      prependListener: [Function: socketListenerWrap],
      _paused: false,
      _httpMessage: [ServerResponse],
      [Symbol(asyncId)]: 21,
      [Symbol(kHandle)]: [TCP],
      [Symbol(kSetNoDelay)]: false,
      [Symbol(lastWriteQueueSize)]: 0,
      [Symbol(timeout)]: null,
      [Symbol(kBuffer)]: null,
      [Symbol(kBufferCb)]: null,
      [Symbol(kBufferGen)]: null,
      [Symbol(kCapture)]: false,
      [Symbol(kBytesRead)]: 0,
      [Symbol(kBytesWritten)]: 0
    },
    httpVersionMajor: 1,
    httpVersionMinor: 1,
    httpVersion: '1.1',
    complete: false,
    headers: {
      host: '127.0.0.1:8080',
      connection: 'keep-alive',
      'cache-control': 'max-age=0',
      'sec-ch-ua': '"Google Chrome";v="95", "Chromium";v="95", ";Not A Brand";v="99"',
      'sec-ch-ua-mobile': '?0',
      'sec-ch-ua-platform': '"macOS"',
      'upgrade-insecure-requests': '1',
      'user-agent': 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/95.0.4638.54 Safari/537.36',
      accept: 'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9',
      'sec-fetch-site': 'none',
      'sec-fetch-mode': 'navigate',
      'sec-fetch-user': '?1',
      'sec-fetch-dest': 'document',
      'accept-encoding': 'gzip, deflate, br',
      'accept-language': 'ja,en-US;q=0.9,en;q=0.8',
      cookie: '_ga=GA1.1.574655998.1624823085; _kyp=QEkQBhnJos53+6AolbK6+OcGWFXoGYJcUMUEpVmoGnKW9tJ+PLhglxQxQuzAbQYBzRzpJ6boScIcRJFA__+eh+127.0.0.1%3A8081'
    },
    rawHeaders: [
      'Host',
      '127.0.0.1:8080',
      'Connection',
      'keep-alive',
      'Cache-Control',
      'max-age=0',
      'sec-ch-ua',
      '"Google Chrome";v="95", "Chromium";v="95", ";Not A Brand";v="99"',
      'sec-ch-ua-mobile',
      '?0',
      'sec-ch-ua-platform',
      '"macOS"',
      'Upgrade-Insecure-Requests',
      '1',
      'User-Agent',
      'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/95.0.4638.54 Safari/537.36',
      'Accept',
      'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9',
      'Sec-Fetch-Site',
      'none',
      'Sec-Fetch-Mode',
      'navigate',
      'Sec-Fetch-User',
      '?1',
      'Sec-Fetch-Dest',
      'document',
      'Accept-Encoding',
      'gzip, deflate, br',
      'Accept-Language',
      'ja,en-US;q=0.9,en;q=0.8',
      'Cookie',
      '_ga=GA1.1.574655998.1624823085; _kyp=QEkQBhnJos53+6AolbK6+OcGWFXoGYJcUMUEpVmoGnKW9tJ+PLhglxQxQuzAbQYBzRzpJ6boScIcRJFA__+eh+127.0.0.1%3A8081'
    ],
    trailers: {},
    rawTrailers: [],
    aborted: false,
    upgrade: false,
    url: '/ping',
    method: 'GET',
    statusCode: null,
    statusMessage: null,
    client: Socket {
      connecting: false,
      _hadError: false,
      _parent: null,
      _host: null,
      _readableState: [ReadableState],
      readable: true,
      _events: [Object: null prototype],
      _eventsCount: 8,
      _maxListeners: undefined,
      _writableState: [WritableState],
      writable: true,
      allowHalfOpen: true,
      _sockname: null,
      _pendingData: null,
      _pendingEncoding: '',
      server: [Server],
      _server: [Server],
      parser: [HTTPParser],
      on: [Function: socketListenerWrap],
      addListener: [Function: socketListenerWrap],
      prependListener: [Function: socketListenerWrap],
      _paused: false,
      _httpMessage: [ServerResponse],
      [Symbol(asyncId)]: 21,
      [Symbol(kHandle)]: [TCP],
      [Symbol(kSetNoDelay)]: false,
      [Symbol(lastWriteQueueSize)]: 0,
      [Symbol(timeout)]: null,
      [Symbol(kBuffer)]: null,
      [Symbol(kBufferCb)]: null,
      [Symbol(kBufferGen)]: null,
      [Symbol(kCapture)]: false,
      [Symbol(kBytesRead)]: 0,
      [Symbol(kBytesWritten)]: 0
    },
    _consuming: false,
    _dumped: false,
    [Symbol(kCapture)]: false
  },
  query: [Object: null prototype] {},
  log: { child: [Function], [Symbol(fastify.disableRequestLogging)]: false },
  body: null,
  [Symbol(fastify.RequestPayloadStream)]: IncomingMessage {
    _readableState: ReadableState {
      objectMode: false,
      highWaterMark: 16384,
      buffer: BufferList { head: null, tail: null, length: 0 },
      length: 0,
      pipes: null,
      pipesCount: 0,
      flowing: null,
      ended: false,
      endEmitted: false,
      reading: false,
      sync: true,
      needReadable: false,
      emittedReadable: false,
      readableListening: false,
      resumeScheduled: false,
      emitClose: true,
      autoDestroy: false,
      destroyed: false,
      defaultEncoding: 'utf8',
      awaitDrain: 0,
      readingMore: true,
      decoder: null,
      encoding: null,
      [Symbol(kPaused)]: null
    },
    readable: true,
    _events: [Object: null prototype] {
      end: [Function: resetHeadersTimeoutOnReqEnd]
    },
    _eventsCount: 1,
    _maxListeners: undefined,
    socket: Socket {
      connecting: false,
      _hadError: false,
      _parent: null,
      _host: null,
      _readableState: [ReadableState],
      readable: true,
      _events: [Object: null prototype],
      _eventsCount: 8,
      _maxListeners: undefined,
      _writableState: [WritableState],
      writable: true,
      allowHalfOpen: true,
      _sockname: null,
      _pendingData: null,
      _pendingEncoding: '',
      server: [Server],
      _server: [Server],
      parser: [HTTPParser],
      on: [Function: socketListenerWrap],
      addListener: [Function: socketListenerWrap],
      prependListener: [Function: socketListenerWrap],
      _paused: false,
      _httpMessage: [ServerResponse],
      [Symbol(asyncId)]: 21,
      [Symbol(kHandle)]: [TCP],
      [Symbol(kSetNoDelay)]: false,
      [Symbol(lastWriteQueueSize)]: 0,
      [Symbol(timeout)]: null,
      [Symbol(kBuffer)]: null,
      [Symbol(kBufferCb)]: null,
      [Symbol(kBufferGen)]: null,
      [Symbol(kCapture)]: false,
      [Symbol(kBytesRead)]: 0,
      [Symbol(kBytesWritten)]: 0
    },
    connection: Socket {
      connecting: false,
      _hadError: false,
      _parent: null,
      _host: null,
      _readableState: [ReadableState],
      readable: true,
      _events: [Object: null prototype],
      _eventsCount: 8,
      _maxListeners: undefined,
      _writableState: [WritableState],
      writable: true,
      allowHalfOpen: true,
      _sockname: null,
      _pendingData: null,
      _pendingEncoding: '',
      server: [Server],
      _server: [Server],
      parser: [HTTPParser],
      on: [Function: socketListenerWrap],
      addListener: [Function: socketListenerWrap],
      prependListener: [Function: socketListenerWrap],
      _paused: false,
      _httpMessage: [ServerResponse],
      [Symbol(asyncId)]: 21,
      [Symbol(kHandle)]: [TCP],
      [Symbol(kSetNoDelay)]: false,
      [Symbol(lastWriteQueueSize)]: 0,
      [Symbol(timeout)]: null,
      [Symbol(kBuffer)]: null,
      [Symbol(kBufferCb)]: null,
      [Symbol(kBufferGen)]: null,
      [Symbol(kCapture)]: false,
      [Symbol(kBytesRead)]: 0,
      [Symbol(kBytesWritten)]: 0
    },
    httpVersionMajor: 1,
    httpVersionMinor: 1,
    httpVersion: '1.1',
    complete: false,
    headers: {
      host: '127.0.0.1:8080',
      connection: 'keep-alive',
      'cache-control': 'max-age=0',
      'sec-ch-ua': '"Google Chrome";v="95", "Chromium";v="95", ";Not A Brand";v="99"',
      'sec-ch-ua-mobile': '?0',
      'sec-ch-ua-platform': '"macOS"',
      'upgrade-insecure-requests': '1',
      'user-agent': 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/95.0.4638.54 Safari/537.36',
      accept: 'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9',
      'sec-fetch-site': 'none',
      'sec-fetch-mode': 'navigate',
      'sec-fetch-user': '?1',
      'sec-fetch-dest': 'document',
      'accept-encoding': 'gzip, deflate, br',
      'accept-language': 'ja,en-US;q=0.9,en;q=0.8',
      cookie: '_ga=GA1.1.574655998.1624823085; _kyp=QEkQBhnJos53+6AolbK6+OcGWFXoGYJcUMUEpVmoGnKW9tJ+PLhglxQxQuzAbQYBzRzpJ6boScIcRJFA__+eh+127.0.0.1%3A8081'
    },
    rawHeaders: [
      'Host',
      '127.0.0.1:8080',
      'Connection',
      'keep-alive',
      'Cache-Control',
      'max-age=0',
      'sec-ch-ua',
      '"Google Chrome";v="95", "Chromium";v="95", ";Not A Brand";v="99"',
      'sec-ch-ua-mobile',
      '?0',
      'sec-ch-ua-platform',
      '"macOS"',
      'Upgrade-Insecure-Requests',
      '1',
      'User-Agent',
      'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/95.0.4638.54 Safari/537.36',
      'Accept',
      'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9',
      'Sec-Fetch-Site',
      'none',
      'Sec-Fetch-Mode',
      'navigate',
      'Sec-Fetch-User',
      '?1',
      'Sec-Fetch-Dest',
      'document',
      'Accept-Encoding',
      'gzip, deflate, br',
      'Accept-Language',
      'ja,en-US;q=0.9,en;q=0.8',
      'Cookie',
      '_ga=GA1.1.574655998.1624823085; _kyp=QEkQBhnJos53+6AolbK6+OcGWFXoGYJcUMUEpVmoGnKW9tJ+PLhglxQxQuzAbQYBzRzpJ6boScIcRJFA__+eh+127.0.0.1%3A8081'
    ],
    trailers: {},
    rawTrailers: [],
    aborted: false,
    upgrade: false,
    url: '/ping',
    method: 'GET',
    statusCode: null,
    statusMessage: null,
    client: Socket {
      connecting: false,
      _hadError: false,
      _parent: null,
      _host: null,
      _readableState: [ReadableState],
      readable: true,
      _events: [Object: null prototype],
      _eventsCount: 8,
      _maxListeners: undefined,
      _writableState: [WritableState],
      writable: true,
      allowHalfOpen: true,
      _sockname: null,
      _pendingData: null,
      _pendingEncoding: '',
      server: [Server],
      _server: [Server],
      parser: [HTTPParser],
      on: [Function: socketListenerWrap],
      addListener: [Function: socketListenerWrap],
      prependListener: [Function: socketListenerWrap],
      _paused: false,
      _httpMessage: [ServerResponse],
      [Symbol(asyncId)]: 21,
      [Symbol(kHandle)]: [TCP],
      [Symbol(kSetNoDelay)]: false,
      [Symbol(lastWriteQueueSize)]: 0,
      [Symbol(timeout)]: null,
      [Symbol(kBuffer)]: null,
      [Symbol(kBufferCb)]: null,
      [Symbol(kBufferGen)]: null,
      [Symbol(kCapture)]: false,
      [Symbol(kBytesRead)]: 0,
      [Symbol(kBytesWritten)]: 0
    },
    _consuming: false,
    _dumped: false,
    [Symbol(kCapture)]: false
  }
}
```

raw

```js
{
  _readableState: ReadableState {
    objectMode: false,
    highWaterMark: 16384,
    buffer: BufferList { head: null, tail: null, length: 0 },
    length: 0,
    pipes: null,
    pipesCount: 0,
    flowing: null,
    ended: false,
    endEmitted: false,
    reading: false,
    sync: true,
    needReadable: false,
    emittedReadable: false,
    readableListening: false,
    resumeScheduled: false,
    emitClose: true,
    autoDestroy: false,
    destroyed: false,
    defaultEncoding: 'utf8',
    awaitDrain: 0,
    readingMore: true,
    decoder: null,
    encoding: null,
    [Symbol(kPaused)]: null
  },
  readable: true,
  _events: [Object: null prototype] {
    end: [Function: resetHeadersTimeoutOnReqEnd]
  },
  _eventsCount: 1,
  _maxListeners: undefined,
  socket: Socket {
    connecting: false,
    _hadError: false,
    _parent: null,
    _host: null,
    _readableState: ReadableState {
      objectMode: false,
      highWaterMark: 16384,
      buffer: BufferList { head: null, tail: null, length: 0 },
      length: 0,
      pipes: null,
      pipesCount: 0,
      flowing: true,
      ended: false,
      endEmitted: false,
      reading: true,
      sync: false,
      needReadable: true,
      emittedReadable: false,
      readableListening: false,
      resumeScheduled: false,
      emitClose: false,
      autoDestroy: false,
      destroyed: false,
      defaultEncoding: 'utf8',
      awaitDrain: 0,
      readingMore: false,
      decoder: null,
      encoding: null,
      [Symbol(kPaused)]: false
    },
    readable: true,
    _events: [Object: null prototype] {
      end: [Array],
      timeout: [Function: socketOnTimeout],
      data: [Function: bound socketOnData],
      error: [Function: socketOnError],
      close: [Array],
      drain: [Function: bound socketOnDrain],
      resume: [Function: onSocketResume],
      pause: [Function: onSocketPause]
    },
    _eventsCount: 8,
    _maxListeners: undefined,
    _writableState: WritableState {
      objectMode: false,
      highWaterMark: 16384,
      finalCalled: false,
      needDrain: false,
      ending: false,
      ended: false,
      finished: false,
      destroyed: false,
      decodeStrings: false,
      defaultEncoding: 'utf8',
      length: 0,
      writing: false,
      corked: 0,
      sync: true,
      bufferProcessing: false,
      onwrite: [Function: bound onwrite],
      writecb: null,
      writelen: 0,
      afterWriteTickInfo: null,
      bufferedRequest: null,
      lastBufferedRequest: null,
      pendingcb: 0,
      prefinished: false,
      errorEmitted: false,
      emitClose: false,
      autoDestroy: false,
      bufferedRequestCount: 0,
      corkedRequestsFree: [Object]
    },
    writable: true,
    allowHalfOpen: true,
    _sockname: null,
    _pendingData: null,
    _pendingEncoding: '',
    server: Server {
      insecureHTTPParser: undefined,
      _events: [Object: null prototype],
      _eventsCount: 3,
      _maxListeners: undefined,
      _connections: 2,
      _handle: [TCP],
      _usingWorkers: false,
      _workers: [],
      _unref: false,
      allowHalfOpen: true,
      pauseOnConnect: false,
      httpAllowHalfOpen: false,
      timeout: 0,
      keepAliveTimeout: 5000,
      maxHeadersCount: null,
      headersTimeout: 40000,
      _connectionKey: '4:127.0.0.1:8080',
      [Symbol(IncomingMessage)]: [Function: IncomingMessage],
      [Symbol(ServerResponse)]: [Function: ServerResponse],
      [Symbol(kCapture)]: false,
      [Symbol(asyncId)]: 18
    },
    _server: Server {
      insecureHTTPParser: undefined,
      _events: [Object: null prototype],
      _eventsCount: 3,
      _maxListeners: undefined,
      _connections: 2,
      _handle: [TCP],
      _usingWorkers: false,
      _workers: [],
      _unref: false,
      allowHalfOpen: true,
      pauseOnConnect: false,
      httpAllowHalfOpen: false,
      timeout: 0,
      keepAliveTimeout: 5000,
      maxHeadersCount: null,
      headersTimeout: 40000,
      _connectionKey: '4:127.0.0.1:8080',
      [Symbol(IncomingMessage)]: [Function: IncomingMessage],
      [Symbol(ServerResponse)]: [Function: ServerResponse],
      [Symbol(kCapture)]: false,
      [Symbol(asyncId)]: 18
    },
    parser: HTTPParser {
      '0': [Function: parserOnHeaders],
      '1': [Function: parserOnHeadersComplete],
      '2': [Function: parserOnBody],
      '3': [Function: parserOnMessageComplete],
      '4': [Function: bound onParserExecute],
      _headers: [],
      _url: '',
      socket: [Circular],
      incoming: [Circular],
      outgoing: null,
      maxHeaderPairs: 2000,
      _consumed: true,
      onIncoming: [Function: bound parserOnIncoming],
      parsingHeadersStart: 0
    },
    on: [Function: socketListenerWrap],
    addListener: [Function: socketListenerWrap],
    prependListener: [Function: socketListenerWrap],
    _paused: false,
    _httpMessage: ServerResponse {
      _events: [Object: null prototype],
      _eventsCount: 1,
      _maxListeners: undefined,
      outputData: [],
      outputSize: 0,
      writable: true,
      _last: false,
      chunkedEncoding: false,
      shouldKeepAlive: true,
      useChunkedEncodingByDefault: true,
      sendDate: true,
      _removedConnection: false,
      _removedContLen: false,
      _removedTE: false,
      _contentLength: null,
      _hasBody: true,
      _trailer: '',
      finished: false,
      _headerSent: false,
      socket: [Circular],
      connection: [Circular],
      _header: null,
      _onPendingData: [Function: bound updateOutgoingData],
      _sent100: false,
      _expect_continue: false,
      [Symbol(kCapture)]: false,
      [Symbol(kNeedDrain)]: false,
      [Symbol(corked)]: 0,
      [Symbol(kOutHeaders)]: null
    },
    [Symbol(asyncId)]: 21,
    [Symbol(kHandle)]: TCP {
      reading: true,
      onconnection: null,
      _consumed: true,
      [Symbol(owner)]: [Circular]
    },
    [Symbol(kSetNoDelay)]: false,
    [Symbol(lastWriteQueueSize)]: 0,
    [Symbol(timeout)]: null,
    [Symbol(kBuffer)]: null,
    [Symbol(kBufferCb)]: null,
    [Symbol(kBufferGen)]: null,
    [Symbol(kCapture)]: false,
    [Symbol(kBytesRead)]: 0,
    [Symbol(kBytesWritten)]: 0
  },
  connection: Socket {
    connecting: false,
    _hadError: false,
    _parent: null,
    _host: null,
    _readableState: ReadableState {
      objectMode: false,
      highWaterMark: 16384,
      buffer: BufferList { head: null, tail: null, length: 0 },
      length: 0,
      pipes: null,
      pipesCount: 0,
      flowing: true,
      ended: false,
      endEmitted: false,
      reading: true,
      sync: false,
      needReadable: true,
      emittedReadable: false,
      readableListening: false,
      resumeScheduled: false,
      emitClose: false,
      autoDestroy: false,
      destroyed: false,
      defaultEncoding: 'utf8',
      awaitDrain: 0,
      readingMore: false,
      decoder: null,
      encoding: null,
      [Symbol(kPaused)]: false
    },
    readable: true,
    _events: [Object: null prototype] {
      end: [Array],
      timeout: [Function: socketOnTimeout],
      data: [Function: bound socketOnData],
      error: [Function: socketOnError],
      close: [Array],
      drain: [Function: bound socketOnDrain],
      resume: [Function: onSocketResume],
      pause: [Function: onSocketPause]
    },
    _eventsCount: 8,
    _maxListeners: undefined,
    _writableState: WritableState {
      objectMode: false,
      highWaterMark: 16384,
      finalCalled: false,
      needDrain: false,
      ending: false,
      ended: false,
      finished: false,
      destroyed: false,
      decodeStrings: false,
      defaultEncoding: 'utf8',
      length: 0,
      writing: false,
      corked: 0,
      sync: true,
      bufferProcessing: false,
      onwrite: [Function: bound onwrite],
      writecb: null,
      writelen: 0,
      afterWriteTickInfo: null,
      bufferedRequest: null,
      lastBufferedRequest: null,
      pendingcb: 0,
      prefinished: false,
      errorEmitted: false,
      emitClose: false,
      autoDestroy: false,
      bufferedRequestCount: 0,
      corkedRequestsFree: [Object]
    },
    writable: true,
    allowHalfOpen: true,
    _sockname: null,
    _pendingData: null,
    _pendingEncoding: '',
    server: Server {
      insecureHTTPParser: undefined,
      _events: [Object: null prototype],
      _eventsCount: 3,
      _maxListeners: undefined,
      _connections: 2,
      _handle: [TCP],
      _usingWorkers: false,
      _workers: [],
      _unref: false,
      allowHalfOpen: true,
      pauseOnConnect: false,
      httpAllowHalfOpen: false,
      timeout: 0,
      keepAliveTimeout: 5000,
      maxHeadersCount: null,
      headersTimeout: 40000,
      _connectionKey: '4:127.0.0.1:8080',
      [Symbol(IncomingMessage)]: [Function: IncomingMessage],
      [Symbol(ServerResponse)]: [Function: ServerResponse],
      [Symbol(kCapture)]: false,
      [Symbol(asyncId)]: 18
    },
    _server: Server {
      insecureHTTPParser: undefined,
      _events: [Object: null prototype],
      _eventsCount: 3,
      _maxListeners: undefined,
      _connections: 2,
      _handle: [TCP],
      _usingWorkers: false,
      _workers: [],
      _unref: false,
      allowHalfOpen: true,
      pauseOnConnect: false,
      httpAllowHalfOpen: false,
      timeout: 0,
      keepAliveTimeout: 5000,
      maxHeadersCount: null,
      headersTimeout: 40000,
      _connectionKey: '4:127.0.0.1:8080',
      [Symbol(IncomingMessage)]: [Function: IncomingMessage],
      [Symbol(ServerResponse)]: [Function: ServerResponse],
      [Symbol(kCapture)]: false,
      [Symbol(asyncId)]: 18
    },
    parser: HTTPParser {
      '0': [Function: parserOnHeaders],
      '1': [Function: parserOnHeadersComplete],
      '2': [Function: parserOnBody],
      '3': [Function: parserOnMessageComplete],
      '4': [Function: bound onParserExecute],
      _headers: [],
      _url: '',
      socket: [Circular],
      incoming: [Circular],
      outgoing: null,
      maxHeaderPairs: 2000,
      _consumed: true,
      onIncoming: [Function: bound parserOnIncoming],
      parsingHeadersStart: 0
    },
    on: [Function: socketListenerWrap],
    addListener: [Function: socketListenerWrap],
    prependListener: [Function: socketListenerWrap],
    _paused: false,
    _httpMessage: ServerResponse {
      _events: [Object: null prototype],
      _eventsCount: 1,
      _maxListeners: undefined,
      outputData: [],
      outputSize: 0,
      writable: true,
      _last: false,
      chunkedEncoding: false,
      shouldKeepAlive: true,
      useChunkedEncodingByDefault: true,
      sendDate: true,
      _removedConnection: false,
      _removedContLen: false,
      _removedTE: false,
      _contentLength: null,
      _hasBody: true,
      _trailer: '',
      finished: false,
      _headerSent: false,
      socket: [Circular],
      connection: [Circular],
      _header: null,
      _onPendingData: [Function: bound updateOutgoingData],
      _sent100: false,
      _expect_continue: false,
      [Symbol(kCapture)]: false,
      [Symbol(kNeedDrain)]: false,
      [Symbol(corked)]: 0,
      [Symbol(kOutHeaders)]: null
    },
    [Symbol(asyncId)]: 21,
    [Symbol(kHandle)]: TCP {
      reading: true,
      onconnection: null,
      _consumed: true,
      [Symbol(owner)]: [Circular]
    },
    [Symbol(kSetNoDelay)]: false,
    [Symbol(lastWriteQueueSize)]: 0,
    [Symbol(timeout)]: null,
    [Symbol(kBuffer)]: null,
    [Symbol(kBufferCb)]: null,
    [Symbol(kBufferGen)]: null,
    [Symbol(kCapture)]: false,
    [Symbol(kBytesRead)]: 0,
    [Symbol(kBytesWritten)]: 0
  },
  httpVersionMajor: 1,
  httpVersionMinor: 1,
  httpVersion: '1.1',
  complete: false,
  headers: {
    host: '127.0.0.1:8080',
    connection: 'keep-alive',
    'cache-control': 'max-age=0',
    'sec-ch-ua': '"Google Chrome";v="95", "Chromium";v="95", ";Not A Brand";v="99"',
    'sec-ch-ua-mobile': '?0',
    'sec-ch-ua-platform': '"macOS"',
    'upgrade-insecure-requests': '1',
    'user-agent': 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/95.0.4638.54 Safari/537.36',
    accept: 'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9',
    'sec-fetch-site': 'none',
    'sec-fetch-mode': 'navigate',
    'sec-fetch-user': '?1',
    'sec-fetch-dest': 'document',
    'accept-encoding': 'gzip, deflate, br',
    'accept-language': 'ja,en-US;q=0.9,en;q=0.8',
    cookie: '_ga=GA1.1.574655998.1624823085; _kyp=QEkQBhnJos53+6AolbK6+OcGWFXoGYJcUMUEpVmoGnKW9tJ+PLhglxQxQuzAbQYBzRzpJ6boScIcRJFA__+eh+127.0.0.1%3A8081'
  },
  rawHeaders: [
    'Host',
    '127.0.0.1:8080',
    'Connection',
    'keep-alive',
    'Cache-Control',
    'max-age=0',
    'sec-ch-ua',
    '"Google Chrome";v="95", "Chromium";v="95", ";Not A Brand";v="99"',
    'sec-ch-ua-mobile',
    '?0',
    'sec-ch-ua-platform',
    '"macOS"',
    'Upgrade-Insecure-Requests',
    '1',
    'User-Agent',
    'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/95.0.4638.54 Safari/537.36',
    'Accept',
    'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9',
    'Sec-Fetch-Site',
    'none',
    'Sec-Fetch-Mode',
    'navigate',
    'Sec-Fetch-User',
    '?1',
    'Sec-Fetch-Dest',
    'document',
    'Accept-Encoding',
    'gzip, deflate, br',
    'Accept-Language',
    'ja,en-US;q=0.9,en;q=0.8',
    'Cookie',
    '_ga=GA1.1.574655998.1624823085; _kyp=QEkQBhnJos53+6AolbK6+OcGWFXoGYJcUMUEpVmoGnKW9tJ+PLhglxQxQuzAbQYBzRzpJ6boScIcRJFA__+eh+127.0.0.1%3A8081'
  ],
  trailers: {},
  rawTrailers: [],
  aborted: false,
  upgrade: false,
  url: '/ping',
  method: 'GET',
  statusCode: null,
  statusMessage: null,
  client: Socket {
    connecting: false,
    _hadError: false,
    _parent: null,
    _host: null,
    _readableState: ReadableState {
      objectMode: false,
      highWaterMark: 16384,
      buffer: BufferList { head: null, tail: null, length: 0 },
      length: 0,
      pipes: null,
      pipesCount: 0,
      flowing: true,
      ended: false,
      endEmitted: false,
      reading: true,
      sync: false,
      needReadable: true,
      emittedReadable: false,
      readableListening: false,
      resumeScheduled: false,
      emitClose: false,
      autoDestroy: false,
      destroyed: false,
      defaultEncoding: 'utf8',
      awaitDrain: 0,
      readingMore: false,
      decoder: null,
      encoding: null,
      [Symbol(kPaused)]: false
    },
    readable: true,
    _events: [Object: null prototype] {
      end: [Array],
      timeout: [Function: socketOnTimeout],
      data: [Function: bound socketOnData],
      error: [Function: socketOnError],
      close: [Array],
      drain: [Function: bound socketOnDrain],
      resume: [Function: onSocketResume],
      pause: [Function: onSocketPause]
    },
    _eventsCount: 8,
    _maxListeners: undefined,
    _writableState: WritableState {
      objectMode: false,
      highWaterMark: 16384,
      finalCalled: false,
      needDrain: false,
      ending: false,
      ended: false,
      finished: false,
      destroyed: false,
      decodeStrings: false,
      defaultEncoding: 'utf8',
      length: 0,
      writing: false,
      corked: 0,
      sync: true,
      bufferProcessing: false,
      onwrite: [Function: bound onwrite],
      writecb: null,
      writelen: 0,
      afterWriteTickInfo: null,
      bufferedRequest: null,
      lastBufferedRequest: null,
      pendingcb: 0,
      prefinished: false,
      errorEmitted: false,
      emitClose: false,
      autoDestroy: false,
      bufferedRequestCount: 0,
      corkedRequestsFree: [Object]
    },
    writable: true,
    allowHalfOpen: true,
    _sockname: null,
    _pendingData: null,
    _pendingEncoding: '',
    server: Server {
      insecureHTTPParser: undefined,
      _events: [Object: null prototype],
      _eventsCount: 3,
      _maxListeners: undefined,
      _connections: 2,
      _handle: [TCP],
      _usingWorkers: false,
      _workers: [],
      _unref: false,
      allowHalfOpen: true,
      pauseOnConnect: false,
      httpAllowHalfOpen: false,
      timeout: 0,
      keepAliveTimeout: 5000,
      maxHeadersCount: null,
      headersTimeout: 40000,
      _connectionKey: '4:127.0.0.1:8080',
      [Symbol(IncomingMessage)]: [Function: IncomingMessage],
      [Symbol(ServerResponse)]: [Function: ServerResponse],
      [Symbol(kCapture)]: false,
      [Symbol(asyncId)]: 18
    },
    _server: Server {
      insecureHTTPParser: undefined,
      _events: [Object: null prototype],
      _eventsCount: 3,
      _maxListeners: undefined,
      _connections: 2,
      _handle: [TCP],
      _usingWorkers: false,
      _workers: [],
      _unref: false,
      allowHalfOpen: true,
      pauseOnConnect: false,
      httpAllowHalfOpen: false,
      timeout: 0,
      keepAliveTimeout: 5000,
      maxHeadersCount: null,
      headersTimeout: 40000,
      _connectionKey: '4:127.0.0.1:8080',
      [Symbol(IncomingMessage)]: [Function: IncomingMessage],
      [Symbol(ServerResponse)]: [Function: ServerResponse],
      [Symbol(kCapture)]: false,
      [Symbol(asyncId)]: 18
    },
    parser: HTTPParser {
      '0': [Function: parserOnHeaders],
      '1': [Function: parserOnHeadersComplete],
      '2': [Function: parserOnBody],
      '3': [Function: parserOnMessageComplete],
      '4': [Function: bound onParserExecute],
      _headers: [],
      _url: '',
      socket: [Circular],
      incoming: [Circular],
      outgoing: null,
      maxHeaderPairs: 2000,
      _consumed: true,
      onIncoming: [Function: bound parserOnIncoming],
      parsingHeadersStart: 0
    },
    on: [Function: socketListenerWrap],
    addListener: [Function: socketListenerWrap],
    prependListener: [Function: socketListenerWrap],
    _paused: false,
    _httpMessage: ServerResponse {
      _events: [Object: null prototype],
      _eventsCount: 1,
      _maxListeners: undefined,
      outputData: [],
      outputSize: 0,
      writable: true,
      _last: false,
      chunkedEncoding: false,
      shouldKeepAlive: true,
      useChunkedEncodingByDefault: true,
      sendDate: true,
      _removedConnection: false,
      _removedContLen: false,
      _removedTE: false,
      _contentLength: null,
      _hasBody: true,
      _trailer: '',
      finished: false,
      _headerSent: false,
      socket: [Circular],
      connection: [Circular],
      _header: null,
      _onPendingData: [Function: bound updateOutgoingData],
      _sent100: false,
      _expect_continue: false,
      [Symbol(kCapture)]: false,
      [Symbol(kNeedDrain)]: false,
      [Symbol(corked)]: 0,
      [Symbol(kOutHeaders)]: null
    },
    [Symbol(asyncId)]: 21,
    [Symbol(kHandle)]: TCP {
      reading: true,
      onconnection: null,
      _consumed: true,
      [Symbol(owner)]: [Circular]
    },
    [Symbol(kSetNoDelay)]: false,
    [Symbol(lastWriteQueueSize)]: 0,
    [Symbol(timeout)]: null,
    [Symbol(kBuffer)]: null,
    [Symbol(kBufferCb)]: null,
    [Symbol(kBufferGen)]: null,
    [Symbol(kCapture)]: false,
    [Symbol(kBytesRead)]: 0,
    [Symbol(kBytesWritten)]: 0
  },
  _consuming: false,
  _dumped: false,
  [Symbol(kCapture)]: false
}
```
