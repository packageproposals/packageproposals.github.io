---
layout: post
title: Volley  Vs  Retrofit  which one is the best ?.
date: 2021-04-08
summary: |
 Between Volley and retrofit, which one is the better library for http requests.
tags: java android spring
categories:
  - java
  - android
  - spring
---
**Volley  Vs  Retrofit  which one is the best.**

Java developers this topic has been highly debated ,however today iam going to give you a clear and concise comparison that you can base on to make a decision to use one of the libraries for your next project.

**VOLLEY.* * ([GitHub](https://github.com/google/volley).)

This library originally developed by google is a light weight http library for java projects.

usage

```groovy
dependencies {
    ...
    implementation 'com.android.volley:volley:1.2.0'
}
```

**Pros  of  Volley.**

-Light weight
-String request
- Automatic scheduling of network requests.
- Multiple concurrent network connections.
- Transparent disk and memory response caching with standard HTTP [cache coherence](https://en.wikipedia.org/wiki/Cache_coherence).
- Support for request prioritization.
- Cancellation request API. You can cancel a single request, or you can set blocks or scopes of requests to cancel.
- Ease of customization, for example, for retry and backoff.
- Strong ordering that makes it easy to correctly populate your UI with data fetched asynchronously from the network.
- Debugging and tracing tools.

**Cons.**

One data type

Volley is not suitable for large projects which involve streaming operations

**Retrofit** ([Github](https://github.com/square/retrofit))

It is an open source http library from square that takes the pain out of making http requests, **HTTP client** for Android and Java

usage

// below is how you include the retrofit library in your project

``` com.squareup.retrofit2:retrofit:2.1.0' implementation 'com.squareup.retrofit2:converter-gson:2.1.0'```

**Pros**

Interceptors

Converters

Multiple data types on requests.

Conclusion

From the above comparison it is clear that the last decision remains to you although retrofit has a slight edge over volley.



.
