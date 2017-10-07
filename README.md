# Node.js-Interview-Questions
Candidates or Interviewer can submit questions they were asked or would like their candidates to know and probable answers to them

1. How is Node.js different different from Javascript?

Ans: Node.js uses a library called [libuv](https://github.com/libuv/libuv), to bring an asynchronous event driven model to Javscript. It piggy backs on Chrome's Javascript Engine called V8 to enable the use of Javascript language.

2. Name 3 ways to manage events in an asynchronous way

Ans: First, a classic use of callback methods. Second, using Promises. Finally, in a more sophisticated way, we can use reactive extensions (RxJS) to define pipelines the manage events asynchronously
