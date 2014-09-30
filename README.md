Angular http-client-factory module
==================================

**Note**: this is only proof-of-concept. I recommend not to use it in production (but who will listen anyway?).

Want separate `$http` service for different endpoints with it's own interceptors and default headers? You have it!

Angular is great. And it's `$http` service is great. Interceptors are very powerfull concept... in case that you're dealing with just single api. But what if your app uses several api services, each should have it's own headers, some of them requires some special interceptors (401 error handlers, [rate-limit apis](http://stackoverflow.com/questions/12154215/efficiently-using-a-rate-limited-api-echo-nest-with-distributed-clients) and many more) which is not needed for another endpoints. `$httpProvider` can't disable some interceptors per-request, and you start to add some config-checking in your interceptor.

But how about to get some configurable sulution built on-top of `$http` service, which have the same API and gives you ability to specify multiple instances of it for each endpoint.

## Installing
Not available for now. Very soon it will be available as bower package.

## Configuration
Nope, configuration examples is also not available for now. Sorry. Please stay in touch!