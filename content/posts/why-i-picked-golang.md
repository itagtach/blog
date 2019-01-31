+++
title = "Why I Picked Go"
featuredImage = "img/golang.png"
displayInMenu = false
displayInList = true
draft = false
tags = [
    "go",
    "golang",
    "development",
    "programming",
]
date = "2019-01-30"
categories = [
    "Development",
    "golang",
]
+++

Every language has pros and cons. While I won’t say that a certain language is bad, there are certainly ones that suit me and ones that don’t. Recently, I decided to pick golang and I've been really enjoying the language and the process of learning it.


The main reason I picked golang was because I wanted to learn a language that was optimized for the web. I also wanted something fast and that would allow me to build programs for the backend. Some of my deciding criteria included:

<ul>
  <li>Is it fast?</li>
  <li>Is it good for web development?</li>
  <li>Is it built for concurrency?</li>
  <li>Does it offer good support for functional programming?</li>
  <li>Does it have a good community?</li>
</ul>

The first language I considered was Rust. Here are some of my initial conclusions about Rust: 
<ul>
<li>Rust is extremely fast, though a touch slower than C</li>
<li>Not great for web due to immaturity of the language</li>
<li>Very good for concurrency</li>
<li>Complete support for functional programming</li>
<li>Nice and helpful community, but very small</li>
</ul>

While researching Rust, I realized that though the ownership model is powerful, the community is still fairly small. This means that the tooling and ecosystem around Rust is still immature. While I remain excited about the prspects that Rust offers, I am not ready to invest in Rust just yet.

This conclusion then led me to look in the direction of Go. Another incredibly popular language for building backend web applications. My first impressions of Go were pretty positive. Here are a couple of them: 

* Very fast, but a little slower than Rust
* Great for the web
* Concurrency is one of the major focuses of the language
* Incomplete functional programming support
* Large community

My only hang up with Go is that it lacks full support for functional programming. Though Go does treat functions as first class citizens, it does not have immutable values. For instance, Go does not have an equivalent to `Final` in Java or `val` in Scala.

### Java
```
Final int variable = 5
```

### Scala 
```
val variable = 5
```

It is also missing a few other tools like pattern matching, which are very useful, but not necessary. 

I despaired a bit regarding the lack of immutable data, until I learned that Go is a pass by value language. This means that when parameters are passed into functions they are copies of the original data, not pointers to memory. (_More on this in future posts!_)

In summary, I am very happy with Go and look forward to deepening my knowledge.

