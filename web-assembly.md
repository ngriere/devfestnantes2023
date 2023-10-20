# ☁️ WebAssembly beyond the browser 
> 19/10 at 10 AM - Mete ATAMEL / Google UK

![Cloud & DevOps](https://img.shields.io/badge/Cloud%20&%20DevOps-orange)

## 1. Intro

**WebAssembly (WASM)** allows you to compile code written in over 40 programming languages and run it in a secure and performant way in web browsers. The **WebAssembly System Interface (WASI)** has expanded the capabilities of WASM by enabling it to run outside the web browser, such as server-side applications, edge computing, and cloud microservices. Docker has also recently announced support for Wasm, allowing it to be used as a lightweight alternative to Linux and Windows containers.

Whether WASM will replace containers remains to be seen but it’s definitely worth learning more about it. In this talk, I’ll introduce Wasm, the basic terminology around it, and its current state as a server side technology. We will also look at some examples and tools for working with Wasm on the server side.


## 2. What is WebAssembly ?
Portable compilation target

Originally focusing on augmenting JavaScript in the browser

Advantages:
- Faster (no cold start)
- Smaller (3-20 Times smaller than native Rust container)
More secure (WASM apps execute in everything is deny by default sandbox)
- More portable
- Different use cases (browser, cloud microservices, IOT, Plugins)

## 3. Why run WASM inside a container ?
We are in a state where the ecosystem isn't mature enough
> Combining the current world with thé future world

In future, it won't be necessary

## 4. Demo: running WASM in docker
Scratch image &rarr; no need to add additionnal dependencies because wasm is enabled in docker &rarr; use of a WASI runtime

### Docker native images vs. Docker wasm
&rarr; native images much smaller in size

### Web Assembly Gateway Interface (WASI)
Different routes with WASM builds compiled in different languages.

`/go` &rarr; WASM build 1

`/csharp` &rarr; WASM build 2

### WASIX
Extends WASM with POSIX
Adoption blocked because very hard to know what is supported and what is not

### 5. Conclusion
**WASM** and **WASI** are interesting technologies to learn about. 
Today, there seem to be at a shifting point.
It could have the potential to replace docker in future as the future of containers.


|  Technology  |  Timeline  |
|----|----|
|  Containers |  now  |
|  WebAssembly  | future ?   |

## 6. Resources 
[Presentation Link](speakerdeck.com/meteatamel)

Google cloud innovators for free credits
