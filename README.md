# Node.js-Interview-Questions
Candidates or Interviewer can submit questions they were asked or would like their candidates to know and probable answers to them

1. How is Node.js different different from Javascript?
2. What is “callback hell” and how can it be avoided?
3. When Should We Use Node.Js?
4. What are Promises?
5. What is the difference between Node.js vs Ajax?
6. Is Node.js really Single-Threaded?
7. Can you explain what is Globals in Node.js?
8. What is the Use of underscore in Node.js?
9. What is Event Loop and Event Emitter?
10. Why to use Buffers instead of binary strings to handle binary data ?

[Answers](https://blog.risingstack.com/node-js-interview-questions/)

Ans: Node.js uses a library called [libuv](https://github.com/libuv/libuv), to bring an asynchronous event driven model to Javscript. It piggy backs on Chrome's Javascript Engine called V8 to enable the use of Javascript language.

2. Name 3 ways to manage events in an asynchronous way

Ans: First, a classic use of callback methods. Second, using Promises. Finally, in a more sophisticated way, we can use reactive extensions (RxJS) to define pipelines the manage events asynchronously
