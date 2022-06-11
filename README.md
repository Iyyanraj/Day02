1. Write a blog on Difference between HTTP1.1 vs HTTP2
Answer:HTTP2 is much faster and more reliable than HTTP1. 
HTTP1 loads a single request for every TCP connection, while HTTP2 avoids network delay by using multiplexing. HTTP is a network delay sensitive protocol in the sense that if there is less network delay, then the page loads faster. 
HTTP/1.1: works on the textual format.HTTP/2: It works on the binary protocol.
HTTP/1.1: There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources. HTTP/2: It allows multiplexing so one TCP connection is required for multiple requests.
HTTP/1.1: It uses requests resource Inlining for use getting multiple pages. HTTP/2: It uses PUSH frame by server that collects all multiple pages.
HTTP/1.1: It compresses data by itself. HTTP/2: It uses HPACK for data compression.

2. Write a blog about objects and its internal representation in Javascript
Answer: Objects And Its Internal Representation In JavaScript
Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).

Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.
An object, is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.

Loosely speaking, objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.

For Eg. If your object is a student, it will have properties like name, age, address, id, etc and methods like updateAddress, updateNam, etc.
