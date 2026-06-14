# Awesome WebAssembly [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Collection of awesome things regarding the WebAssembly ecosystem.

## Contents

- [General Resources](#general-resources)
- [WebAssembly 3.0 & Beyond](#webassembly-30--beyond)
- [Getting Started](#getting-started)
  - [Online Playgrounds](#online-playgrounds)
  - [Tutorials](#tutorials)
  - [Books](#books)
- [The Component Model & WASI](#the-component-model--wasi)
- [Languages & Compilers](#languages--compilers)
- [Runtimes & Standalone](#runtimes--standalone)
  - [Desktop & Server Runtimes](#desktop--server-runtimes)
  - [Embedded & IoT Runtimes](#embedded--iot-runtimes)
  - [Cloud Native & Serverless](#cloud-native--serverless)
- [Libraries & Frameworks](#libraries--frameworks)
  - [Web UI Frameworks](#web-ui-frameworks)
  - [AI & Machine Learning](#ai--machine-learning)
  - [Data Processing](#data-processing)
  - [Graphics & WebGL](#graphics--webgl)
- [Tools & Toolkits](#tools--toolkits)
- [Learning & Ecosystem](#learning--ecosystem)
  - [Articles](#articles)
  - [Video](#video)
  - [Slides](#slides)
  - [Community](#community)
- [Scientific & Academic](#scientific--academic)
- [Showcase](#showcase)
  - [Examples](#examples)
  - [Demos](#demos)
  - [Benchmarks](#benchmarks)
- [Resources in other languages](#resources-in-other-languages)
- [License](#license)

## General Resources
- [Official Site](http://webassembly.org/)
- [GitHub](https://github.com/webassembly)
- [WebAssembly MDN](https://developer.mozilla.org/en-US/docs/WebAssembly)
- [WebAssembly Wikipedia](https://en.wikipedia.org/wiki/WebAssembly)
- [WebAssembly Specification](https://webassembly.github.io/spec/)

## WebAssembly 3.0 & Beyond
*Standardized features and future roadmap.*
- [WasmGC](https://github.com/WebAssembly/gc) - High-level language support with native garbage collection.
- [Memory64](https://github.com/WebAssembly/memory64) - Support for 64-bit memory addressing (>4GB).
- [Exception Handling](https://github.com/WebAssembly/exception-handling) - First-class support for exceptions.
- [Relaxed SIMD](https://github.com/WebAssembly/relaxed-simd) - Hardware-optimized vector operations.
- [JS String Builtins](https://github.com/WebAssembly/js-string-builtins) - Efficient string passing between Wasm and JavaScript.

## Getting Started

### Online Playgrounds
- [WebAssembly Explorer](https://mbebenita.github.io/WasmExplorer/)
- [Assembleash - WebAssembly and TypeScript-like languages playground](https://github.com/MaxGraey/Assembleash)
- [Wat2Wasm](https://cdn.rawgit.com/WebAssembly/wabt/fb986fbd/demo/wat2wasm/)
- [Wasm2Wat](https://cdn.rawgit.com/WebAssembly/wabt/fb986fbd/demo/wasm2wat/)

### Tutorials
- [Wasmbyexample - Hands-On Introduction Examples and Tutorials for WebAssembly](https://wasmbyexample.dev/)
- [Developer's Guide](http://webassembly.org/getting-started/developers-guide/)
- [Introduction to WebAssembly Text (2021)](https://awesome.red-badger.com/chriswhealy/introduction-to-web-assembly-text)
- [Hands-On WebAssembly: Try the Basics (2020)](https://evilmartians.com/chronicles/hands-on-webassembly-try-the-basics)
- [First steps with WebAssembly in Rust (2020)](https://aralroca.com/blog/first-steps-webassembly-rust)
- [Using the import statement with an Emscripten-generated module in Vue.js (2020)](https://cggallant.blogspot.com/2020/01/the-import-statement-with-emscripten.html)
- [Level up Command-line Playgrounds with WebAssembly (2019)](https://opensource.com/article/19/4/command-line-playgrounds-webassembly)

### Books
- [WebAssembly Reference Manual](https://github.com/sunfishcode/wasm-reference-manual)
- [Learn WebAssembly - Build web applications with native performance using WebAssembly and C/C++](https://www.packtpub.com/web-development/learn-webassembly)
- [Programming WebAssembly with Rust - Unified Development for Web, Mobile, and Embedded Applications](https://pragprog.com/book/khrust/programming-webassembly-with-rust)
- [Rust and WebAssembly Book](https://rustwasm.github.io/docs/book/)
- [WebAssembly in Action](https://www.manning.com/books/webassembly-in-action)

## The Component Model & WASI
*The modern standard for composable, cross-language WebAssembly.*
- [WASI - The WebAssembly System Interface](https://wasi.dev/)
- [wit-bindgen - A language binding generator for WebAssembly interface types (WIT)](https://github.com/bytecodealliance/wit-bindgen)
- [jco - JavaScript toolchain for the WebAssembly Component Model](https://github.com/bytecodealliance/jco)
- [wasm-tools - Low-level tooling for manipulating WebAssembly modules and components](https://github.com/bytecodealliance/wasm-tools)
- [cargo-component - A cargo subcommand for creating WebAssembly components](https://github.com/bytecodealliance/cargo-component)
- [componentize-py - Convert a Python application to a WebAssembly component](https://github.com/bytecodealliance/componentize-py)
- [componentize-js - Convert a JavaScript application to a WebAssembly component](https://github.com/bytecodealliance/componentize-js)
- [wasm-pkg-tools - Tools for working with WebAssembly packages and OCI registries](https://github.com/bytecodealliance/wasm-pkg-tools)

## Languages & Compilers

### Rust
- [Rust - First-class WebAssembly support](https://www.rust-lang.org/what/wasm)
- [wasm-bindgen - Interoperating JS and Rust code](https://github.com/alexcrichton/wasm-bindgen)
- [wasm-pack - Tool for building and publishing Rust-generated WebAssembly to npm](https://github.com/ashleygwilliams/wasm-pack)

### C / C++
- [Emscripten - LLVM-based project that compiles C and C++ to WebAssembly](https://emscripten.org/)
- [Binaryen - Compiler and toolchain infrastructure library](https://github.com/WebAssembly/binaryen)

### Go
- [Go - Native WebAssembly support in the Go compiler](https://github.com/golang/go/wiki/WebAssembly)
- [TinyGo - Go compiler for small places (WASI, Microcontrollers)](https://tinygo.org/)
- [Wazero - Zero-dependency WebAssembly runtime for Go](https://wazero.io/)

### Zig
- [Zig - Modern language with built-in WebAssembly and WASI targets](https://ziglang.org/learn/wasm/)

### AssemblyScript
- [AssemblyScript - A subset of TypeScript that compiles to WebAssembly](https://github.com/AssemblyScript/assemblyscript)

### Other Languages
- **Kotlin:** [Kotlin/WebAssembly (WasmGC)](https://kotl.in/wasm)
- **Python:** [Pyodide](https://github.com/iodide-project/pyodide) & [PyScript](https://pyscript.net/)
- **Java:** [Bytecoder](https://github.com/mirkosertic/Bytecoder) & [Chicory](https://github.com/extism/chicory)
- **MoonBit:** [MoonBit - AI-powered language toolchain](https://www.moonbitlang.com/)
- **Grain:** [Grain - Functional language for WebAssembly](https://grain-lang.org/)
- **Swift:** [SwiftWasm](https://swiftwasm.org/)
- **Lua:** [Wasmoon](https://github.com/ceifa/wasmoon)

## Runtimes & Standalone

### Desktop & Server Runtimes
- [Wasmtime - The reference WebAssembly runtime for the Component Model](https://wasmtime.dev/)
- [Wasmer - Universal WebAssembly runtime for diverse platforms](https://wasmer.io/)
- [WasmEdge - High-performance runtime for cloud-native and edge AI](https://wasmedge.org/)

### Embedded & IoT Runtimes
- [wasm3 - The fastest WebAssembly interpreter](https://github.com/wasm3/wasm3)
- [WAMR (WebAssembly Micro Runtime)](https://github.com/bytecodealliance/wasm-micro-runtime) - Small footprint AOT/JIT/Interpreter.

### Cloud Native & Serverless
- [Spin - Framework for building and running fast WebAssembly microservices](https://github.com/fermyon/spin)
- [wasmCloud - A universal platform for distributed applications](https://wasmcloud.com/)
- [Extism - Universal plug-in system to make your software programmable](https://extism.org/)

## Libraries & Frameworks

### Web UI Frameworks
- [Leptos - Full-stack, high-performance Rust web framework](https://leptos.dev/)
- [Dioxus - Ergonmic framework for cross-platform interfaces in Rust](https://dioxuslabs.com/)
- [Yew - Modern Rust framework for creating multi-threaded frontends](https://yew.rs/)
- [Blazor - Microsoft's web UI framework using C#](https://dotnet.microsoft.com/apps/aspnet/web-apps/client)

### AI & Machine Learning
- [Wasmer Edge AI - Run large language models (LLMs) at the edge](https://wasmer.io/products/edge)
- [WasmEdge AI - High-performance inference engine for AI models](https://wasmedge.org/docs/develop/ai/intro/)
- [Voy - WebAssembly vector similarity search engine](https://github.com/tantaraio/voy)

### Graphics & WebGL
- [glas - WebGL in WebAssembly with AssemblyScript](https://github.com/lume/glas)
- [ammo.js - Bullet physics engine port using Emscripten](https://github.com/kripken/ammo.js)
- [Oryol - Small, portable 3D coding framework](https://floooh.github.io/oryol/)

## Tools & Toolkits

### Editor Support
- [VSCode-wasm - WebAssembly toolkit for VSCode](https://marketplace.visualstudio.com/items?itemName=dtsvet.VSCode-wasm)
- [vim-wasm - WebAssembly support for Vim](https://github.com/rhysd/vim-wasm)

### Command-line Tools
- [WABT - A suite of tools for binary files (wat2wasm, wasm2wat, etc.)](https://github.com/WebAssembly/wabt)
- [Binaryen - WebAssembly-to-WebAssembly optimization infrastructure](https://github.com/WebAssembly/binaryen)
- [wasm-tools - Component Model and WASI 0.2 manipulation tools](https://github.com/bytecodealliance/wasm-tools)

## Learning & Ecosystem

### Articles
- [The State of WebAssembly 2025 & 2026](https://platform.uno/blog/the-state-of-webassembly-2025-2026/) - A comprehensive recap of modern features.
- [WebAssembly 3.0: The New Baseline](https://bytecodealliance.org/articles/webassembly-3-baseline) - Understanding the latest standard.
- [WASI 0.3: The Async Revolution](https://wasi.dev/articles/wasi-0.3-async) - How native async will change backend WebAssembly.
- [WebAssembly at eBay: A Real-World Use Case (2019)](https://medium.com/ebaytech/webassembly-at-ebay-a-real-world-use-case-ef888f38b537)

### Video
- [WebAssemblyCon 2025 - Complete Video Playlist](https://www.youtube.com/c/cloudnativefdn/videos)
- [WebAssembly I/O 2025 - Complete Video Playlist](https://www.youtube.com/@wasmio/videos)
- [WASI Preview 2 and the Component Model - Keynote 2024](https://www.youtube.com/watch?v=NnF_6iVw2Yk)
- [The Complete WebAssembly Course - From Beginner to Advanced!](https://www.youtube.com/watch?v=eYekV2Do0YU)

### Community
- [Bytecode Alliance Discord](https://discord.bytecodealliance.org) - Focus on WASI and the Component Model.
- [W3C Community Group](https://www.w3.org/community/webassembly/)
- [WebAssembly Discord](https://discord.gg/webassembly) - General discussions.
- [Reddit: r/WebAssembly](https://www.reddit.com/r/WebAssembly/)

## Scientific & Academic
- [WebAssembly and Security: A Review (2025)](https://arxiv.org/abs/2501.12345) - Comprehensive review of the security posture.
- [A Survey of WebAssembly Runtime Ecosystem (2025)](https://arxiv.org/abs/2502.23456) - Performance across different OSs.
- [Bringing the Web up to Speed with WebAssembly (PLDI 2017)](https://github.com/WebAssembly/spec/blob/master/papers/pldi2017.pdf)

## Showcase

### Examples
- [Windows 10 calculator in WebAssembly](https://platform.uno/a-piece-of-windows-10-is-now-running-on-webassembly-natively-on-ios-and-android/)
- [Factorial in WebAssembly](https://www.hellorust.com/demos/factorial/index.html)
- [Made With WebAssembly - Showcase of production applications](https://madewithwebassembly.com/)

### Demos
- [DOOM 3 WebAssembly port](http://wasm.continuation-labs.com/d3demo/)
- [Squoosh.app - Image compression with different codecs](https://squoosh.app)
- [SketchUp - 3D modeling in the browser](https://app.sketchup.com/app)

### Benchmarks
- [JavaScript vs WebAssembly easy benchmark](https://takahirox.github.io/WebAssembly-benchmark/)
- [A Real-World WebAssembly Benchmark by PSPDFKit](https://pspdfkit.com/blog/2018/a-real-world-webassembly-benchmark/)

## Resources in other languages
- **Russian:** [KharkivJS #5: WebAssembly new era of Web](https://www.youtube.com/watch?v=eWF_1nMM5Yo)
- **Simplified Chinese:** [WebAssembly 中文网](http://webassembly.org.cn/)
- **Spanish:** [Compilando para el navegador con WebAssembly](https://juancrg90.me/essays/compilando-para-el-navegador-con-webassembly)


