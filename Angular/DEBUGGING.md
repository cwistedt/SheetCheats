# Logging
Log angular error on production.
Its a chalange since js is minified and uglyfied. Must use sourcemap do descifer.

Angular Using Stacktrace and 
* source-map-clie
* Source-map-cli
* https://www.npmjs.com/package/source-map-cli
* https://medium.com/taskworld-tech/tracking-down-an-error-from-a-minified-production-stack-trace-7a7c7b812d55
* Alternative use source-map-toolkit made in c#
* https://github.com/Microsoft/sourcemap-toolkit
* Stacktrace.js
* http://www.stacktracejs.com/#!/docs/stacktrace-js
* https://www.mattzeunert.com/2016/07/07/resolving-minified-production-stacktrace.html
* https://medium.com/@amcdnl/global-error-handling-with-angular2-6b992bdfb59c
* Must output hidden sourcemap
* Have changed in webpack.prod
* Have changed starupt.cs must be a problem in vscode becaus can not turn of HotWebPack