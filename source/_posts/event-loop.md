---
title: evnt loop
date: 2022-11-01 10:52:27
tags:
 - JS
---

# JavaScript Event Loop

## Browser Engine Processes

A browser engine consists of several different processes, including the rendering main thread where JavaScript code run.

## JavaScript Engine Time Loop

The JavaScript engine uses an event loop to handle asynchronous operations. The event loop is a constantly running process that monitors both the callback queue and the call stack. When the call stack is empty, the event loop checks the callback queue for any pending tasks and executes them in order.

### V8 Engine Queues

The V8 engine has several different queues that it uses to manage asynchronous tasks. For example, the microtask queue is always executed first, followed by other task queues with different priorities. 

## Inaccuracy of JavaScript Timers

JavaScript timers are not always accurate because they are dependent on the browser's rendering performance and other factors such as system load and network latency.
