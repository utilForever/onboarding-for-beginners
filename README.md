<h1 align="center"><strong>🔰 Onboarding Plans for Beginners 🔰</strong></h1>

> A step-by-step onboarding plans and related materials for beginners.

> Check out my [GitHub](https://github.com/utilForever) and say "hi" on [Twitter](https://twitter.com/utilForever). 👋

***
<h3 align="center"><strong>Purpose of these Onboarding Plans</strong></h3>

> Suppose a new team member joins the company. This person used a different programming language in his previous company, so needs to learn a new programming language that fits company's technology stack. 🤔

> I think we should write an onboarding plan for this member to work with us. Let's share various scenarios with collective intelligence to help many people. 🤗

<h3 align="center"><strong>Note to Beginners</strong></h3>

> Don't feel overwhelmed! Also, always ask questions if you don't know anything! It's your first time learning. 😀
***

If you think that these can be improved in any way, please do suggest.

## Rust engineer with cross-platform (iOS, WebAssembly)

### Onboarding Plan (for Beginners)

* Week 1 ~ 2: Learn base knowledge (Rust programming language)
  * Week 1
    * Day 1 (Official Tutorial 1 ~ 3)
      * Setup environments (The Rust Toolchain only)
      * Run first Rust code
      * Understand Rust basics
    * Day 2 (Official Tutorial 4 ~ 6)
      * Understand ownership, borrowing, and pattern matching
      * Practice simple exercises and code review
    * Day 3 (Official Tutorial 7 ~ 9)
      * Understand the relationship among packages, modules, and crates
      * Understand basic collections such as `Vec`, `String` and `BTreeMap`
      * Understand basic error handling
      * Practice simple exercises and code review
    * Day 4 (Official Tutorial 10 ~ 12)
      * Understand generics and traits
      * Understand how to write and run test code
      * Practice simple exercises and code review
    * Day 5 (Official Tutorial 13 ~ 15)
      * Understand iterators and closures
      * Understand smart pointers such as `Box<T>`, `Rc<T>` and `RefCell<T>`
      * Practice simple exercises and code review
  * Week 2
    * Day 1 (Official Tutorial 16 ~ 18)
      * Understand concurrency in Rust using `Mutex<T>` and `Arc<T>`
      * Understand OOP in Rust
      * Practice simple exercises and code review
    * Day 2 (Official Tutorial 19 ~ 20)
      * Understand advanced features in Rust such as unsafe and macros
      * Practice simple exercises and code review
    * Day 3
      * Practical project #1: Rectangles
      * Practical code review
    * Day 4
      * Practical project #2: Circular Buffer
      * Practical code review
    * Day 5
      * Practical project #3: Doubly Linked List
      * Practical code review
* Week 3: Utilize code by using various crates (tokio, serde, prost, rxRust)
  * Day 1 (tokio)
    * tokio: A runtime for writing reliable asynchronous applications with Rust
    * Practice simple exercises and code review: TCP chat
  * Day 2 (serde)
    * serde: Serialization framework for Rust
    * Practice simple exercises and code review: JSON RPC
  * Day 3 (prost)
    * prost: a Protocol Buffers implementation for the Rust Language
    * Practice simple exercises and code review: Protobuf RPC
  * Day 4 (rxRust #1)
    * rxRust: Rust implementation of Reactive Extensions
    * Understand ReactiveX
    * Understand rxRust basics
    * Practice simple exercises and code review
  * Day 5 (rxRust #2)
    * rxRust: Rust implementation of Reactive Extensions
    * Understand rxRust internals
    * Practice simple exercises and code review
* Week 4: Collaborate with cross-platform (iOS and WebAssembly)
  * Day 1 (Rust with iOS #1)
    * Setup environments (iOS related)
    * Practice [Building and Deploying a Rust library on iOS](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-06-rust-on-ios.html)
  * Day 2 (Rust with iOS #2)
    * Practical exercises and code review
      * Rust with iOS + tokio
      * Rust with iOS + prost
      * Rust with iOS + rxRust
  * Day 3 (Rust with WebAssembly #1)
    * Setup environments (WebAssembly related)
    * Practice [Conway's Game of Life](https://rustwasm.github.io/docs/book/game-of-life/introduction.html#tutorial-conways-game-of-life)
  * Day 4 (Rust with WebAssembly #2)
    * Practical exercises and code review
      * Rust with WebAssembly + tokio
      * Rust with WebAssembly + prost
      * Rust with WebAssembly + rxRust
  * Day 5 (Cross-platform)
    * How to make a core engine to support cross-platforms
    * Practical exercise and code review
      * Consider cross-platform compatibility
      * Using tokio, prost and rxRust

### Materials

* Beginner
  * [The Rust Programming Language](https://doc.rust-lang.org/book/)
  * [Rustlings](https://github.com/rust-lang/rustlings/)
  * [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/)
  * [Exercism - Rust](https://exercism.org/tracks/rust)
  * [Book: The Rust Programming Language](http://www.yes24.com/Product/Goods/83075894)
  * [Book: Rust in Action](https://www.manning.com/books/rust-in-action)
  * [Book: Programming Rust](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/)
* Intermediate
  * [The Standard Library](https://doc.rust-lang.org/std/index.html)
  * [The Edition Guide](https://doc.rust-lang.org/edition-guide/index.html)
  * [The Cargo Book](https://doc.rust-lang.org/cargo/index.html)
  * [The rustdoc Book](https://doc.rust-lang.org/rustdoc/index.html)
  * [The rustc Book](https://doc.rust-lang.org/rustc/index.html)
  * [ReactiveX](https://reactivex.io/documentation)
  * [Protocol Buffers](https://developers.google.com/protocol-buffers)
  * [Building and Deploying a Rust library on iOS](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-06-rust-on-ios.html)
  * [Rust and WebAssembly](https://rustwasm.github.io/docs/book/)
  * [Book: Concurrent Programming](http://www.yes24.com/Product/Goods/108570426)
  * [Book: Rust for Rustaceans](https://rust-for-rustaceans.com/)
* Advanced
  * [The Rust Reference](https://doc.rust-lang.org/reference/index.html)
  * [The Rustonomicon](https://doc.rust-lang.org/nomicon/index.html)
  * [The Rust Unstable Book](https://doc.rust-lang.org/nightly/unstable-book/index.html)
  * [Book: The Art of WebAssembly](https://nostarch.com/art-webassembly)
  * [Book: WebAssembly: The Definitive Guide](https://www.oreilly.com/library/view/webassembly-the-definitive/9781492089834/)
* Other resources
  * [The Rustacean Station Podcast](https://rustacean-station.org/)
  * [Rust Conference Videos](https://www.youtube.com/c/RustVideos)
  * [Rust's Discord](https://discord.gg/rust-lang)
  * [rxRust Repository](https://github.com/rxRust/rxRust)
  * [prost Repository](https://github.com/tokio-rs/prost)
  * [tokio Repository](https://github.com/tokio-rs/tokio)
  * [RxMarbles](https://rxmarbles.com/)

## 🚦 Wrap Up

If you think any of the onboarding plans can be improved, please do open a PR with any updates and submit any issues. Also, I will continue to improve this, so you might want to watch/star this repository to revisit.

## 🙌 Contribution

Contributions are always welcome, either reporting issues/bugs or forking the repository and then issuing pull requests when you have completed some additional coding that you feel will be beneficial to the main project.

- Open pull request with improvements
- Discuss ideas in issues
- Spread the word
- Reach out to me directly at utilforever@gmail.com or [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/utilForever.svg?style=social&label=Follow%20%40utilForever)](https://twitter.com/utilForever)

## License

<img align="right" src="http://opensource.org/trademarks/opensource/OSI-Approved-License-100x137.png">

The class is licensed under the [MIT License](http://opensource.org/licenses/MIT):

Copyright &copy; 2022 [Chris Ohk](http://www.github.com/utilForever).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
