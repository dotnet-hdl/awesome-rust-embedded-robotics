# Awesome-Rust-List
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

🔥🔥🔥 This repository lists some awesome public Rust programming language projects.

## Contents
- [Awesome-Rust-List](#awesome-rust-list)
  - [Contents](#contents)
  - [Summary](#summary)
    - [Official Rust](#official-rust)
    - [Awesome List](#awesome-list)
    - [Learning Resources](#learning-resources)
    - [Learning Resources](#learning-resources)
  - [Data Structure and Algorithm](#data-structure-and-algorithm)
  - [Parallelism Library](#parallelism-library)
  - [Asynchronous Runtime](#asynchronous-runtime)
  - [FFI Bindings](#ffi-bindings)
  - [GPU Computing](#gpu-computing)
  - [Scientific Computation](#scientific-computation)
    - [Numerical Calculation](#numerical-calculation)
    - [Linear Algebra](#linear-algebra)
    - [Lie Groups](#lie-groups)
    - [Optimization Engine](#optimization-engine)
    - [Finite Element Analysis](#finite-element-analysis)
    - [Data Analysis and Visualization](#data-analysis-and-visualization)
  - [Machine Learning](#machine-learning)
    - [Machine Learning Framework](#machine-learning-framework)
    - [Large Language Model](#large-language-model)
    - [Stable Diffusion](#stable-diffusion)
    - [Object Detection](#object-detection)
  - [Design Pattern](#design-pattern)
  - [Static Variables](#static-variables)
  - [Memory Allocator](#memory-allocator)
  - [Embedded Development](#embedded-development)
  - [General Operating System](#general-operating-system)
  - [Robot Operating System](#robot-operating-system)
  - [Hardware Description Language](#hardware-description-language)
  - [Logic Programming](#logic-programming)
  - [Shared Memory](#shared-memory)
  - [Remote Desktop](#remote-desktop)
  - [Date and Time](#date-and-time)
  - [Data Encryption](#data-encryption)
  - [Database](#database)
  - [Sensor and Communication Protocol](#sensor-and-communication-protocol)
  - [Signal Processing](#signal-processing)
  - [Text Processing](#text-processing)
  - [Image and Video Processing](#image-and-video-processing)
  - [Localization and Mapping](#localization-and-mapping)
  - [Path Planning](#path-planning)
  - [Motion Control](#motion-control)
  - [Finite State Machine](#finite-state-machine)
  - [Game Field](#game-field)
  - [Search Engine](#search-engine)
  - [Web Crawler](#web-crawler)
  - [Web Framework](#web-framework)
  - [RPC Framework](#rpc-framework)
  - [Web3 Framework](#web3-framework)
  - [WebAssembly](#webassembly)
  - [Graphics Library](#graphics-library)
  - [GUI](#gui)
    - [GUI Framework](#gui-framework)
        - [Desktop APP Development](#desktop-app-development)
        - [Mobile APP Development](#mobile-app-development)
    - [GUI Software](#gui-framework)
        - [Tauri-Related](#tauri-related)
        - [Slint-Related](#slint-related)
        - [Makepad-Related](#makepad-related)
  - [Blogs](#blogs)



## Summary

  - ### Official Rust

    - [Rust](https://github.com/rust-lang/rust) <img src="https://img.shields.io/github/stars/rust-lang/rust?style=social"/> : The Rust Programming Language. Empowering everyone to build reliable and efficient software. [www.rust-lang.org](www.rust-lang.org). [Rust Foundation](https://foundation.rust-lang.org/).

    - [Rust std](https://doc.rust-lang.org/std/index.html) : The Rust Standard Library.

    - [Docs.rs](https://docs.rs/) : Docs.rs documentation.

    - [Cheats.rs](https://github.com/ralfbiedert/cheats.rs/) <img src="https://img.shields.io/github/stars/ralfbiedert/cheats.rs?style=social"/> : Rust Language Cheat Sheet. [cheats.rs](https://cheats.rs/)

    - [crates.io](https://crates.io/) : The Rust community’s crate registry.

    - [Lib.rs](https://lib.rs/) : Fast, lightweight, opinionated, unofficial alternative to crates.io.

    - [Rust Playground](https://play.rust-lang.org/) : The Rust Playground. [rust-lang/rust-playground](https://github.com/rust-lang/rust-playground) <img src="https://img.shields.io/github/stars/rust-lang/rust-playground?style=social"/>.



  - ### Awesome List

    - [rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust) <img src="https://img.shields.io/github/stars/rust-unofficial/awesome-rust?style=social"/> : A curated list of Rust code and resources.

    - [rust-embedded/awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) <img src="https://img.shields.io/github/stars/rust-embedded/awesome-embedded-rust?style=social"/> : Curated list of resources for Embedded and Low-level development in the Rust programming language.

    - [TaKO8Ki/awesome-alternatives-in-rust](https://github.com/TaKO8Ki/awesome-alternatives-in-rust) <img src="https://img.shields.io/github/stars/TaKO8Ki/awesome-alternatives-in-rust?style=social"/> : A curated list of replacements for existing software written in Rust.

    - [rust-in-blockchain/awesome-blockchain-rust](https://github.com/rust-in-blockchain/awesome-blockchain-rust) <img src="https://img.shields.io/github/stars/rust-in-blockchain/awesome-blockchain-rust?style=social"/> : Collect libraries and packages about blockchain/cryptography in Rust.

    - [jetli/awesome-yew](https://github.com/jetli/awesome-yew) <img src="https://img.shields.io/github/stars/jetli/awesome-yew?style=social"/> : 😎 A curated list of awesome things related to Yew / WebAssembly.

    - [vaaaaanquish/Awesome-Rust-MachineLearning](https://github.com/vaaaaanquish/Awesome-Rust-MachineLearning) <img src="https://img.shields.io/github/stars/vaaaaanquish/Awesome-Rust-MachineLearning?style=social"/> : This repository is a list of machine learning libraries written in Rust. It's a compilation of GitHub repositories, blogs, books, movies, discussions, papers, etc. 🦀

    - [awesome-rust-com/awesome-rust](https://github.com/awesome-rust-com/awesome-rust) <img src="https://img.shields.io/github/stars/awesome-rust-com/awesome-rust?style=social"/> :A curated list of awesome Rust frameworks, libraries and software. [awesome-rust](https://awesome-rust.com/)

    - [rust-cc/awesome-cryptography-rust](https://github.com/rust-cc/awesome-cryptography-rust) <img src="https://img.shields.io/github/stars/rust-cc/awesome-cryptography-rust?style=social"/> : Collect libraries and packages about cryptography in Rust.

    - [ddotta/awesome-polars](https://github.com/ddotta/awesome-polars) <img src="https://img.shields.io/github/stars/ddotta/awesome-polars?style=social"/> : A curated list of [Polars](https://www.pola.rs/) talks, tools, examples & articles. Contributions welcome !

    - [ex0dus-0x/awesome-rust-security](https://github.com/ex0dus-0x/awesome-rust-security) <img src="https://img.shields.io/github/stars/ex0dus-0x/awesome-rust-security?style=social"/> : Curated list of awesome projects and resources related to Rust and computer security.

    - [robotics-rs/robotics.rs](https://github.com/robotics-rs/robotics.rs) <img src="https://img.shields.io/github/stars/robotics-rs/robotics.rs?style=social"/> : List of (awesome) Rust libraries for Robotics. Web site of robotics.rs. See index.md. [robotics.rs](https://robotics.rs/)

    - [jgsimard/RustRobotics](https://github.com/jgsimard/RustRobotics) <img src="https://img.shields.io/github/stars/jgsimard/RustRobotics?style=social"/> : This package is a rust implementation of robotics algorithms. So far, the main source is the book [Probabilistic Robotics](https://mitpress.mit.edu/9780262201629/probabilistic-robotics/).

    - [rsasaki0109/RustRobotics](https://github.com/rsasaki0109/RustRobotics) <img src="https://img.shields.io/github/stars/rsasaki0109/RustRobotics?style=social"/> : Rust implementation of PythonRobotics such as EKF, DWA, Pure Pursuit, LQR.




  - ### Learning Resources

    - [Rust std](https://doc.rust-lang.org/std/index.html) : The Rust Standard Library.

    - [Docs.rs](https://docs.rs/) : Docs.rs documentation.

    - [Cheats.rs](https://github.com/ralfbiedert/cheats.rs/) <img src="https://img.shields.io/github/stars/ralfbiedert/cheats.rs?style=social"/> : Rust Language Cheat Sheet. [cheats.rs](https://cheats.rs/)

    - [kingfree/cheats.rs](https://github.com/kingfree/cheats.rs/) <img src="https://img.shields.io/github/stars/kingfree/cheats.rs?style=social"/> : Rust 语言备忘清单 (简体中文). [https://cheats.rs.kingfree.moe/](https://cheats.rs.kingfree.moe/)

    - [rust-lang/book](https://github.com/rust-lang/book) <img src="https://img.shields.io/github/stars/rust-lang/book?style=social"/> : The Rust Programming Language. [doc.rust-lang.org/book/](https://doc.rust-lang.org/book/)

    - [rust-lang/reference](https://github.com/rust-lang/reference) <img src="https://img.shields.io/github/stars/rust-lang/reference?style=social"/> : The Rust Reference. [doc.rust-lang.org/nightly/reference/](https://doc.rust-lang.org/reference/)

    - [pretzelhammer/rust-blog](https://github.com/pretzelhammer/rust-blog) <img src="https://img.shields.io/github/stars/pretzelhammer/rust-blog?style=social"/> : pretzelhammer's Rust blog 🦀. Educational blog posts for Rust beginners.

    - [ctjhoa/rust-learning](https://github.com/ctjhoa/rust-learning) <img src="https://img.shields.io/github/stars/ctjhoa/rust-learning?style=social"/> : A bunch of links to blog posts, articles, videos, etc for learning Rust.

    - [lborb/book](https://github.com/lborb/book) <img src="https://img.shields.io/github/stars/lborb/book?style=social"/> : The Little Book of Rust Books. [lborb.github.io/book/](https://lborb.github.io/book/)

    - [instrumentisto/rust-incubator](https://github.com/instrumentisto/rust-incubator) <img src="https://img.shields.io/github/stars/instrumentisto/rust-incubator?style=social"/> :  Learning Rust step-by-step. This project represents a hard-way step-by-step Rust learning course from language basics to a capability of web backend development.

    - [1595901624/StudyRust](https://github.com/1595901624/StudyRust) <img src="https://img.shields.io/github/stars/1595901624/StudyRust?style=social"/> :  公众号：《Rust学习日记》Rust 学习日记 源码 ，让你的Rust从0基础小白到大牛。

    - [rust-lang/rust-by-example](https://github.com/rust-lang/rust-by-example) <img src="https://img.shields.io/github/stars/rust-lang/rust-by-example?style=social"/> : Learn Rust with examples (Live code editor included). [doc.rust-lang.org/stable/rust-by-example/](https://doc.rust-lang.org/stable/rust-by-example/)

    - [rust-lang/rustlings](https://github.com/rust-lang/rustlings) <img src="https://img.shields.io/github/stars/rust-lang/rustlings?style=social"/> : rustlings 🦀❤️. 🦀 Small exercises to get you used to reading and writing Rust code!

    - [MacroKata](https://tfpk.github.io/macrokata/) : Welcome to MacroKata, a set of exercises which you can use to learn how to write macros in Rust.

    - [veykril/tlborm](https://github.com/veykril/tlborm/) <img src="https://img.shields.io/github/stars/veykril/tlborm?style=social"/> : The Little Book of Rust Macros (updated fork). [veykril.github.io/tlborm/](https://veykril.github.io/tlborm/). [The Little Book of Rust Macros （Rust 宏小册）](https://zjp-cn.github.io/tlborm/)

    - [dtolnay/proc-macro-workshop](https://github.com/dtolnay/proc-macro-workshop) <img src="https://img.shields.io/github/stars/dtolnay/proc-macro-workshop?style=social"/> : Rust Latam: procedural macros workshop. This repo contains a selection of projects designed to learn to write Rust procedural macros — Rust code that generates Rust code.

    - [dtolnay/proc-macro2](https://github.com/dtolnay/proc-macro2) <img src="https://img.shields.io/github/stars/dtolnay/proc-macro2?style=social"/> : A wrapper around the procedural macro API of the compiler's proc_macro crate.

    - [nrc/proc-macro-rules](https://github.com/nrc/proc-macro-rules) <img src="https://img.shields.io/github/stars/nrc/proc-macro-rules?style=social"/> : Macro-rules-style syntax matching for procedural macros.

    - [rustomax/rust-iterators](https://github.com/rustomax/rust-iterators) <img src="https://img.shields.io/github/stars/rustomax/rust-iterators?style=social"/> : Basic Rust iterator usage. The goal of this tutorial is to provide a handy reference to some of the common iterator patterns.

    - [Rust文档网](https://rustwiki.org/) : Rust 官方文档中文教程。

    - [rust-boom/rust-boom](https://github.com/rust-boom/rust-boom) <img src="https://img.shields.io/github/stars/rust-boom/rust-boom?style=social"/> : rust awesome（资源）. 💥 [rust-boom.github.io/rust-boom/](https://rust-boom.github.io/rust-boom/). Rust Boom 是一个仓主在学习使用 Rust 的时候，对 Rust 的一些难点的解决方法以及一些 Rust 开源的好玩的库、书籍、文章的整理，希望可以帮助更多的 Rust 初学者来翻过 Rust 这座大山。

    - [Rust程序设计语言](https://kaisery.github.io/trpl-zh-cn/) : Rust 程序设计语言 简体中文版。

    - [rust-lang-cn/reference-cn](https://github.com/rust-lang-cn/reference-cn) <img src="https://img.shields.io/github/stars/rust-lang-cn/reference-cn?style=social"/> : Rust 参考手册 中文版——Chinese translation of The Rust Reference. [rustwiki.org/zh-CN/reference](https://rustwiki.org/zh-CN/reference/)

    - [sunface/rust-course](https://github.com/sunface/rust-course) <img src="https://img.shields.io/github/stars/sunface/rust-course?style=social"/> : Rust语言圣经(Rust Course)。“连续六年成为全世界最受喜爱的语言，无 GC 也无需手动内存管理、极高的性能和安全性、过程/OO/函数式编程、优秀的包管理、JS 未来基石" — 工作之余的第二语言来试试Rust吧。<<Rust语言圣经>>拥有全面且深入的讲解、生动贴切的示例、德芙般丝滑的内容，甚至还有JS程序员关注的 WASM 和 Deno 等专题。这可能是目前最用心的 Rust 中文学习教程。[course.rs](https://course.rs/about-book.html)

    - [rust-lang-cn/rust-by-example-cn](https://github.com/rust-lang-cn/rust-by-example-cn) <img src="https://img.shields.io/github/stars/rust-lang-cn/rust-by-example-cn?style=social"/> : Rust By Example 中文版(包含在线代码编辑器)。[通过例子学 Rust 中文版](https://rustwiki.org/zh-CN/rust-by-example/)

    - [sunface/rust-by-practice](https://github.com/sunface/rust-by-practice) <img src="https://img.shields.io/github/stars/sunface/rust-by-practice?style=social"/> : Learning Rust By Practice, narrowing the gap between beginner and skilled-dev through challenging examples, exercises and projects. [Rust By Practice(Rust语言实战)](https://zh.practice.rs/why-exercise.html)

    - [rust-lang-cn/nomicon-zh-Hans](https://github.com/rust-lang-cn/nomicon-zh-Hans) <img src="https://img.shields.io/github/stars/rust-lang-cn/nomicon-zh-Hans?style=social"/> : Rust 秘典（死灵书）。[nomicon.purewhite.io/](https://nomicon.purewhite.io/)

    - [tyrchen/geektime-rust](https://github.com/tyrchen/geektime-rust) <img src="https://img.shields.io/github/stars/tyrchen/geektime-rust?style=social"/> : geektime-rust：我的极客时间 Rust 课程的代码仓库，随课程更新。

    - [Warrenren/inside-rust-std-library](https://github.com/Warrenren/inside-rust-std-library) <img src="https://img.shields.io/github/stars/Warrenren/inside-rust-std-library?style=social"/> : 本书主要对RUST的标准库代码进行分析，并试图给出RUST标准库代码的分析脉络。This project try to give a venation of how reading the RUST standard library source code.

    - [wtklbm/rust-library-i18n](https://github.com/wtklbm/rust-library-i18n) <img src="https://img.shields.io/github/stars/wtklbm/rust-library-i18n?style=social"/> : Rust 核心库和标准库中文翻译，可作为 IDE 工具的智能提示，并生成本地 API 文档。

    - [johnthagen/min-sized-rust](https://github.com/johnthagen/min-sized-rust) <img src="https://img.shields.io/github/stars/johnthagen/min-sized-rust?style=social"/> :  🦀 How to minimize Rust binary size 📦

    - [better-rs/learn-rs](https://github.com/better-rs/learn-rs) <img src="https://img.shields.io/github/stars/better-rs/learn-rs?style=social"/> :  learn-rs: 快速学习 rust。

    - [Tauri + Vue3 + Naive-UI Template](https://github.com/better-rs/learn-rs/blob/main/crates/rs-tauri-vue/README.md) <img src="https://img.shields.io/github/stars/better-rs/learn-rs?style=social"/> : Tauri + Vue3 + Naive-UI Template.  前端框架: typescript + vue3 + naive-ui.

    - [better-rs/annotated-rs](https://github.com/better-rs/annotated-rs) <img src="https://img.shields.io/github/stars/better-rs/annotated-rs?style=social"/> : annotated-rs: rust 知名项目源码分析。

    - [zanderxyz/advent-of-code](https://github.com/zanderxyz/advent-of-code) <img src="https://img.shields.io/github/stars/zanderxyz/advent-of-code?style=social"/> : My solutions to the annual Advent of Code problems. 2020 in Zig; 2021/22 in Rust. [www.adventofcode.com/](https://adventofcode.com/)

    - [pavloslav/advent-of-code-rust](https://github.com/pavloslav/advent-of-code-rust) <img src="https://img.shields.io/github/stars/pavloslav/advent-of-code-rust?style=social"/> : Learning Rust language.

    - [kovyrin/aoc2022](https://github.com/kovyrin/aoc2022) <img src="https://img.shields.io/github/stars/kovyrin/aoc2022?style=social"/> :  Playing with AOC 2022 problems using Rust.

    - [CreatorsDAO/rust-co-learn](https://github.com/CreatorsDAO/rust-co-learn) <img src="https://img.shields.io/github/stars/CreatorsDAO/rust-co-learn?style=social"/> : rust-co-learn.

    - [DaviRain-Su/all-in-one-rust](https://github.com/DaviRain-Su/all-in-one-rust) <img src="https://img.shields.io/github/stars/DaviRain-Su/all-in-one-rust?style=social"/> : all-in-one-rust.

    - [DaviRain-Su/rust-no-std-source](https://github.com/DaviRain-Su/rust-no-std-source) <img src="https://img.shields.io/github/stars/DaviRain-Su/rust-no-std-source?style=social"/> : About Rust no std sources.

    - [night-cruise/async-rust](https://github.com/night-cruise/async-rust) <img src="https://img.shields.io/github/stars/night-cruise/async-rust?style=social"/> : 这是一本电子书，旨在介绍 Rust 中 async/await 语法和异步运行时的原理和工作机制。[night-cruise.github.io/async-rust/](https://night-cruise.github.io/async-rust/)






## Data Structure and Algorithm

  - [krahets/hello-algo](https://github.com/krahets/hello-algo) <img src="https://img.shields.io/github/stars/krahets/hello-algo?style=social"/> : 《Hello 算法》是一本动画图解、能运行、可提问的数据结构与算法入门书，支持 Java, C++, Python, Go, JS, TS, C#, Swift, Zig 等语言。 前往阅读 > [hello-algo.com](https://www.hello-algo.com/).

  - [sjinzh/hello-algo-rust](https://github.com/sjinzh/hello-algo-rust) <img src="https://img.shields.io/github/stars/sjinzh/hello-algo-rust-zig?style=social"/> : Rust codes for the famous public project [《Hello, Algorithm》|《 Hello，算法 》](https://github.com/krahets/hello-algo) about data structures and algorithms.

  - [TheAlgorithms/Rust](https://github.com/TheAlgorithms/Rust) <img src="https://img.shields.io/github/stars/TheAlgorithms/Rust?style=social"/> : All Algorithms implemented in Rust.

  - [EbTech/rust-algorithms](https://github.com/EbTech/rust-algorithms) <img src="https://img.shields.io/github/stars/EbTech/rust-algorithms?style=social"/> : Common data structures and algorithms in Rust. A collection of classic data structures and algorithms, emphasizing usability, beauty and clarity over full generality.

  - [rust-unofficial/too-many-lists](https://github.com/rust-unofficial/too-many-lists) <img src="https://img.shields.io/github/stars/rust-unofficial/too-many-lists?style=social"/> : [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/index.html).

  - [rustlang-cn/rust-algos](https://github.com/rustlang-cn/rust-algos) <img src="https://img.shields.io/github/stars/rustlang-cn/rust-algos?style=social"/> : Rust算法题解，用Rust语言实现常见的算法和数据结构，以及leetcode题解。

  - [QMHTMY/RustBook](https://github.com/QMHTMY/RustBook) <img src="https://img.shields.io/github/stars/QMHTMY/RustBook?style=social"/> : A book about Rust Data Structures and Algorithms.

  - [matey-jack/dl-list-mini.fs](https://gist.github.com/matey-jack/3e19b6370c6f7036a9119b79a82098ca) : Simple doubly-linked list in safe Rust.

  - [Bonsai](https://github.com/Sollimann/bonsai) <img src="https://img.shields.io/github/stars/Sollimann/bonsai?style=social"/> : Rust implementation of behavior trees.

  - [msakuta/rusty-behavior-tree-lite](https://github.com/msakuta/rusty-behavior-tree-lite) <img src="https://img.shields.io/github/stars/msakuta/rusty-behavior-tree-lite?style=social"/> : Lightweight behavior tree implementation in Rust.

  - [darthdeus/behavior-tree](https://github.com/darthdeus/behavior-tree) <img src="https://img.shields.io/github/stars/darthdeus/behavior-tree?style=social"/> : Behavior trees for Rust!

  - [callmestech/lists](https://github.com/callmestech/lists) <img src="https://img.shields.io/github/stars/callmestech/lists?style=social"/> : Learning Rust With Entirely Too Many Linked Lists.



## Parallelism Library

  - [Rayon](https://github.com/rayon-rs/rayon) <img src="https://img.shields.io/github/stars/rayon-rs/rayon?style=social"/> : Rayon: A data parallelism library for Rust.

  - [Flume](https://github.com/zesterer/flume) <img src="https://img.shields.io/github/stars/zesterer/flume?style=social"/> : A safe and fast multi-producer, multi-consumer channel. [crates.io/crates/flume](https://crates.io/crates/flume)





## Asynchronous Runtime

  - [Tokio](https://github.com/tokio-rs/tokio) <img src="https://img.shields.io/github/stars/tokio-rs/tokio?style=social"/> : A runtime for writing reliable, asynchronous, and slim applications with the Rust programming language.

  - [May](https://github.com/Xudong-Huang/may) <img src="https://img.shields.io/github/stars/Xudong-Huang/may?style=social"/> : May is a high-performance library for programming stackful coroutines with which you can easily develop and maintain massive concurrent programs. It can be thought as the Rust version of the popular [Goroutine](https://tour.golang.org/concurrency/1).




## FFI Bindings

  - [PyO3](https://github.com/PyO3/pyo3) <img src="https://img.shields.io/github/stars/PyO3/pyo3?style=social"/> : Rust bindings for the Python interpreter.

  - [bindgen](https://github.com/rust-lang/rust-bindgen) <img src="https://img.shields.io/github/stars/rust-lang/rust-bindgen?style=social"/> : Automatically generates Rust FFI bindings to C (and some C++) libraries.

  - [C2Rust](https://github.com/immunant/c2rust) <img src="https://img.shields.io/github/stars/immunant/c2rust?style=social"/> : C2Rust helps you migrate C99-compliant code to Rust. [c2rust.com/](https://c2rust.com/)

  - [embed-c](https://github.com/zdimension/embed-c) <img src="https://img.shields.io/github/stars/zdimension/embed-c?style=social"/> : Embed C code at compile time inside Rust using C2Rust.

  - [rust-cpp](https://github.com/mystor/rust-cpp) <img src="https://img.shields.io/github/stars/mystor/rust-cpp?style=social"/> : rust-cpp - Embed C++ code directly in Rust.

  - [cxx](https://github.com/dtolnay/cxx) <img src="https://img.shields.io/github/stars/dtolnay/cxx?style=social"/> : Safe interop between Rust and C++. [cxx.rs](https://cxx.rs/)

  - [Autocxx](https://github.com/google/autocxx) <img src="https://img.shields.io/github/stars/google/autocxx?style=social"/> : Tool for safe ergonomic Rust/C++ interop driven from existing C++ headers. [docs.rs/autocxx](https://docs.rs/autocxx/latest/autocxx/)

  - [safer_ffi](https://github.com/getditto/safer_ffi) <img src="https://img.shields.io/github/stars/getditto/safer_ffi?style=social"/> : Write safer FFI code in Rust without polluting it with unsafe code. [getditto.github.io/safer_ffi](https://getditto.github.io/safer_ffi/)

  - [UniFFI](https://github.com/mozilla/uniffi-rs) <img src="https://img.shields.io/github/stars/mozilla/uniffi-rs?style=social"/> : UniFFI - a multi-language bindings generator for Rust. [mozilla.github.io/uniffi-rs/](https://mozilla.github.io/uniffi-rs/)

  - [Diplomat](https://github.com/rust-diplomat/diplomat) <img src="https://img.shields.io/github/stars/rust-diplomat/diplomat?style=social"/> : Experimental Rust tool for generating FFI definitions allowing many other languages to call Rust code.

  - [jlrs](https://github.com/Taaitaaiger/jlrs) <img src="https://img.shields.io/github/stars/Taaitaaiger/jlrs?style=social"/> : Julia bindings for Rust.

  - [Rutie](https://github.com/danielpclark/rutie) <img src="https://img.shields.io/github/stars/danielpclark/rutie?style=social"/> : “The Tie Between Ruby and Rust.”

  - [suirad/zig-header-gen](https://github.com/suirad/zig-header-gen) <img src="https://img.shields.io/github/stars/suirad/zig-header-gen?style=social"/> : Automatically generate headers/bindings for other languages from Zig code.

  - [kassane/zFFI](https://github.com/kassane/zFFI) <img src="https://img.shields.io/github/stars/kassane/zFFI?style=social"/> : CBindgen FFI test.

  - [emilHof/zigc](https://github.com/emilHof/zigc) <img src="https://img.shields.io/github/stars/emilHof/zigc?style=social"/> : Zigc aims to provide the basic functionality for compiling and linking [Zig](https://ziglang.org/) libraries into your [Rust](https://www.rust-lang.org/) projects.

  - [jeremyBanks/zig_with_cargo](https://github.com/jeremyBanks/zig_with_cargo) <img src="https://img.shields.io/github/stars/jeremyBanks/zig_with_cargo?style=social"/> : Building Zig libraries in a Rust Cargo package.

  - [nekodjin/rusty-ziguanas](https://github.com/nekodjin/rusty-ziguanas) <img src="https://img.shields.io/github/stars/nekodjin/rusty-ziguanas?style=social"/> : Experiments in Zig-Rust and Rust-Zig FFI.

  - [DutchGhost/zigiffy](https://github.com/DutchGhost/zigiffy) <img src="https://img.shields.io/github/stars/DutchGhost/zigiffy?style=social"/> : Rust FFI with Zig.

  - [DutchGhost/rustiffy](https://github.com/DutchGhost/rustiffy) <img src="https://img.shields.io/github/stars/DutchGhost/rustiffy?style=social"/> : Zig FFI with Rust.

  - [natanalt/zig2rs](https://github.com/natanalt/zig2rs) <img src="https://img.shields.io/github/stars/natanalt/zig2rs?style=social"/> : use zig code in rust - a medium effort shitpost.

  - [ogxd/ffidji](https://github.com/ogxd/ffidji) <img src="https://img.shields.io/github/stars/ogxd/ffidji?style=social"/> : 🐶 FFIDJI is a tool to automatically generate bindings between languages, like calling Rust code from C# for instance.

  - [Deukhoofd/csharp_binder](https://github.com/Deukhoofd/csharp_binder) <img src="https://img.shields.io/github/stars/Deukhoofd/csharp_binder?style=social"/> : A simple library to generate C# bindings for a Rust foreign function interface (FFI).

  - [toolness/csharpbindgen](https://github.com/toolness/csharpbindgen) <img src="https://img.shields.io/github/stars/toolness/csharpbindgen?style=social"/> : A Rust library for generating C# bindings from Rust code.

  - [Cysharp/csbindgen](https://github.com/Cysharp/csbindgen) <img src="https://img.shields.io/github/stars/Cysharp/csbindgen?style=social"/> : Generate C# FFI from Rust for automatically brings native code and C native library to .NET and Unity.

  - [nikomatsakis/duchess](https://github.com/nikomatsakis/duchess) <img src="https://img.shields.io/github/stars/nikomatsakis/duchess?style=social"/> : Experiments with Java-Rust interop.

  - [antoniusnaumann/cargo-swift](https://github.com/antoniusnaumann/cargo-swift) <img src="https://img.shields.io/github/stars/antoniusnaumann/cargo-swift?style=social"/> : A cargo plugin to easily build Swift packages from Rust code. [crates.io/crates/cargo-swift](https://crates.io/crates/cargo-swift)

  - [tomleavy/safer-ffi-gen](https://github.com/tomleavy/safer-ffi-gen) <img src="https://img.shields.io/github/stars/tomleavy/safer-ffi-gen?style=social"/> : Attribute macro to help automate Rust FFI bindings.

  - [py2many/py2many](https://github.com/py2many/py2many) <img src="https://img.shields.io/github/stars/py2many/py2many?style=social"/> : Transpiler of Python to many other languages.






## GPU Computing

  - [cudarc](https://github.com/coreylowman/cudarc) <img src="https://img.shields.io/github/stars/coreylowman/cudarc?style=social"/> : cudarc: minimal and safe api over the cuda toolkit.

  - [Vulkano](https://github.com/vulkano-rs/vulkano) <img src="https://img.shields.io/github/stars/vulkano-rs/vulkano?style=social"/> : Safe and rich Rust wrapper around the Vulkan API. Vulkano is a Rust wrapper around [the Vulkan graphics API](https://www.vulkan.org/). It follows the Rust philosophy, which is that as long as you don't use unsafe code you shouldn't be able to trigger any undefined behavior. In the case of Vulkan, this means that non-unsafe code should always conform to valid API usage.

  - [rust-gpu](https://github.com/EmbarkStudios/rust-gpu) <img src="https://img.shields.io/github/stars/EmbarkStudios/rust-gpu?style=social"/> : 🐉 Making Rust a first-class language and ecosystem for GPU shaders 🚧 [shader.rs](https://shader.rs/)

  - [wgpu](https://github.com/gfx-rs/wgpu) <img src="https://img.shields.io/github/stars/gfx-rs/wgpu?style=social"/> : Safe and portable GPU abstraction in Rust, implementing WebGPU API. [wgpu.rs](https://wgpu.rs/)

  - [custos](https://github.com/elftausend/custos) <img src="https://img.shields.io/github/stars/elftausend/custos?style=social"/> : A minimal OpenCL, CUDA, WGPU and host CPU array manipulation engine / framework.

  - [Ash](https://github.com/ash-rs/ash) <img src="https://img.shields.io/github/stars/ash-rs/ash?style=social"/> : Vulkan bindings for Rust.

  - [Rust-CUDA](https://github.com/Rust-GPU/Rust-CUDA) <img src="https://img.shields.io/github/stars/Rust-GPU/Rust-CUDA?style=social"/> : Ecosystem of libraries and tools for writing and executing fast GPU code fully in Rust.

  - [ocl](https://github.com/cogciprocate/ocl) <img src="https://img.shields.io/github/stars/cogciprocate/ocl?style=social"/> : OpenCL for Rust.

  - [opencl3](https://github.com/kenba/opencl3) <img src="https://img.shields.io/github/stars/kenba/opencl3?style=social"/> : A Rust implementation of the Khronos [OpenCL 3.0](https://registry.khronos.org/OpenCL/) API.

  - [Jafagervik/cruda](https://github.com/Jafagervik/cruda) <img src="https://img.shields.io/github/stars/Jafagervik/cruda?style=social"/> : CRUDA - Writing rust with cuda.

  - [oddity-ai/async-cuda](https://github.com/oddity-ai/async-cuda) <img src="https://img.shields.io/github/stars/oddity-ai/async-cuda?style=social"/> : Asynchronous CUDA, NPP and TensorRT for Rust.

  - [lennyerik/cutransform](https://github.com/lennyerik/cutransform) <img src="https://img.shields.io/github/stars/lennyerik/cutransform?style=social"/> : CUDA kernels in any language supported by LLVM.





## Scientific Computation

  - ### Numerical Calculation

    - [rapl](https://github.com/JErnestoMtz/rapl) <img src="https://img.shields.io/github/stars/JErnestoMtz/rapl?style=social"/> : Rank Polymorphic array library for Rust. rapl is an experimental numerical computing Rust library that provides a simple way of working with N-dimensional array, along with a wide range of mathematical functions to manipulate them. It takes inspiration from NumPy and APL, with the primary aim of achieving maximum ergonomics and user-friendliness while maintaining generality.

    - [scilib](https://github.com/At0micBee/scilib) <img src="https://img.shields.io/github/stars/At0micBee/scilib?style=social"/> : A rust crate for mathematics and science. [crates.io/crates/scilib](https://crates.io/crates/scilib)

    - [fitting-rs](https://github.com/mshrtsr/fitting-rs) <img src="https://img.shields.io/github/stars/mshrtsr/fitting-rs?style=social"/> : Curve fitting library for Rust. [crates.io/crates/fitting](https://crates.io/crates/fitting)


  - ### Linear Algebra

    - [mathbench](https://github.com/bitshifter/mathbench-rs) <img src="https://img.shields.io/github/stars/bitshifter/mathbench-rs?style=social"/> : mathbench is a suite of unit tests and benchmarks comparing the output and performance of a number of different Rust linear algebra libraries for common game and graphics development tasks.

    - [ndarray](https://github.com/rust-ndarray/ndarray) <img src="https://img.shields.io/github/stars/rust-ndarray/ndarray?style=social"/> : The ndarray crate provides an n-dimensional container for general elements and for numerics.

    - [ndarray-linalg](https://github.com/rust-ndarray/ndarray-linalg) <img src="https://img.shields.io/github/stars/rust-ndarray/ndarray-linalg?style=social"/> : Linear algebra package for rust-ndarray using LAPACK binding.

    - [nalgebra](https://github.com/dimforge/nalgebra) <img src="https://img.shields.io/github/stars/dimforge/nalgebra?style=social"/> : Linear algebra library for the Rust programming language.

    - [glam](https://github.com/bitshifter/glam-rs) <img src="https://img.shields.io/github/stars/bitshifter/glam-rs?style=social"/> : A simple and fast 3D math library for games and graphics.

    - [faer](https://github.com/sarah-ek/faer-rs) <img src="https://img.shields.io/github/stars/sarah-ek/faer-rs?style=social"/> : Linear algebra foundation for the Rust programming language. [faer-rs.github.io](https://faer-rs.github.io/). faer is a collection of crates that implement low level linear algebra routines in pure Rust. The aim is to eventually provide a fully featured library for linear algebra with focus on portability, correctness, and performance.

    - [rust-numpy](https://github.com/PyO3/rust-numpy) <img src="https://img.shields.io/github/stars/PyO3/rust-numpy?style=social"/> : PyO3-based Rust bindings of the NumPy C-API.

    - [cgmath](https://github.com/rustgd/cgmath) <img src="https://img.shields.io/github/stars/rustgd/cgmath?style=social"/> : A linear algebra and mathematics library for computer graphics.

    - [ultraviolet](https://github.com/fu5ha/ultraviolet) <img src="https://img.shields.io/github/stars/fu5ha/ultraviolet?style=social"/> : A wide linear algebra crate for games and graphics.

    - [vek](https://github.com/yoanlcq/vek) <img src="https://img.shields.io/github/stars/yoanlcq/vek?style=social"/> : Generic 2D-3D math swiss army knife for game engines, with SIMD support and focus on convenience.

    - [static-math](https://github.com/elsuizo/static-math) <img src="https://img.shields.io/github/stars/elsuizo/static-math?style=social"/> : Safe and fast mathematical operations with static arrays in the Rust programming language.

    - [custos-math](https://github.com/elftausend/custos-math) <img src="https://img.shields.io/github/stars/elftausend/custos-math?style=social"/> : This crate provides CUDA, OpenCL, CPU (and Stack) based matrix operations using [custos](https://github.com/elftausend/custos).

    - [bluss/matrixmultiply](https://github.com/bluss/matrixmultiply) <img src="https://img.shields.io/github/stars/bluss/matrixmultiply?style=social"/> : General matrix multiplication of f32 and f64 matrices in Rust. Supports matrices with general strides. [docs.rs/matrixmultiply/](https://docs.rs/matrixmultiply/latest/matrixmultiply/)



  - ### Lie Groups

    - [sophus-rs](https://github.com/strasdat/sophus-rs) <img src="https://img.shields.io/github/stars/strasdat/sophus-rs?style=social"/> : Rust bindings for the C++ implementation of Lie Groups using Eigen.




  - ### Optimization Engine

    - [OpEn](https://github.com/alphaville/optimization-engine) <img src="https://img.shields.io/github/stars/alphaville/optimization-engine?style=social"/> : Optimization Engine (OpEn) is a solver for Fast & Accurate Embedded Optimization for next-generation Robotics and Autonomous Systems. Nonconvex embedded optimization: code generation for fast real-time optimization. [alphaville.github.io/optimization-engine/](https://alphaville.github.io/optimization-engine/)

    - [light-curve/ceres-solver-rs](https://github.com/light-curve/ceres-solver-rs) <img src="https://img.shields.io/github/stars/light-curve/ceres-solver-rs?style=social"/> : Rust bindings for [Ceres Solver](http://ceres-solver.org/).

    - [pranayspeed/g2o-rust-bindings](https://github.com/pranayspeed/g2o-rust-bindings) <img src="https://img.shields.io/github/stars/pranayspeed/g2o-rust-bindings?style=social"/> :  g2o-rust-bindings.

    - [mithi/rusty-genes](https://github.com/mithi/rusty-genes) <img src="https://img.shields.io/github/stars/mithi/rusty-genes?style=social"/> : Genetic algorithm implementation in Rust with animated visualizations in Python.





  - ### Finite Element Analysis

    - [FENRIS](https://github.com/InteractiveComputerGraphics/fenris) <img src="https://img.shields.io/github/stars/InteractiveComputerGraphics/fenris?style=social"/> : A Rust library for building advanced applications with the Finite Element Method (FEM).

    - [InteractiveComputerGraphics/higher_order_embedded_fem](https://github.com/InteractiveComputerGraphics/higher_order_embedded_fem) <img src="https://img.shields.io/github/stars/InteractiveComputerGraphics/higher_order_embedded_fem?style=social"/> : Source code for our paper "Higher-order finite elements for embedded simulation".


  - ### Data Analysis and Visualization

    - [Polars](https://github.com/pola-rs/polars) <img src="https://img.shields.io/github/stars/pola-rs/polars?style=social"/> : [Polars](https://www.pola.rs/). Fast multi-threaded, hybrid-out-of-core DataFrame library in Rust | Python | Node.js.

    - [Lance](https://github.com/eto-ai/lance) <img src="https://img.shields.io/github/stars/eto-ai/lance?style=social"/> : Lance: modern columnar data format for ML. Convert from parquet in 2-lines of code for 100x faster random access, a vector index, data versioning, and more. Compatible with pandas, duckdb, polars, pyarrow, with more integrations on the way. [eto-ai.github.io/lance/](https://eto-ai.github.io/lance/)

    - [Plotters](https://github.com/plotters-rs/plotters) <img src="https://img.shields.io/github/stars/plotters-rs/plotters?style=social"/> : A rust drawing library for high quality data plotting for both WASM and native, statically and realtimely 🦀 📈🚀

    - [Typst](https://github.com/typst/typst) <img src="https://img.shields.io/github/stars/typst/typst?style=social"/> : A new markup-based typesetting system that is powerful and easy to learn. Typst is a new markup-based typesetting system that is designed to be as powerful as LaTeX while being much easier to learn and use.  [typst.app](https://typst.app/).

    - [Rerun](https://github.com/rerun-io/rerun) <img src="https://img.shields.io/github/stars/rerun-io/rerun?style=social"/> : Rerun: Visualization infrastructure for computer vision. Log images, point clouds, etc, and visualize them effortlessly. Built in Rust using egui. [rerun.io](https://www.rerun.io/)

    - [Charming](https://github.com/yuankunzhang/charming) <img src="https://img.shields.io/github/stars/yuankunzhang/charming?style=social"/> : A visualization library for Rust.




## Machine Learning

  - ### Machine Learning Framework

    - [Candle](https://github.com/huggingface/candle) <img src="https://img.shields.io/github/stars/huggingface/candle?style=social"/> : Minimalist ML framework for Rust.

    - [Tokenizers](https://github.com/huggingface/tokenizers) <img src="https://img.shields.io/github/stars/huggingface/tokenizers?style=social"/> : 💥 Fast State-of-the-Art Tokenizers optimized for Research and Production. [huggingface.co/docs/tokenizers](https://huggingface.co/docs/tokenizers/index)

    - [Safetensors](https://github.com/huggingface/safetensors) <img src="https://img.shields.io/github/stars/huggingface/safetensors?style=social"/> : Simple, safe way to store and distribute tensors. [huggingface.co/docs/safetensors](https://huggingface.co/docs/safetensors/index)

    - [Burn](https://github.com/burn-rs/burn) <img src="https://img.shields.io/github/stars/burn-rs/burn?style=social"/> : Burn - A Flexible and Comprehensive Deep Learning Framework in Rust. [burn-rs.github.io/](https://burn-rs.github.io/)

    - [TensorFlow Rust](https://github.com/tensorflow/rust) <img src="https://img.shields.io/github/stars/tensorflow/rust?style=social"/> : Rust language bindings for TensorFlow.

    - [tch-rs](https://github.com/LaurentMazare/tch-rs) <img src="https://img.shields.io/github/stars/LaurentMazare/tch-rs?style=social"/> : Rust bindings for the C++ api of PyTorch.


    - [dfdx](https://github.com/coreylowman/dfdx) <img src="https://img.shields.io/github/stars/coreylowman/dfdx?style=social"/> : Deep learning in Rust, with shape checked tensors and neural networks.

    - [tract](https://github.com/sonos/tract) <img src="https://img.shields.io/github/stars/sonos/tract?style=social"/> : Sonos' Neural Network inference engine. Tiny, no-nonsense, self-contained, Tensorflow and ONNX inference

    - [ort](https://github.com/pykeio/ort) <img src="https://img.shields.io/github/stars/pykeio/ort?style=social"/> : A Rust wrapper for ONNX Runtime. [docs.rs/ort](https://docs.rs/ort/latest/ort/)

    - [arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) <img src="https://img.shields.io/github/stars/arrayfire/arrayfire-rust?style=social"/> : Rust wrapper for [ArrayFire](https://github.com/arrayfire/arrayfire). [ArrayFire](https://github.com/arrayfire/arrayfire) is a high performance library for parallel computing with an easy-to-use API. It enables users to write scientific computing code that is portable across CUDA, OpenCL and CPU devices.

    - [Linfa](https://github.com/rust-ml/linfa) <img src="https://img.shields.io/github/stars/rust-ml/linfa?style=social"/> : A Rust machine learning framework. Linfa aims to provide a comprehensive toolkit to build Machine Learning applications with Rust.

    - [Juice](https://github.com/spearow/juice) <img src="https://img.shields.io/github/stars/spearow/juice?style=social"/> : The Hacker's Machine Learning Engine.

    - [autograph](https://github.com/charles-r-earp/autograph) <img src="https://img.shields.io/github/stars/charles-r-earp/autograph?style=social"/> : A machine learning library for Rust.

    - [SmartCore](https://github.com/smartcorelib/smartcore) <img src="https://img.shields.io/github/stars/smartcorelib/smartcore?style=social"/> : The most advanced machine learning library in Rust. SmartCore is a comprehensive library for machine learning and numerical computing. The library provides a set of tools for linear algebra, numerical computing, optimization, and enables a generic, powerful yet still efficient approach to machine learning. [smartcorelib.org/](https://smartcorelib.org/)

    - [onnxruntime-rs](https://github.com/nbigaouette/onnxruntime-rs) <img src="https://img.shields.io/github/stars/nbigaouette/onnxruntime-rs?style=social"/> : This is an attempt at a Rust wrapper for [Microsoft's ONNX Runtime](https://github.com/microsoft/onnxruntime) (version 1.8).

    - [Wonnx](https://github.com/webonnx/wonnx) <img src="https://img.shields.io/github/stars/webonnx/wonnx?style=social"/> : Wonnx is a GPU-accelerated ONNX inference run-time written 100% in Rust, ready for the web.

    - [altius](https://github.com/maekawatoshiki/altius) <img src="https://img.shields.io/github/stars/maekawatoshiki/altius?style=social"/> : Small ONNX inference runtime written in Rust.

    - [goldstraw/RustCNN](https://github.com/goldstraw/RustCNN) <img src="https://img.shields.io/github/stars/goldstraw/RustCNN?style=social"/> : Rust convolutional neural network from scratch.

    - [goldstraw/RustTransformer](https://github.com/goldstraw/RustTransformer) <img src="https://img.shields.io/github/stars/goldstraw/RustTransformer?style=social"/> : A transformer built from scratch in Rust.

    - [elftausend/gradients](https://github.com/elftausend/gradients) <img src="https://img.shields.io/github/stars/elftausend/gradients?style=social"/> : Deep Learning library using [custos](https://github.com/elftausend/custos) and [custos-math](https://github.com/elftausend/custos-math).

    - [michaelmelanson/spiking-neural-net](https://github.com/michaelmelanson/spiking-neural-net) <img src="https://img.shields.io/github/stars/michaelmelanson/spiking-neural-net?style=social"/> : A spiking neural network simulation library.

    - [AnicetNgrt/neural_networks_rust](https://github.com/AnicetNgrt/neural_networks_rust) <img src="https://img.shields.io/github/stars/AnicetNgrt/neural_networks_rust?style=social"/> : Implementing NNs & other machine learning utils in Rust from scratch.

    - [herrmann/rustorch](https://github.com/herrmann/rustorch) <img src="https://img.shields.io/github/stars/herrmann/rustorch?style=social"/> : "PyTorch in Rust".

    - [michaelgiba/ggml-rs](https://github.com/michaelgiba/ggml-rs) <img src="https://img.shields.io/github/stars/michaelgiba/ggml-rs?style=social"/> : Work in progress rust bindings to ggml.

    - [KerfuffleV2/ggml-sys-bleedingedge](https://github.com/KerfuffleV2/ggml-sys-bleedingedge) <img src="https://img.shields.io/github/stars/KerfuffleV2/ggml-sys-bleedingedge?style=social"/> : Bleeding edge low level Rust binding for GGML.

    - [PABannier/rust-ggml](https://github.com/PABannier/rust-ggml) <img src="https://img.shields.io/github/stars/PABannier/rust-ggml?style=social"/> : Rust bindings for C tensor library ggml.

    - [KerfuffleV2/rusty-ggml](https://github.com/KerfuffleV2/rusty-ggml) <img src="https://img.shields.io/github/stars/KerfuffleV2/rusty-ggml?style=social"/> : GGML bindings that aim to be idiomatic Rust rather than directly corresponding to the C/C++ interface.

    - [danforbes/ggml-rs-bindings](https://github.com/danforbes/ggml-rs-bindings) <img src="https://img.shields.io/github/stars/danforbes/ggml-rs-bindings?style=social"/> : This is a personal educational project for learning more about [rustformers/llm](https://github.com/rustformers/llm), from which almost all of the code in this repository was copied.

    - [kurtschelfthout/tensorken](https://github.com/kurtschelfthout/tensorken) <img src="https://img.shields.io/github/stars/kurtschelfthout/tensorken?style=social"/> : A fun, hackable, GPU-accelerated, neural network library in Rust, written by an idiot.

    - [Orion](https://github.com/gizatechxyz/orion) <img src="https://img.shields.io/github/stars/gizatechxyz/orion?style=social"/> : Orion: An Open-source Framework for Validity and ZK ML ✨. ONNX Runtime in Cairo 1.0 for verifiable ML inference using STARK. [orion.gizatech.xyz](https://orion.gizatech.xyz/)

    - [franalgaba/neural-network-cairo](https://github.com/franalgaba/neural-network-cairo) <img src="https://img.shields.io/github/stars/franalgaba/neural-network-cairo?style=social"/> : Neural Network implementation from scratch for MNIST using Cairo 1.0.

    - [raphaelDkhn/cairo_ml](https://github.com/raphaelDkhn/cairo_ml) <img src="https://img.shields.io/github/stars/raphaelDkhn/cairo_ml?style=social"/> : Build neural network models in Cairo 1.0.





​
  - ### Large Language Model

    - [phodal/aigc](https://github.com/phodal/aigc) <img src="https://img.shields.io/github/stars/phodal/aigc?style=social"/> : 《构筑大语言模型应用：应用开发与架构设计》一本关于 LLM 在真实世界应用的开源电子书，介绍了大语言模型的基础知识和应用，以及如何构建自己的模型。其中包括Prompt的编写、开发和管理，探索最好的大语言模型能带来什么，以及LLM应用开发的模式和架构设计。

    - [llama2.rs](https://github.com/srush/llama2.rs) <img src="https://img.shields.io/github/stars/srush/llama2.rs?style=social"/> : A fast llama2 decoder in pure Rust.

    - [Llama2-burn](https://github.com/Gadersd/llama2-burn) <img src="https://img.shields.io/github/stars/Gadersd/llama2-burn?style=social"/> : Llama2 LLM ported to Rust burn.

    - [gaxler/llama2.rs](https://github.com/gaxler/llama2.rs) <img src="https://img.shields.io/github/stars/gaxler/llama2.rs?style=social"/> : Inference Llama 2 in one file of pure Rust 🦀

    - [whisper-burn](https://github.com/Gadersd/whisper-burn) <img src="https://img.shields.io/github/stars/Gadersd/whisper-burn?style=social"/> : A Rust implementation of OpenAI's Whisper model using the burn framework.

    - [stable-diffusion-burn](https://github.com/Gadersd/stable-diffusion-burn) <img src="https://img.shields.io/github/stars/Gadersd/stable-diffusion-burn?style=social"/> : Stable Diffusion v1.4 ported to Rust's burn framework.

    - [coreylowman/llama-dfdx](https://github.com/coreylowman/llama-dfdx) <img src="https://img.shields.io/github/stars/coreylowman/llama-dfdx?style=social"/> : [LLaMa 7b](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/) with CUDA acceleration implemented in rust. Minimal GPU memory needed!

    - [tazz4843/whisper-rs](https://github.com/tazz4843/whisper-rs) <img src="https://img.shields.io/github/stars/tazz4843/whisper-rs?style=social"/> : Rust bindings to [whisper.cpp](https://github.com/ggerganov/whisper.cpp).

    - [rustformers/llm](https://github.com/rustformers/llm) <img src="https://img.shields.io/github/stars/rustformers/llm?style=social"/> : Run inference for Large Language Models on CPU, with Rust 🦀🚀🦙.

    - [Chidori](https://github.com/ThousandBirdsInc/chidori) <img src="https://img.shields.io/github/stars/ThousandBirdsInc/chidori?style=social"/> : A reactive runtime for building durable AI agents. [docs.thousandbirds.ai](https://docs.thousandbirds.ai/).

    - [llm-chain](https://github.com/sobelio/llm-chain) <img src="https://img.shields.io/github/stars/sobelio/llm-chain?style=social"/> : llm-chain is a collection of Rust crates designed to help you work with Large Language Models (LLMs) more effectively. [llm-chain.xyz](https://llm-chain.xyz/)

    - [Atome-FE/llama-node](https://github.com/Atome-FE/llama-node) <img src="https://img.shields.io/github/stars/Atome-FE/llama-node?style=social"/> : Believe in AI democratization. llama for nodejs backed by llama-rs and llama.cpp, work locally on your laptop CPU. support llama/alpaca/gpt4all/vicuna model. [www.npmjs.com/package/llama-node](https://www.npmjs.com/package/llama-node)

    - [Noeda/rllama](https://github.com/Noeda/rllama) <img src="https://img.shields.io/github/stars/Noeda/rllama?style=social"/> : Rust+OpenCL+AVX2 implementation of LLaMA inference code.

    - [lencx/ChatGPT](https://github.com/lencx/ChatGPT) <img src="https://img.shields.io/github/stars/lencx/ChatGPT?style=social"/> : 🔮 ChatGPT Desktop Application (Mac, Windows and Linux). [NoFWL](https://app.nofwl.com/).

    - [Synaptrix/ChatGPT-Desktop](https://github.com/Synaptrix/ChatGPT-Desktop) <img src="https://img.shields.io/github/stars/Synaptrix/ChatGPT-Desktop?style=social"/> : Fuel your productivity with ChatGPT-Desktop - Blazingly fast and supercharged!

    - [Poordeveloper/chatgpt-app](https://github.com/Poordeveloper/chatgpt-app) <img src="https://img.shields.io/github/stars/Poordeveloper/chatgpt-app?style=social"/> : A ChatGPT App for all platforms. Built with Rust + Tauri + Vue + Axum.

    - [mxismean/chatgpt-app](https://github.com/mxismean/chatgpt-app) <img src="https://img.shields.io/github/stars/mxismean/chatgpt-app?style=social"/> : Tauri 项目：ChatGPT App.

    - [sonnylazuardi/chat-ai-desktop](https://github.com/sonnylazuardi/chat-ai-desktop) <img src="https://img.shields.io/github/stars/sonnylazuardi/chat-ai-desktop?style=social"/> : Chat AI Desktop App. Unofficial ChatGPT desktop app for Mac & Windows menubar using Tauri & Rust.

    - [yetone/openai-translator](https://github.com/yetone/openai-translator) <img src="https://img.shields.io/github/stars/yetone/openai-translator?style=social"/> : The translator that does more than just translation - powered by OpenAI.

    - [m1guelpf/browser-agent](https://github.com/m1guelpf/browser-agent) <img src="https://img.shields.io/github/stars/m1guelpf/browser-agent?style=social"/> : A browser AI agent, using GPT-4. [docs.rs/browser-agent](https://docs.rs/browser-agent/latest/browser_agent/)

    - [sigoden/aichat](https://github.com/sigoden/aichat) <img src="https://img.shields.io/github/stars/sigoden/aichat?style=social"/> : Using ChatGPT/GPT-3.5/GPT-4 in the terminal.

    - [uiuifree/rust-openai-chatgpt-api](https://github.com/uiuifree/rust-openai-chatgpt-api) <img src="https://img.shields.io/github/stars/uiuifree/rust-openai-chatgpt-api?style=social"/> : "rust-openai-chatgpt-api" is a Rust library for accessing the ChatGPT API, a powerful NLP platform by OpenAI. The library provides a simple and efficient interface for sending requests and receiving responses, including chat. It uses reqwest and serde for HTTP requests and JSON serialization.

    - [1595901624/gpt-aggregated-edition](https://github.com/1595901624/gpt-aggregated-edition) <img src="https://img.shields.io/github/stars/1595901624/gpt-aggregated-edition?style=social"/> : 聚合ChatGPT官方版、ChatGPT免费版、文心一言、Poe、chatchat等多平台，支持自定义导入平台。

    - [Cormanz/smartgpt](https://github.com/Cormanz/smartgpt) <img src="https://img.shields.io/github/stars/Cormanz/smartgpt?style=social"/> : A program that provides LLMs with the ability to complete complex tasks using plugins.

    - [femtoGPT](https://github.com/keyvank/femtoGPT) <img src="https://img.shields.io/github/stars/keyvank/femtoGPT?style=social"/> : femtoGPT is a pure Rust implementation of a minimal Generative Pretrained Transformer. [discord.gg/wTJFaDVn45](https://github.com/keyvank/femtoGPT)

    - [shafishlabs/llmchain-rs](https://github.com/shafishlabs/llmchain-rs) <img src="https://img.shields.io/github/stars/shafishlabs/llmchain-rs?style=social"/> : 🦀Rust + Large Language Models - Make AI Services Freely and Easily. Inspired by LangChain.

    - [flaneur2020/llama2.rs](https://github.com/flaneur2020/llama2.rs) <img src="https://img.shields.io/github/stars/flaneur2020/llama2.rs?style=social"/> : An rust reimplementatin of [https://github.com/karpathy/llama2.c](https://github.com/karpathy/llama2.c).





  - ### Stable Diffusion

    - [pykeio/diffusers](https://github.com/pykeio/diffusers) <img src="https://img.shields.io/github/stars/pykeio/diffusers?style=social"/> : modular Rust library for optimized Stable Diffusion inference 🔮 [docs.rs/pyke-diffusers](https://docs.rs/pyke-diffusers/latest/pyke_diffusers/)





  - ### Object Detection

    - [sjinzh/yolov5-rs-app](https://github.com/sjinzh/yolov5-rs-app) <img src="https://img.shields.io/github/stars/sjinzh/yolov5-rs-app?style=social"/> : A inference framework with GUI for YOLOv5 written in Rust.

    - [pnn](https://github.com/ptaxom/pnn) <img src="https://img.shields.io/github/stars/ptaxom/pnn?style=social"/> : pnn is [Darknet](https://github.com/alexeyAB/darknet) compatible neural nets inference engine implemented in Rust. By optimizing was achieved significant performance increment(especially in FP16 mode). pnn provide CUDNN-based and TensorRT-based inference engines.

    - [bencevans/rust-opencv-yolov5](https://github.com/bencevans/rust-opencv-yolov5) <img src="https://img.shields.io/github/stars/bencevans/rust-opencv-yolov5?style=social"/> : YOLOv5 Inference with ONNX & OpenCV in Rust.

    - [masc-it/yolov5-api-rust](https://github.com/masc-it/yolov5-api-rust) <img src="https://img.shields.io/github/stars/masc-it/yolov5-api-rust?style=social"/> : Rust API to run predictions with YoloV5 models.

    - [AndreyGermanov/yolov8_onnx_rust](https://github.com/AndreyGermanov/yolov8_onnx_rust) <img src="https://img.shields.io/github/stars/AndreyGermanov/yolov8_onnx_rust?style=social"/> : YOLOv8 inference using Rust.

    - [igor-yusupov/rusty-yolo](https://github.com/igor-yusupov/rusty-yolo) <img src="https://img.shields.io/github/stars/igor-yusupov/rusty-yolo?style=social"/> : rusty-yolo.

    - [gsuyemoto/yolo-rust](https://github.com/gsuyemoto/yolo-rust) <img src="https://img.shields.io/github/stars/gsuyemoto/yolo-rust?style=social"/> : Run YOLO computer vision model using Rust and OpenCV and/or Torch.

    - [alianse777/darknet-rust](https://github.com/alianse777/darknet-rust) <img src="https://img.shields.io/github/stars/alianse777/darknet-rust?style=social"/> : A Rust wrapper for Darknet, an open source neural network framework written in C and CUDA. [pjreddie.com/darknet/](https://pjreddie.com/darknet/)

    - [12101111/yolo-rs](https://github.com/12101111/yolo-rs) <img src="https://img.shields.io/github/stars/12101111/yolo-rs?style=social"/> : Yolov3 & Yolov4 with TVM and rust.

    - [TKGgunter/yolov4_tiny_rs](https://github.com/TKGgunter/yolov4_tiny_rs) <img src="https://img.shields.io/github/stars/TKGgunter/yolov4_tiny_rs?style=social"/> : A rust implementation of yolov4_tiny algorithm.

    - [flixstn/You-Only-Look-Once](https://github.com/flixstn/You-Only-Look-Once) <img src="https://img.shields.io/github/stars/flixstn/You-Only-Look-Once?style=social"/> : A Rust implementation of Yolo for object detection and tracking.

    - [lenna-project/yolo-plugin](https://github.com/lenna-project/yolo-plugin) <img src="https://img.shields.io/github/stars/lenna-project/yolo-plugin?style=social"/> : Yolo Object Detection Plugin for Lenna.

    - [laclouis5/globox-rs](https://github.com/laclouis5/globox-rs) <img src="https://img.shields.io/github/stars/laclouis5/globox-rs?style=social"/> : Object detection toolbox for parsing, converting and evaluating bounding box annotations.

    - [metobom/tchrs-opencv-webcam-inference](https://github.com/metobom/tchrs-opencv-webcam-inference) <img src="https://img.shields.io/github/stars/metobom/tchrs-opencv-webcam-inference?style=social"/> : This example shows steps for running a Python trained model on webcam feed with opencv and tch-rs. Model will run on GPU.






## Design Pattern

  - [fadeevab/design-patterns-rust](https://github.com/fadeevab/design-patterns-rust) <img src="https://img.shields.io/github/stars/fadeevab/design-patterns-rust?style=social"/> : Rust examples for all 23 classic GoF design patterns, and even a little more.

  - [lpxxn/rust-design-pattern](https://github.com/lpxxn/rust-design-pattern) <img src="https://img.shields.io/github/stars/lpxxn/rust-design-pattern?style=social"/> : Rust Design Patterns.



## Static Variables

  - [typed-arena](https://github.com/rust-lang-nursery/lazy-static.rs) <img src="https://img.shields.io/github/stars/rust-lang-nursery/lazy-static.rs?style=social"/> : A small macro for defining lazy evaluated static variables in Rust.




## Memory Allocator

  - [typed-arena](https://github.com/thomcc/rust-typed-arena) <img src="https://img.shields.io/github/stars/thomcc/rust-typed-arena?style=social"/> : A fast (but limited) allocation arena for values of a single type.

  - [bumpalo](https://github.com/fitzgen/bumpalo) <img src="https://img.shields.io/github/stars/fitzgen/bumpalo?style=social"/> : A fast bump allocation arena for Rust. [docs.rs/bumpalo](https://docs.rs/bumpalo/latest/bumpalo/)

  - [generational-arena](https://github.com/fitzgen/generational-arena) <img src="https://img.shields.io/github/stars/fitzgen/generational-arena?style=social"/> : A safe arena allocator that allows deletion without suffering from the ABA problem by using generational indices. [docs.rs/generational-arena](https://docs.rs/generational-arena/latest/generational_arena/)

  - [tikv/jemallocator](https://github.com/tikv/jemallocator) <img src="https://img.shields.io/github/stars/tikv/jemallocator?style=social"/> : Rust allocator using jemalloc as a backend.













## Embedded Development

  - [stm32-rs](https://github.com/stm32-rs) : Community Rust support projects for STM32 microcontrollers.

  - [rust-embedded](https://github.com/rust-embedded) : Enabling usage of Rust on Embedded Platforms (Embedded Linux / RTOS / Bare Metal).

  - [RTIC](https://github.com/rtic-rs/rtic) <img src="https://img.shields.io/github/stars/rtic-rs/rtic?style=social"/> : Real-Time Interrupt-driven Concurrency (RTIC) framework for ARM Cortex-M microcontrollers. [rtic.rs](https://rtic.rs/)

  - [Embassy](https://github.com/embassy-rs/embassy) <img src="https://img.shields.io/github/stars/embassy-rs/embassy?style=social"/> : Modern embedded framework, using Rust and async. [embassy.dev](https://embassy.dev/)

  - [rust-raspberrypi-OS-tutorials](https://github.com/rust-embedded/rust-raspberrypi-OS-tutorials) <img src="https://img.shields.io/github/stars/rust-embedded/rust-raspberrypi-OS-tutorials?style=social"/> :  📚 Learn to write an embedded OS in Rust 🦀

  - [Tock](https://github.com/tock/tock) <img src="https://img.shields.io/github/stars/tock/tock?style=social"/> : A secure embedded operating system for microcontrollers. [www.tockos.org](https://www.tockos.org/)

  - [lobaro/FreeRTOS-rust](https://github.com/lobaro/FreeRTOS-rust) <img src="https://img.shields.io/github/stars/lobaro/FreeRTOS-rust?style=social"/> : This project is based on code from [freertos.rs](https://github.com/hashmismatch/freertos.rs) and some additions to simplify the usage of [FreeRTOS](https://github.com/FreeRTOS/FreeRTOS-Kernel) in embedded applications written in Rust.

  - [Exein-io/pulsar](https://github.com/Exein-io/pulsar) <img src="https://img.shields.io/github/stars/Exein-io/pulsar?style=social"/> : A modular and blazing fast runtime security framework for the IoT, powered by eBPF. [pulsar.sh](https://pulsar.sh/)





## General Operating System

  - [BlogOS](https://github.com/phil-opp/blog_os) <img src="https://img.shields.io/github/stars/phil-opp/blog_os?style=social"/> : This repository contains the source code for the Writing an OS in Rust series at [os.phil-opp.com](https://os.phil-opp.com/).

  - [rCore-Tutorial-v3](https://github.com/chyyuu/os_kernel_lab) <img src="https://img.shields.io/github/stars/chyyuu/os_kernel_lab?style=social"/> : OS kernel labs based on Rust/C Lang & RISC-V 64/X86-32.

  - [rCore](https://github.com/rcore-os/rCore) <img src="https://img.shields.io/github/stars/rcore-os/rCore?style=social"/> : Rust version of THU uCore OS. Linux compatible.

  - [zCore](https://github.com/rcore-os/zCore) <img src="https://img.shields.io/github/stars/rcore-os/zCore?style=social"/> : Reimplement Zircon microkernel in Rust.

  - [RustSBI](https://github.com/rustsbi/rustsbi) <img src="https://img.shields.io/github/stars/rustsbi/rustsbi?style=social"/> : RISC-V Supervisor Binary Interface (RISC-V SBI) implementation library in Rust; runs on M or HS mode; good support for embedded Rust ecosystem.

  - [writing-an-os-in-rust](https://github.com/rustcc/writing-an-os-in-rust) <img src="https://img.shields.io/github/stars/rustcc/writing-an-os-in-rust?style=social"/> : 《使用Rust编写操作系统》

  - [Theseus](https://github.com/theseus-os/Theseus) <img src="https://img.shields.io/github/stars/theseus-os/Theseus?style=social"/> : Theseus is a modern OS written from scratch in Rust that explores 𝐢𝐧𝐭𝐫𝐚𝐥𝐢𝐧𝐠𝐮𝐚𝐥 𝐝𝐞𝐬𝐢𝐠𝐧, novel OS structure, and state management.

  - [snarkOS](https://github.com/AleoHQ/snarkOS) <img src="https://img.shields.io/github/stars/AleoHQ/snarkOS?style=social"/> : A Decentralized Operating System for Zero-Knowledge Applications.

  - [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) <img src="https://img.shields.io/github/stars/thepowersgang/rust_os?style=social"/> : An OS kernel written in rust. Non POSIX.

  - [MOROS](https://github.com/vinc/moros) <img src="https://img.shields.io/github/stars/vinc/moros?style=social"/> : MOROS: Obscure Rust Operating System 🦉

  - [EuraliOS](https://github.com/bendudson/EuraliOS) <img src="https://img.shields.io/github/stars/bendudson/EuraliOS?style=social"/> : A hobby x86-64 operating system written in Rust.

  - [SIMDeez](https://github.com/arduano/simdeez) <img src="https://img.shields.io/github/stars/arduano/simdeez?style=social"/> : A library that abstracts over SIMD instruction sets, including ones with differing widths. SIMDeez is designed to allow you to write a function one time and produce SSE2, SSE41, and AVX2 versions of the function.

  - [yavkOS](https://github.com/yavko/yavkOS) <img src="https://img.shields.io/github/stars/yavko/yavkOS?style=social"/> : Operating system based off of blog_os, with the goal of running wasm modules as executables.

  - [Felix OS](https://github.com/mrgian/felix) <img src="https://img.shields.io/github/stars/mrgian/felix?style=social"/> : 🐱 x86 operating system. Felix is my attempt at writing an x86 operating system. It's written completely from scratch in Rust and doesn't use any external dependencies.

  - [jdreaver/rust-os](https://github.com/jdreaver/rust-os) <img src="https://img.shields.io/github/stars/jdreaver/rust-os?style=social"/> : Creating a bare metal OS in Rust.

  - [r9os/r9](https://github.com/r9os/r9) <img src="https://img.shields.io/github/stars/r9os/r9?style=social"/> : The R9 operating system.




## Robot Operating System

  - [micro-ROS for Arduino](https://github.com/micro-ROS/micro_ros_arduino) <img src="https://img.shields.io/github/stars/micro-ROS/micro_ros_arduino?style=social"/> : micro-ROS library for Arduino.

  - [openrr](https://github.com/openrr/openrr) <img src="https://img.shields.io/github/stars/openrr/openrr?style=social"/> : Open Rust Robotics. OpenRR (pronounced like "opener") is Open Rust Robotics platform.

  - [rosrust](https://github.com/adnanademovic/rosrust) <img src="https://img.shields.io/github/stars/adnanademovic/rosrust?style=social"/> : rosrust is a pure Rust implementation of a [ROS](https://www.ros.org/) client library.

  - [ros2_rust](https://github.com/ros2-rust/ros2_rust) <img src="https://img.shields.io/github/stars/ros2-rust/ros2_rust?style=social"/> : Rust bindings for ROS2.

  - [r2r](https://github.com/sequenceplanner/r2r) <img src="https://img.shields.io/github/stars/sequenceplanner/r2r?style=social"/> : R2R - Easy to use, runtime-agnostic, async rust bindings for ROS2.

  - [erdos](https://github.com/erdos-project/erdos) <img src="https://img.shields.io/github/stars/erdos-project/erdos?style=social"/> : Dataflow system for building self-driving car and robotics applications.

  - [rclrust](https://github.com/rclrust/rclrust) <img src="https://img.shields.io/github/stars/rclrust/rclrust?style=social"/> : This is yet another ROS2 client library written in Rust.

  - [RustDDS](https://github.com/jhelovuo/RustDDS) <img src="https://img.shields.io/github/stars/jhelovuo/RustDDS?style=social"/> : [RustDDS](https://atostek.com/en/products/rustdds/) is a pure Rust implementation of [Data Distribution Service](https://www.omg.org/spec/DDS/), developed by [Atostek Oy](https://atostek.com/en/).

  - [ros2-client](https://github.com/jhelovuo/ros2-client) <img src="https://img.shields.io/github/stars/jhelovuo/ros2-client?style=social"/> : ROS2 client library based on RustDDS.

  - [rosbag-rs](https://github.com/SkoltechRobotics/rosbag-rs) <img src="https://img.shields.io/github/stars/SkoltechRobotics/rosbag-rs?style=social"/> : A pure Rust crate for reading ROS bag files.

  - [rustros_tf](https://github.com/arjo129/rustros_tf) <img src="https://img.shields.io/github/stars/arjo129/rustros_tf?style=social"/> : This is a rust port of the [ROS tf library](http://wiki.ros.org/tf).

  - [urdf-rs](https://github.com/openrr/urdf-rs) <img src="https://img.shields.io/github/stars/openrr/urdf-rs?style=social"/> : [URDF](http://wiki.ros.org/urdf) parser using [serde-xml-rs](https://github.com/RReverser/serde-xml-rs) for rust.

  - [urdf-viz](https://github.com/openrr/urdf-viz) <img src="https://img.shields.io/github/stars/openrr/urdf-viz?style=social"/> : visualize URDF/XACRO file, URDF Viewer works on Windows/MacOS/Linux.

  - [ros-nalgebra](https://github.com/openrr/ros-nalgebra) <img src="https://img.shields.io/github/stars/openrr/ros-nalgebra?style=social"/> : Generate code to convert geometry_msgs into nalgebra structs, for [rosrust](https://github.com/adnanademovic/rosrust).

  - [strawlab/opencv-ros-camera](https://github.com/strawlab/opencv-ros-camera) <img src="https://img.shields.io/github/stars/strawlab/opencv-ros-camera?style=social"/> : Geometric models of OpenCV/ROS cameras for photogrammetry.

  - [luickk/MinimalRoboticsPlatform](https://github.com/luickk/MinimalRoboticsPlatform/tree/rust_code) <img src="https://img.shields.io/github/stars/luickk/MinimalRoboticsPlatform?style=social"/> : MRP is a minimal microkernel that supports the most fundamental robotic domains. It's thought for highly integrated robotics development.

  - [newpavlov/rosbag-rs](https://github.com/newpavlov/rosbag-rs) <img src="https://img.shields.io/github/stars/newpavlov/rosbag-rs?style=social"/> : A pure Rust crate for reading ROS bag files.




## Hardware Description Language

  - [Veryl](https://github.com/dalance/veryl) <img src="https://img.shields.io/github/stars/dalance/veryl?style=social"/> : Veryl: A Modern Hardware Description Language.

  - [RustHDL](https://github.com/samitbasu/rust-hdl) <img src="https://img.shields.io/github/stars/samitbasu/rust-hdl?style=social"/> : A framework for writing FPGA firmware using the Rust Programming Language.

  - [VHDL-LS/rust_hdl](https://github.com/VHDL-LS/rust_hdl) <img src="https://img.shields.io/github/stars/VHDL-LS/rust_hdl?style=social"/> : This repository contains a fast VHDL language server and analysis library written in Rust.

  - [yupferris/kaze](https://github.com/yupferris/kaze) <img src="https://img.shields.io/github/stars/yupferris/kaze?style=social"/> : An [HDL](https://en.wikipedia.org/wiki/Hardware_description_language) embedded in Rust. kaze provides an API to describe Modules composed of Signals, which can then be used to generate Rust simulator code or Verilog modules.

  - [dalance/sv-parser](https://github.com/dalance/sv-parser) <img src="https://img.shields.io/github/stars/dalance/sv-parser?style=social"/> : SystemVerilog parser library fully compliant with IEEE 1800-2017.

  - [dalance/svls](https://github.com/dalance/svls) <img src="https://img.shields.io/github/stars/dalance/svls?style=social"/> : SystemVerilog language server.

  - [dalance/svlint](https://github.com/dalance/svlint) <img src="https://img.shields.io/github/stars/dalance/svlint?style=social"/> : SystemVerilog linter.

  - [vivekmalneedi/veridian](https://github.com/vivekmalneedi/veridian) <img src="https://img.shields.io/github/stars/vivekmalneedi/veridian?style=social"/> : A SystemVerilog Language Server.

  - [zachjs/sv2v](https://github.com/zachjs/sv2v) <img src="https://img.shields.io/github/stars/zachjs/sv2v?style=social"/> : SystemVerilog to Verilog conversion.








## Logic Programming

  - [Scryer Prolog](https://github.com/mthom/scryer-prolog) <img src="https://img.shields.io/github/stars/mthom/scryer-prolog?style=social"/> : A modern Prolog implementation written mostly in Rust.









## Shared Memory

  - [elast0ny/shared_memory](https://github.com/elast0ny/shared_memory) <img src="https://img.shields.io/github/stars/elast0ny/shared_memory?style=social"/> : A Rust wrapper around native shared memory for Linux and Windows.


## Remote Desktop

  - [RustDesk](https://github.com/rustdesk/rustdesk) <img src="https://img.shields.io/github/stars/rustdesk/rustdesk?style=social"/> : Virtual / remote desktop infrastructure for everyone! Open source TeamViewer / Citrix alternative. [rustdesk.com](https://rustdesk.com).



## Date and Time

  - [Chrono](https://github.com/chronotope/chrono) <img src="https://img.shields.io/github/stars/chronotope/chrono?style=social"/> : [Chrono](https://docs.rs/chrono/latest/chrono/): Date and Time for Rust.



## Data Encryption

  - [rustic](https://github.com/rustic-rs/rustic) <img src="https://img.shields.io/github/stars/rustic-rs/rustic?style=social"/> : rustic - fast, encrypted, deduplicated backups powered by Rust.




## Database

  - [SQLx](https://github.com/launchbadge/sqlx) <img src="https://img.shields.io/github/stars/launchbadge/sqlx?style=social"/> : 🧰 The Rust SQL Toolkit. An async, pure Rust SQL crate featuring compile-time checked queries without a DSL. Supports PostgreSQL, MySQL, SQLite, and MSSQL.

  - [Qdrant](https://github.com/qdrant/qdrant) <img src="https://img.shields.io/github/stars/qdrant/qdrant?style=social"/> : Qdrant - Vector Database for the next generation of AI applications. Also available in the cloud [https://cloud.qdrant.io/](https://cloud.qdrant.io/). [qdrant.tech](https://qdrant.tech/)

  - [Rusqlite](https://github.com/rusqlite/rusqlite) <img src="https://img.shields.io/github/stars/rusqlite/rusqlite?style=social"/> : Rusqlite is an ergonomic wrapper for using SQLite from Rust.

  - [CeresDB](https://github.com/CeresDB/ceresdb) <img src="https://img.shields.io/github/stars/CeresDB/ceresdb?style=social"/> : CeresDB is a high-performance, distributed, cloud native time-series database. [docs.ceresdb.io](https://docs.ceresdb.io/)

  - [redb](https://github.com/cberner/redb) <img src="https://img.shields.io/github/stars/cberner/redb?style=social"/> : An embedded key-value database in pure Rust. [www.redb.org](https://www.redb.org/)

  - [Rustbase](https://github.com/rustbase/rustbase) <img src="https://img.shields.io/github/stars/rustbase/rustbase?style=social"/> : Rustbase is open source, lightweight, modern and fast NoSQL database. [rustbase.app/](https://www.rustbase.app/)







## Sensor and Communication Protocol

  - [WebRTC.rs](https://github.com/webrtc-rs/webrtc) <img src="https://img.shields.io/github/stars/webrtc-rs/webrtc?style=social"/> : A pure Rust implementation of WebRTC. [webrtc.rs](https://webrtc.rs/)

  - [serialport-rs](https://github.com/serialport/serialport-rs) <img src="https://img.shields.io/github/stars/serialport/serialport-rs?style=social"/> : A cross-platform serial port library in Rust. Provides a blocking I/O interface and port enumeration including USB device information.

  - [scottlamb/moonfire-nvr](https://github.com/scottlamb/moonfire-nvr) <img src="https://img.shields.io/github/stars/scottlamb/moonfire-nvr?style=social"/> : Moonfire NVR, a security camera network video recorder.

  - [l1npengtul/nokhwa](https://github.com/l1npengtul/nokhwa) <img src="https://img.shields.io/github/stars/l1npengtul/nokhwa?style=social"/> : Cross Platform Rust Library for Powerful Webcam/Camera Capture.

  - [shirok1/livox-rs](https://github.com/shirok1/livox-rs) <img src="https://img.shields.io/github/stars/shirok1/livox-rs?style=social"/> : Alternative Livox LiDAR library.

  - [jerry73204/rust-lidar-utils](https://github.com/jerry73204/rust-lidar-utils) <img src="https://img.shields.io/github/stars/jerry73204/rust-lidar-utils?style=social"/> : Encode and decode Velodyne and Ouster lidar packets in Rust.

  - [hacknus/serial-monitor-rust](https://github.com/hacknus/serial-monitor-rust) <img src="https://img.shields.io/github/stars/hacknus/serial-monitor-rust?style=social"/> : A cross-plattform serial monitor/plotter written entirely in rust.

  - [apertus-open-source-cinema/axiom-recorder](https://github.com/apertus-open-source-cinema/axiom-recorder) <img src="https://img.shields.io/github/stars/apertus-open-source-cinema/axiom-recorder?style=social"/> : Software to record moving images from Apertus° AXIOM cameras via USB3 or ethernet.

  - [cameleon-rs/cameleon](https://github.com/cameleon-rs/cameleon) <img src="https://img.shields.io/github/stars/cameleon-rs/cameleon?style=social"/> : A safe, fast, and flexible library for GenICam compatible cameras.




## Signal Processing

  - [strawlab/adskalman-rs](https://github.com/strawlab/adskalman-rs) <img src="https://img.shields.io/github/stars/strawlab/adskalman-rs?style=social"/> : Kalman filter implementation in Rust.

  - [nravic/kalmanrs](https://github.com/nravic/kalmanrs) <img src="https://img.shields.io/github/stars/nravic/kalmanrs?style=social"/> : A (yet to be) comprehensive Kalman Filter library in Rust.

  - [spdes/kalman-rust](https://github.com/spdes/kalman-rust) <img src="https://img.shields.io/github/stars/spdes/kalman-rust?style=social"/> : A simple implementation of Kalman filter and RTS smoother in Rust (ndarray).

  - [hortovanyi/Unscented-Kalman-Filter-Rust](https://github.com/hortovanyi/Unscented-Kalman-Filter-Rust) <img src="https://img.shields.io/github/stars/hortovanyi/Unscented-Kalman-Filter-Rust?style=social"/> : UKF written in Rust based on the C++ UKF from the Udacity SD Car Nanodegree.

  - [wangxiaochuTHU/yakf](https://github.com/wangxiaochuTHU/yakf) <img src="https://img.shields.io/github/stars/wangxiaochuTHU/yakf?style=social"/> : Yet Another Kalman Filter Implementation. As well as Lie Theory (Lie group and algebra) on SE(3). [no_std] is supported by default.

  - [MichaelMauderer/filter-rs](https://github.com/MichaelMauderer/filter-rs) <img src="https://img.shields.io/github/stars/MichaelMauderer/filter-rs?style=social"/> : Kalman filters and other optimal and non-optimal estimation filters in Rust.

  - [rbagd/rust-linearkalman](https://github.com/rbagd/rust-linearkalman) <img src="https://img.shields.io/github/stars/rbagd/rust-linearkalman?style=social"/> : Kalman filtering and smoothing in Rust.



## Text Processing

  - [Serde](https://github.com/serde-rs/serde) <img src="https://img.shields.io/github/stars/serde-rs/serde?style=social"/> : Serde is a framework for serializing and deserializing Rust data structures efficiently and generically. [serde.rs/](https://serde.rs/)

  - [serde-rs/json](https://github.com/serde-rs/json) <img src="https://img.shields.io/github/stars/serde-rs/json?style=social"/> : Strongly typed JSON library for Rust.

  - [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) <img src="https://img.shields.io/github/stars/BurntSushi/rust-csv?style=social"/> : A fast and flexible CSV reader and writer for Rust, with support for Serde.

  - [informationsea/xlsxwriter-rs](https://github.com/informationsea/xlsxwriter-rs) <img src="https://img.shields.io/github/stars/informationsea/xlsxwriter-rs?style=social"/> : Excel file writer for Rust. [crates.io/crates/xlsxwriter](https://crates.io/crates/xlsxwriter)

  - [Ballasi/num2words](https://github.com/Ballasi/num2words) <img src="https://img.shields.io/github/stars/Ballasi/num2words?style=social"/> : Convert numbers like 42 to forty-two. [crates.io/crates/num2words](https://crates.io/crates/num2words)





## Image and Video Processing

  - [opencv-rust](https://github.com/twistedfall/opencv-rust) <img src="https://img.shields.io/github/stars/twistedfall/opencv-rust?style=social"/> : Rust bindings for OpenCV 3 & 4.

  - [rust-cv/cv](https://github.com/rust-cv/cv) <img src="https://img.shields.io/github/stars/rust-cv/cv?style=social"/> : Rust CV mono-repo. Contains pure-Rust dependencies which attempt to encapsulate the capability of OpenCV, OpenMVG, and vSLAM frameworks in a cohesive set of APIs.

  - [photon](https://github.com/silvia-odwyer/photon) <img src="https://img.shields.io/github/stars/silvia-odwyer/photon?style=social"/> : ⚡ Rust/WebAssembly image processing library. [silvia-odwyer.github.io/photon](https://silvia-odwyer.github.io/photon/). Photon is a high-performance Rust image processing library, which compiles to WebAssembly, allowing for safe, blazing-fast image processing both natively and on the web.

  - [image-rs/image](https://github.com/image-rs/image) <img src="https://img.shields.io/github/stars/image-rs/image?style=social"/> : Encoding and decoding images in Rust.

  - [image-rs/imageproc](https://github.com/image-rs/imageproc) <img src="https://img.shields.io/github/stars/image-rs/imageproc?style=social"/> : An image processing library, based on the [image](https://github.com/image-rs/image) library.

  - [zshipko/image2-rs](https://github.com/zshipko/image2-rs) <img src="https://img.shields.io/github/stars/zshipko/image2-rs?style=social"/> : A Rust crate focused on generic image processing for a wide range of image formats and data types.

  - [WebRTC.rs](https://github.com/webrtc-rs/webrtc) <img src="https://img.shields.io/github/stars/webrtc-rs/webrtc?style=social"/> : A pure Rust implementation of WebRTC. [webrtc.rs](https://webrtc.rs/)

  - [zmwangx/rust-ffmpeg](https://github.com/zmwangx/rust-ffmpeg) <img src="https://img.shields.io/github/stars/zmwangx/rust-ffmpeg?style=social"/> : Safe FFmpeg wrapper.

  - [meh/rust-ffmpeg](https://github.com/meh/rust-ffmpeg) <img src="https://img.shields.io/github/stars/meh/rust-ffmpeg?style=social"/> : Safe FFmpeg wrapper.

  - [Simp](https://github.com/Kl4rry/simp) <img src="https://img.shields.io/github/stars/Kl4rry/simp?style=social"/> : 🖼️ Simp is a fast and simple GPU-accelerated image manipulation program.

  - [jay3332/ril](https://github.com/jay3332/ril) <img src="https://img.shields.io/github/stars/jay3332/ril?style=social"/> : Rust Imaging Library: A high-level imaging crate for Rust. [crates.io/crates/ril](https://crates.io/crates/ril)

  - [Futsch1/image-sieve](https://github.com/Futsch1/image-sieve) <img src="https://img.shields.io/github/stars/Futsch1/image-sieve?style=social"/> : ImageSieve is a GUI based tool to assist in sorting images based on taken date and similarity, categorize them according to their creation date and archive them in a target folder.

  - [neka-nat/cuimage](https://github.com/neka-nat/cuimage) <img src="https://img.shields.io/github/stars/neka-nat/cuimage?style=social"/> : Rust implementation of image processing library with CUDA.

  - [iamdb/stream-cv](https://github.com/iamdb/stream-cv) <img src="https://img.shields.io/github/stars/iamdb/stream-cv?style=social"/> : Playing around with Rust, libav (ffmpeg), opencv and multithreading.

  - [BinciLuo/Rust-opencv-Application](https://github.com/BinciLuo/Rust-opencv-Application) <img src="https://img.shields.io/github/stars/BinciLuo/Rust-opencv-Application?style=social"/> : Implementation of an application based on OpenCV written in Rust.

  - [koukemo/rust_cv_sample](https://github.com/koukemo/rust_cv_sample) <img src="https://img.shields.io/github/stars/koukemo/rust_cv_sample?style=social"/> : Sample of Rust using opencv to load images.





## Localization and Mapping

  - [richardanaya/slamburger](https://github.com/richardanaya/slamburger) <img src="https://img.shields.io/github/stars/richardanaya/slamburger?style=social"/> : A SLAM algorithm for WebAssembly 🍔

  - [pekkaran/violet](https://github.com/pekkaran/violet) <img src="https://img.shields.io/github/stars/pekkaran/violet?style=social"/> : A toy stereo visual inertial odometry (VIO) system.

  - [ndbaker1/SLAMR](https://github.com/ndbaker1/SLAMR) <img src="https://img.shields.io/github/stars/ndbaker1/SLAMR?style=social"/> : modules for visual odometry and IMU integration written in Rust.

  - [geoeo/Vision](https://github.com/geoeo/Vision) <img src="https://img.shields.io/github/stars/geoeo/Vision?style=social"/> : Computer Vision stuff in Rust.

  - [geoeo/visual_odometry](https://github.com/geoeo/visual_odometry) <img src="https://img.shields.io/github/stars/geoeo/visual_odometry?style=social"/> : A rust port of [https://github.com/geoeo/Dense_VO](https://github.com/geoeo/Dense_VO).

  - [mpizenberg/visual-odometry-rs](https://github.com/mpizenberg/visual-odometry-rs) <img src="https://img.shields.io/github/stars/mpizenberg/visual-odometry-rs?style=social"/> : Visual Odometry in Rust (vors).








## Path Planning

  - [pathfinding](https://github.com/samueltardieu/pathfinding) <img src="https://img.shields.io/github/stars/samueltardieu/pathfinding?style=social"/> : Pathfinding library for rust. This crate implements several pathfinding, flow, and graph algorithms in Rust.

  - [rrt](https://github.com/openrr/rrt) <img src="https://img.shields.io/github/stars/openrr/rrt?style=social"/> : RRT (Rapidly-exploring Random Tree) library in Rust.

  - [gear](https://github.com/openrr/gear) <img src="https://img.shields.io/github/stars/openrr/gear?style=social"/> : Collision Avoidance Path Planning in Rust-lang.

  - [trajectory](https://github.com/openrr/trajectory) <img src="https://img.shields.io/github/stars/openrr/trajectory?style=social"/> : trajectory interpolation library for Rust and robotics.

  - [marcbone/s_curve](https://github.com/marcbone/s_curve) <img src="https://img.shields.io/github/stars/marcbone/s_curve?style=social"/> : S-Curve trajectory generator written in rust.

  - [Sollimann/bonsai](https://github.com/Sollimann/bonsai) <img src="https://img.shields.io/github/stars/Sollimann/bonsai?style=social"/> : Rust implementation of behavior trees.




## Motion Control

  - [k](https://github.com/openrr/k) <img src="https://img.shields.io/github/stars/openrr/k?style=social"/> : k: Kinematics library for rust-lang.

  - [rsasaki0109/RustRobotics](https://github.com/rsasaki0109/RustRobotics) <img src="https://img.shields.io/github/stars/rsasaki0109/RustRobotics?style=social"/> : This package is a rust implementation of [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics). Rust implementation of PythonRobotics such as EKF, DWA, Pure Pursuit, LQR.

  - [braincore/pid-rs](https://github.com/braincore/pid-rs) <img src="https://img.shields.io/github/stars/braincore/pid-rs?style=social"/> : A PID controller for Rust projects.

  - [yoshuawuyts/pid-lite](https://github.com/yoshuawuyts/pid-lite) <img src="https://img.shields.io/github/stars/yoshuawuyts/pid-lite?style=social"/> : A small PID controller library.

  - [bohonghuang/rov-host](https://github.com/bohonghuang/rov-host) <img src="https://img.shields.io/github/stars/bohonghuang/rov-host?style=social"/> : A cross-platform, high-performance underwater robot controll program written in Rust.

  - [zaiic/pid_rs](https://github.com/zaiic/pid_rs) <img src="https://img.shields.io/github/stars/zaiic/pid_rs?style=social"/> : A fairly minimal PID controller implementation in Rust.

  - [josh-tracey/PIDController](https://github.com/josh-tracey/PIDController) <img src="https://img.shields.io/github/stars/josh-tracey/PIDController?style=social"/> : Rust PID Controller library. Rust Crate: [https://crates.io/crates/adriftdev_pid](https://crates.io/crates/adriftdev_pid)

  - [ua-kxie/pid-ctrl](https://github.com/ua-kxie/pid-ctrl) <img src="https://img.shields.io/github/stars/ua-kxie/pid-ctrl?style=social"/> : Flexible pid controller with time delta as argument.

  - [tana/balance-robot2](https://github.com/tana/balance-robot2) <img src="https://img.shields.io/github/stars/tana/balance-robot2?style=social"/> : Self-balancing robot using LQR control, written in Rust.

  - [AlexKaravaev/rust_mpc](https://github.com/AlexKaravaev/rust_mpc) <img src="https://img.shields.io/github/stars/AlexKaravaev/rust_mpc?style=social"/> : MPC racing controller made in [ros2-rust](https://github.com/ros2-rust/ros2_rust).





## Finite State Machine

  - [eugene-babichenko/rust-fsm](https://github.com/eugene-babichenko/rust-fsm) <img src="https://img.shields.io/github/stars/eugene-babichenko/rust-fsm?style=social"/> : A framework for building finite state machines in Rust.

  - [hashmismatch/finny.rs](https://github.com/hashmismatch/finny.rs) <img src="https://img.shields.io/github/stars/hashmismatch/finny.rs?style=social"/> : Finny - Hierarchical Finite State Machines for Rust.






## Game Field

  - [Bevy](https://github.com/bevyengine/bevy) <img src="https://img.shields.io/github/stars/bevyengine/bevy?style=social"/> : Bevy is a refreshingly simple data-driven game engine built in Rust. It is free and open-source forever! [bevyengine.org](https://bevyengine.org/)

  - [Fyrox](https://github.com/FyroxEngine/Fyrox) <img src="https://img.shields.io/github/stars/FyroxEngine/Fyrox?style=social"/> : 3D and 2D game engine written in Rust. [fyrox.rs](https://fyrox.rs/)

  - [Ambient](https://github.com/AmbientRun/Ambient) <img src="https://img.shields.io/github/stars/AmbientRun/Ambient?style=social"/> : Ambient is a runtime for building high-performance multiplayer games and 3D applications, powered by WebAssembly, Rust and WebGPU. [ambient.run](https://www.ambient.run/)

  - [Rapier](https://github.com/dimforge/rapier) <img src="https://img.shields.io/github/stars/dimforge/rapier?style=social"/> : Rapier is a set of 2D and 3D physics engines for games, animation, and robotics. [rapier.rs](https://rapier.rs/)

  - [bevy_rapier](https://github.com/dimforge/bevy_rapier) <img src="https://img.shields.io/github/stars/dimforge/bevy_rapier?style=social"/> : Official Rapier plugin for the Bevy game engine.

  - [Parry](https://github.com/dimforge/parry) <img src="https://img.shields.io/github/stars/dimforge/parry?style=social"/> : 2D and 3D collision-detection library for Rust. [parry.rs](https://parry.rs/)

  - [Eldiron](https://github.com/markusmoenig/Eldiron) <img src="https://img.shields.io/github/stars/markusmoenig/Eldiron?style=social"/> : A cross platform classic RPG game creator written in Rust. [www.eldiron.com](https://eldiron.com/)





## Search Engine

  - [Meilisearch](https://github.com/meilisearch/meilisearch) <img src="https://img.shields.io/github/stars/meilisearch/meilisearch?style=social"/> : ⚡ A lightning-fast search engine that fits effortlessly into your apps, websites, and workflow 🔍 [www.meilisearch.com](https://www.meilisearch.com/)





## Web Crawler

  - [Spider](https://github.com/spider-rs/spider) <img src="https://img.shields.io/github/stars/spider-rs/spider?style=social"/> : Spider: The fastest web crawler and indexer. [docs.rs/spider/](https://docs.rs/spider/latest/spider/)

  - [a11ywatch/crawler](https://github.com/a11ywatch/crawler) <img src="https://img.shields.io/github/stars/a11ywatch/crawler?style=social"/> : A [gRPC](https://grpc.io/) web indexer turbo charged for performance.

  - [Antosser/web-crawler](https://github.com/Antosser/web-crawler) <img src="https://img.shields.io/github/stars/Antosser/web-crawler?style=social"/> : Rust Web Crawler that finds every page, image, and script on a website (and downloads it)

  - [ravenxd0/crawler](https://github.com/ravenxd0/crawler) <img src="https://img.shields.io/github/stars/ravenxd0/crawler?style=social"/> : Web Crawler in Rust.

  - [lonexw/rust-crawler](https://github.com/lonexw/rust-crawler) <img src="https://img.shields.io/github/stars/lonexw/rust-crawler?style=social"/> : A simple crawler, built with Rust lang.

  - [tawilkinson/rust_web_crawler](https://github.com/tawilkinson/rust_web_crawler) <img src="https://img.shields.io/github/stars/tawilkinson/rust_web_crawler?style=social"/> : A simple web crawler in rust.



## Web Framework

  - [reqwest](https://github.com/seanmonstar/reqwest) <img src="https://img.shields.io/github/stars/seanmonstar/reqwest?style=social"/> : An easy and powerful Rust HTTP Client. [docs.rs/reqwest](https://docs.rs/reqwest/latest/reqwest/)

  - [Yew](https://github.com/yewstack/yew) <img src="https://img.shields.io/github/stars/yewstack/yew?style=social"/> : Yew is a modern Rust framework for creating multi-threaded front-end web apps with WebAssembly. [yew.rs](https://yew.rs/)

  - [Axum](https://github.com/tokio-rs/axum) <img src="https://img.shields.io/github/stars/tokio-rs/axum?style=social"/> : Ergonomic and modular web framework built with Tokio, Tower, and Hyper.

  - [Salvo](https://github.com/salvo-rs/salvo) <img src="https://img.shields.io/github/stars/salvo-rs/salvo?style=social"/> : [Salvo](https://salvo.rs/) is a powerful and simplest web server framework in Rust world. [salvo.rs](https://salvo.rs/)

  - [Actix](https://github.com/actix/actix-web) <img src="https://img.shields.io/github/stars/actix/actix-web?style=social"/> : Actix Web is a powerful, pragmatic, and extremely fast web framework for Rust. [actix.rs](https://actix.rs/)

  - [Rocket](https://github.com/SergioBenitez/Rocket) <img src="https://img.shields.io/github/stars/SergioBenitez/Rocket?style=social"/> : A web framework for Rust. [rocket.rs](https://rocket.rs/)

  - [Poem](https://github.com/poem-web/poem) <img src="https://img.shields.io/github/stars/poem-web/poem?style=social"/> : A full-featured and easy-to-use web framework with the Rust programming language.

  - [Rouille](https://github.com/tomaka/rouille) <img src="https://img.shields.io/github/stars/tomaka/rouille?style=social"/> : Rouille, a Rust web micro-framework.

  - [Leptos](https://github.com/leptos-rs/leptos) <img src="https://img.shields.io/github/stars/leptos-rs/leptos?style=social"/> : Build fast web applications with Rust.

  - [Farm](https://github.com/farm-fe/farm) <img src="https://img.shields.io/github/stars/farm-fe/farm?style=social"/> : Super fast web build tool written in Rust - 基于 Rust 的极速 web 构建引擎。 [farm-fe.github.io](https://farm-fe.github.io/)

  - [zino](https://github.com/photino/zino) <img src="https://img.shields.io/github/stars/photino/zino?style=social"/> : zino is a full-featured web application framework for Rust with a focus on productivity and performance.

  - [Hyper](https://github.com/vercel/hyper) <img src="https://img.shields.io/github/stars/vercel/hyper?style=social"/> : A terminal built on web technologies. [hyper.is](https://hyper.is/)

  - [Deno](https://github.com/denoland/deno) <img src="https://img.shields.io/github/stars/denoland/deno?style=social"/> : Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust. [deno.land](https://deno.land/)

  - [SWC](https://github.com/swc-project/swc) <img src="https://img.shields.io/github/stars/swc-project/swc?style=social"/> : SWC (stands for Speedy Web Compiler) is a super-fast TypeScript / JavaScript compiler written in Rust. [swc.rs](https://swc.rs/)

  - [tchatche.rs](https://github.com/nag763/tchatchers) <img src="https://img.shields.io/github/stars/nag763/tchatchers?style=social"/> : tchatche.rs is a blazing fast chat application built with Axum and Yew.rs. [tchatche.rs](https://tchatche.rs/signin)

  - [tonic](https://github.com/hyperium/tonic) <img src="https://img.shields.io/github/stars/hyperium/tonic?style=social"/> : A native gRPC client & server implementation with async/await support. [docs.rs/tonic](https://docs.rs/tonic/latest/tonic/)

  - [MoonZoon](https://github.com/MoonZoon/MoonZoon) <img src="https://img.shields.io/github/stars/MoonZoon/MoonZoon?style=social"/> : Rust Fullstack Framework.






## RPC Framework

  - [Volo](https://github.com/cloudwego/volo) <img src="https://img.shields.io/github/stars/cloudwego/volo?style=social"/> : Volo is a high-performance and strong-extensibility Rust RPC framework that helps developers build microservices. [crates.io/crates/volo](https://crates.io/crates/volo)






## Web3 Framework

  - [nostr](https://github.com/nostr-protocol/nostr) <img src="https://img.shields.io/github/stars/nostr-protocol/nostr?style=social"/> : a truly censorship-resistant alternative to Twitter that has a chance of working. The simplest open protocol that is able to create a censorship-resistant global "social" network once and for all.

  - [awesome-nostr](https://github.com/aljazceru/awesome-nostr) <img src="https://img.shields.io/github/stars/aljazceru/awesome-nostr?style=social"/> : A curated list of nostr projects and resources. [www.nostr.net](https://www.nostr.net/)

  - [Damus](https://github.com/damus-io/damus) <img src="https://img.shields.io/github/stars/damus-io/damus?style=social"/> : A twitter-like nostr client for iPhone, iPad and MacOS.

  - [Amethyst](https://github.com/vitorpamplona/amethyst) <img src="https://img.shields.io/github/stars/vitorpamplona/amethyst?style=social"/> : Amethyst brings the best social network to your Android phone. Just insert your Nostr private key and start posting.

  - [rust-nostr/nostr](https://github.com/rust-nostr/nostr) <img src="https://img.shields.io/github/stars/rust-nostr/nostr?style=social"/> : Nostr protocol implementation, SDK and FFI.

  - [mikedilger/gossip](https://github.com/mikedilger/gossip) <img src="https://img.shields.io/github/stars/mikedilger/gossip?style=social"/> : Gossip is a desktop client for nostr.

  - [Sway](https://github.com/FuelLabs/sway) <img src="https://img.shields.io/github/stars/FuelLabs/sway?style=social"/> : 🌴 Empowering everyone to build reliable and efficient smart contracts. [ fuellabs.github.io/sway](https://fuellabs.github.io/sway)

  - [FuelLabs/fuel-core](https://github.com/FuelLabs/fuel-core) <img src="https://img.shields.io/github/stars/FuelLabs/fuel-core?style=social"/> : Rust full node implementation of the Fuel v2 protocol.

  - [FuelLabs/fuels-rs](https://github.com/FuelLabs/fuels-rs) <img src="https://img.shields.io/github/stars/FuelLabs/fuels-rs?style=social"/> : Fuel Network Rust SDK. [fuellabs.github.io/fuels-rs](https://fuellabs.github.io/fuels-rs)

  - [solana](https://github.com/solana-labs/solana) <img src="https://img.shields.io/github/stars/solana-labs/solana?style=social"/> : Web-Scale Blockchain for fast, secure, scalable, decentralized apps and marketplaces. [solanalabs.com](https://solanalabs.com/)

  - [Anchor](https://github.com/coral-xyz/anchor) <img src="https://img.shields.io/github/stars/coral-xyz/anchor?style=social"/> : ⚓ Solana Sealevel Framework. [anchor-lang.com](https://www.anchor-lang.com/)

  - [CreatorsDAO/awesome-learn-solana](https://github.com/CreatorsDAO/awesome-learn-solana) <img src="https://img.shields.io/github/stars/CreatorsDAO/awesome-learn-solana?style=social"/> : awesome-learn-solana.

  - [CreatorsDAO/all-in-one-solana](https://github.com/CreatorsDAO/all-in-one-solana) <img src="https://img.shields.io/github/stars/CreatorsDAO/all-in-one-solana?style=social"/> : All in One Solana.

  - [CleverProgrammers/facebook-solana-blockchain](https://github.com/CleverProgrammers/facebook-solana-blockchain) <img src="https://img.shields.io/github/stars/CleverProgrammers/facebook-solana-blockchain?style=social"/> : Build Facebook 3.0 on Blockchain with Solana | Next.js | Netlify | Sanity.io.

  - [MartinKavik/voting-solana-moonzoon](https://github.com/MartinKavik/voting-solana-moonzoon) <img src="https://img.shields.io/github/stars/MartinKavik/voting-solana-moonzoon?style=social"/> : The Voting example based on MoonZoon and Solana.

  - [NEAR Docs](https://docs.near.org/) : Welcome! This is the starting point for all the documentation in NEAR.

  - [near/awesome-near](https://github.com/near/awesome-near) <img src="https://img.shields.io/github/stars/near/awesome-near?style=social"/> : Curated list of resources: examples, libraries, projects. [examples.near.org](https://examples.near.org/)

  - [near/nearcore](https://github.com/near/nearcore) <img src="https://img.shields.io/github/stars/near/nearcore?style=social"/> : Reference client for NEAR Protocol. [near.org](https://near.org/)

  - [near/near-sdk-rs](https://github.com/near/near-sdk-rs) <img src="https://img.shields.io/github/stars/near/near-sdk-rs?style=social"/> : Rust library for writing NEAR smart contracts. [near-sdk.io](https://github.com/near/near-sdk-rs)

  - [near/create-near-app](https://github.com/near/create-near-app) <img src="https://img.shields.io/github/stars/near/create-near-app?style=social"/> : Create a starter app hooked up to the NEAR blockchain.

  - [near-examples/NFT](https://github.com/near-examples/NFT) <img src="https://img.shields.io/github/stars/near-examples/NFT?style=social"/> : Example implementations of tokens to represent unique assets, such as collectibles or deeds, using the NEP-171 spec (similar to ERC-721).

  - [near-examples/nft-tutorial](https://github.com/near-examples/nft-tutorial) <img src="https://img.shields.io/github/stars/near-examples/nft-tutorial?style=social"/> : Welcome to NEAR's NFT tutorial, where we will help you parse the details around NEAR's [NEP-171 standard](https://nomicon.io/Standards/Tokens/NonFungibleToken/Core) (Non-Fungible Token Standard), and show you how to build your own NFT smart contract from the ground up, improving your understanding about the NFT standard along the way.

  - [hanakannzashi/near-course-base](https://github.com/hanakannzashi/near-course-base) <img src="https://img.shields.io/github/stars/hanakannzashi/near-course-base?style=social"/> : NEAR 智能合约开发教程（基础篇）。

  - [tranvinh146/voting-contract](https://github.com/tranvinh146/voting-contract) <img src="https://img.shields.io/github/stars/tranvinh146/voting-contract?style=social"/> : This is smart contract to vote from phase 1 to phase 2 on Near.

  - [catmcgee/near-voting-contracts](https://github.com/catmcgee/near-voting-contracts) <img src="https://img.shields.io/github/stars/catmcgee/near-voting-contracts?style=social"/> : Different types of voting smart contracts on NEAR blockchain.

  - [rickhysis/vote-coffe-near](https://github.com/rickhysis/vote-coffe-near) <img src="https://img.shields.io/github/stars/rickhysis/vote-coffe-near?style=social"/> : This is smart contract example for vote the best coffe using NEAR Protocol ("NEAR" hereafter).

  - [Dispa1r/Disp41r-Super-Voting-System](https://github.com/Dispa1r/Disp41r-Super-Voting-System) <img src="https://img.shields.io/github/stars/Dispa1r/Disp41r-Super-Voting-System?style=social"/> : a super super super voting system on near block chain :)

  - [flexabyte/near-vote](https://github.com/flexabyte/near-vote) <img src="https://img.shields.io/github/stars/flexabyte/near-vote?style=social"/> : A decentralized voting contract for NEAR protocol.

  - [YellingOilbird/choice](https://github.com/YellingOilbird/choice) <img src="https://img.shields.io/github/stars/YellingOilbird/choice?style=social"/> : NEAR smart contract for non-binary vote.

  - [dylan751/near-app-vote-sc](https://github.com/dylan751/near-app-vote-sc) <img src="https://img.shields.io/github/stars/dylan751/near-app-vote-sc?style=social"/> : Voting App using Near-Rust and implement ZKP.

  - [winkelstein/DeChat](https://github.com/winkelstein/DeChat) <img src="https://img.shields.io/github/stars/winkelstein/DeChat?style=social"/> : Messenger based on NEAR blockchain.

  - [Cairo](https://github.com/starkware-libs/cairo) <img src="https://img.shields.io/github/stars/starkware-libs/cairo?style=social"/> : Cairo is the first Turing-complete language for creating provable programs for general computation. ⚡ Blazing ⚡ fast ⚡ compiler for Cairo, written in 🦀 Rust 🦀

  - [cairo-book/cairo-book.github.io](https://github.com/cairo-book/cairo-book.github.io/) <img src="https://img.shields.io/github/stars/cairo-book/cairo-book.github.io/?style=social"/> : The Cairo Programming Language Book, a comprehensive documentation of the Cairo 1 programming language. [The Cairo Programming Language Book](https://book.cairo-lang.org/)

  - [Orion](https://github.com/gizatechxyz/orion) <img src="https://img.shields.io/github/stars/gizatechxyz/orion?style=social"/> : Orion: An Open-source Framework for Validity and ZK ML ✨. ONNX Runtime in Cairo 1.0 for verifiable ML inference using STARK. [orion.gizatech.xyz](https://orion.gizatech.xyz/)

  - [franalgaba/neural-network-cairo](https://github.com/franalgaba/neural-network-cairo) <img src="https://img.shields.io/github/stars/franalgaba/neural-network-cairo?style=social"/> : Neural Network implementation from scratch for MNIST using Cairo 1.0.

  - [raphaelDkhn/cairo_ml](https://github.com/raphaelDkhn/cairo_ml) <img src="https://img.shields.io/github/stars/raphaelDkhn/cairo_ml?style=social"/> : Build neural network models in Cairo 1.0.

  - [gakonst/awesome-starknet](https://github.com/gakonst/awesome-starknet) <img src="https://img.shields.io/github/stars/gakonst/awesome-starknet?style=social"/> : A curated list of awesome StarkNet resources, libraries, tools and more.

  - [starknet-edu/starknetbook](https://github.com/starknet-edu/starknetbook) <img src="https://img.shields.io/github/stars/starknet-edu/starknetbook?style=social"/> : Mastering Cairo and Starknet. By the Starknet community. [book.starknet.io](https://book.starknet.io/)

  - [xJonathanLEI/starknet-rs](https://github.com/xJonathanLEI/starknet-rs) <img src="https://img.shields.io/github/stars/xJonathanLEI/starknet-rs?style=social"/> : Complete Starknet library in Rust™. [starknet.rs](https://github.com/xJonathanLEI/starknet-rs)

  - [0xSpaceShard/starknet-devnet-rs](https://github.com/0xSpaceShard/starknet-devnet-rs) <img src="https://img.shields.io/github/stars/0xSpaceShard/starknet-devnet-rs?style=social"/> : A local testnet for Starknet... in Rust.

  - [0xAsten/Starknet-Tech-Stacks-Mindmap](https://github.com/0xAsten/Starknet-Tech-Stacks-Mindmap) <img src="https://img.shields.io/github/stars/0xAsten/Starknet-Tech-Stacks-Mindmap?style=social"/> : This open collaboration project aims to explore and document the various technology stacks associated with Starknet.

  - [gakonst/ethers-rs](https://github.com/gakonst/ethers-rs) <img src="https://img.shields.io/github/stars/gakonst/ethers-rs?style=social"/> :  Complete Ethereum & Celo library and wallet implementation in Rust. [https://docs.rs/ethers](https://docs.rs/ethers/latest/ethers/)

  - [move](https://github.com/move-language/move) <img src="https://img.shields.io/github/stars/move-language/move?style=social"/> : Move is a programming language for writing safe smart contracts originally developed at Facebook to power the Diem blockchain.

  - [Sui](https://github.com/MystenLabs/sui) <img src="https://img.shields.io/github/stars/MystenLabs/sui?style=social"/> : Sui is a next-generation smart contract platform with high throughput, low latency, and an asset-oriented programming model powered by the [Move programming language](https://github.com/MystenLabs/awesome-move). [sui.io](https://sui.io/)

  - [Rooch](https://github.com/rooch-network/rooch) <img src="https://img.shields.io/github/stars/rooch-network/rooch?style=social"/> : Rooch is a modular DApp container with the [Move language](https://github.com/move-language/move). [rooch.network](https://rooch.network/zh-CN)

  - [Substrate](https://github.com/paritytech/substrate) <img src="https://img.shields.io/github/stars/paritytech/substrate?style=social"/> : Substrate is a next-generation framework for blockchain innovation 🚀.

  - [Galactic-Hub/cosmos-sdk-rs](https://github.com/Galactic-Hub/cosmos-sdk-rs) <img src="https://img.shields.io/github/stars/Galactic-Hub/cosmos-sdk-rs?style=social"/> : Cosmos SDK implement by Rust.

  - [cosmos/ibc-rs](https://github.com/cosmos/ibc-rs) <img src="https://img.shields.io/github/stars/cosmos/ibc-rs?style=social"/> : Rust implementation of the Inter-Blockchain Communication (IBC) protocol.

  - [Sovereign-Labs/sovereign-sdk](https://github.com/Sovereign-Labs/sovereign-sdk) <img src="https://img.shields.io/github/stars/Sovereign-Labs/sovereign-sdk?style=social"/> : A framework for building seamlessly scalable and interoperable rollups that can run on any blockchain. [sovereign.xyz](https://www.sovereign.xyz/)

  - [octopus-network/near-ibc](https://github.com/octopus-network/near-ibc) <img src="https://img.shields.io/github/stars/octopus-network/near-ibc?style=social"/> : near smart contract implement ibc protocol.

  - [talent-verse/Jobs](https://github.com/talent-verse/Jobs) <img src="https://img.shields.io/github/stars/talent-verse/Jobs?style=social"/> : Web3, Blockchain, AI jobs.

  - [wildonion/smarties](https://github.com/wildonion/smarties) <img src="https://img.shields.io/github/stars/wildonion/smarties?style=social"/> :  🍬 NEAR and Ethereum NFT Marketplace Smart Contracts 🍫

  - [sigp/lighthouse](https://github.com/sigp/lighthouse) <img src="https://img.shields.io/github/stars/sigp/lighthouse?style=social"/> :  Ethereum consensus client in Rust.









## WebAssembly

  - [Wasmer](https://github.com/wasmerio/wasmer) <img src="https://img.shields.io/github/stars/wasmerio/wasmer?style=social"/> : Wasmer is a fast and secure [WebAssembly](https://webassembly.org/) runtime that enables super lightweight containers to run anywhere: from Desktop to the Cloud, Edge and IoT devices. [wasmer.io](https://wasmer.io/)

  - [wasmtime](https://github.com/bytecodealliance/wasmtime) <img src="https://img.shields.io/github/stars/bytecodealliance/wasmtime?style=social"/> : A fast and secure runtime for WebAssembly. [wasmtime.dev/](https://wasmtime.dev/)




## Graphics Library

  - [rust-skia/rust-skia](https://github.com/rust-skia/rust-skia) <img src="https://img.shields.io/github/stars/rust-skia/rust-skia?style=social"/> : Safe Rust bindings to the [Skia Graphics Library](https://skia.org/).

  - [gtk-rs/gtk4-rs](https://github.com/gtk-rs/gtk4-rs) <img src="https://img.shields.io/github/stars/gtk-rs/gtk4-rs?style=social"/> : Rust bindings of GTK 4. [gtk-rs.org/gtk4-rs/](https://gtk-rs.org/gtk4-rs/)

  - [gtk-rs/gtk3-rs](https://github.com/gtk-rs/gtk3-rs) <img src="https://img.shields.io/github/stars/gtk-rs/gtk3-rs?style=social"/> : Rust bindings for GTK 3. [gtk-rs.org](https://gtk-rs.org/)

  - [SabianF/rust_wgpu_3D_vision](https://github.com/SabianF/rust_wgpu_3D_vision) <img src="https://img.shields.io/github/stars/SabianF/rust_wgpu_3D_vision?style=social"/> : A program to simulate stereoscopic 4D vision, using a virtual 3D retina which is created by rapidly displaying all voxels at varying depths of a 3D volume.



## GUI

  - ### GUI Framework

    - #### Desktop APP Development

        - [Tauri](https://github.com/tauri-apps/tauri) <img src="https://img.shields.io/github/stars/tauri-apps/tauri?style=social"/> : Build smaller, faster, and more secure desktop applications with a web frontend. [tauri.app](https://tauri.app/). Tauri is a framework for building tiny, blazingly fast binaries for all major desktop platforms. Developers can integrate any front-end framework that compiles to HTML, JS and CSS for building their user interface. The backend of the application is a rust-sourced binary with an API that the front-end can interact with.

        - [Pake](https://github.com/tw93/Pake) <img src="https://img.shields.io/github/stars/tw93/Pake?style=social"/> : 🤱🏻 Turn any webpage into a desktop app with Rust. 🤱🏻 很简单的用 Rust 打包网页生成很小的桌面 App.

        - [Slint](https://github.com/slint-ui/slint) <img src="https://img.shields.io/github/stars/slint-ui/slint?style=social"/> : Slint is a declarative GUI toolkit to build native user interfaces for applications that are written in Rust, C++, or JavaScript. [slint.dev](https://slint.dev/)

        - [slint-ui/slint-rust-template](https://github.com/slint-ui/slint-rust-template) <img src="https://img.shields.io/github/stars/slint-ui/slint?style=social"/> : A template for a Rust Application using Slint. This is meant to be used with cargo-generate. [slint.dev](https://slint.dev/)

        - [Makepad](https://github.com/makepad/makepad) <img src="https://img.shields.io/github/stars/makepad/makepad?style=social"/> : Makepad is a creative software development platform for Rust that compiles to wasm/webGL, osx/metal, windows/dx11 linux/opengl. [makepad.dev/](https://makepad.dev/)

        - [Dioxus](https://github.com/DioxusLabs/dioxus) <img src="https://img.shields.io/github/stars/DioxusLabs/dioxus?style=social"/> : Fullstack GUI library for desktop, web, mobile, and more. [dioxuslabs.com](https://dioxuslabs.com/)

        - [egui](https://github.com/emilk/egui) <img src="https://img.shields.io/github/stars/emilk/egui?style=social"/> : egui: an easy-to-use immediate mode GUI in Rust that runs on both web and native.

        - [Iced](https://github.com/iced-rs/iced) <img src="https://img.shields.io/github/stars/iced-rs/iced?style=social"/> : A cross-platform GUI library for Rust focused on simplicity and type-safety. Inspired by [Elm](https://elm-lang.org/).

        - [Xilem](https://github.com/linebender/xilem) <img src="https://img.shields.io/github/stars/linebender/xilem?style=social"/> : An experimental Rust architecture for reactive UI.

        - [Druid](https://github.com/linebender/druid) <img src="https://img.shields.io/github/stars/linebender/druid?style=social"/> : A data-first Rust-native UI toolkit.

        - [Floem](https://github.com/lapce/floem) <img src="https://img.shields.io/github/stars/lapce/floem?style=social"/> : A native Rust UI library with fine-grained reactivity.

        - [marek-g/rust-fui](https://github.com/marek-g/rust-fui) <img src="https://img.shields.io/github/stars/marek-g/rust-fui?style=social"/> : MVVM Rust UI Framework Library.

        - [KDAB/cxx-qt](https://github.com/KDAB/cxx-qt) <img src="https://img.shields.io/github/stars/KDAB/cxx-qt?style=social"/> : Safe interop between Rust and Qt.

        - [KDE/rust-qt-binding-generator](https://github.com/KDE/rust-qt-binding-generator) <img src="https://img.shields.io/github/stars/KDE/rust-qt-binding-generator?style=social"/> : Generate bindings to use Rust code in Qt and QML.

        - [apertus-open-source-cinema/narui](https://github.com/apertus-open-source-cinema/narui) <img src="https://img.shields.io/github/stars/apertus-open-source-cinema/narui?style=social"/> : A react-inspired UI library for building multimedia desktop apps with rust and vulkan.

        - [marc2332/freya](https://github.com/marc2332/freya) <img src="https://img.shields.io/github/stars/marc2332/freya?style=social"/> : Native GUI library for 🦀 Rust powered by 🧬 Dioxus and 🎨 Skia. [freyaui.dev/](https://freyaui.dev/)



    - #### Mobile APP Development

        - [flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge) <img src="https://img.shields.io/github/stars/fzyzcjy/flutter_rust_bridge?style=social"/> : High-level memory-safe binding generator for Flutter/Dart <-> Rust. [fzyzcjy.github.io/flutter_rust_bridge/](https://cjycode.com/flutter_rust_bridge/)

        - [Rust-In-Flutter](https://github.com/cunarist/rust-in-flutter) <img src="https://img.shields.io/github/stars/cunarist/rust-in-flutter?style=social"/> : Rust as your Flutter backend, Flutter as your Rust frontend.

        - [Crux](https://github.com/redbadger/crux) <img src="https://img.shields.io/github/stars/redbadger/crux?style=social"/> : Cross-platform app development in Rust. [redbadger.github.io/crux/](https://redbadger.github.io/crux/)






  - ### GUI Software

    - #### Tauri-Related

      - [sandunwira/SupTube](https://github.com/sandunwira/SupTube) <img src="https://img.shields.io/github/stars/sandunwira/SupTube?style=social"/> : An open-source Windows client for YouTube. [suptube.repl.co](https://suptube.repl.co/)

      - [spieglt/FlyingCarpet](https://github.com/spieglt/FlyingCarpet) <img src="https://img.shields.io/github/stars/spieglt/FlyingCarpet?style=social"/> : File transfer between Android, iOS, Linux, macOS, and Windows over ad hoc WiFi. No network infrastructure required, just two devices with WiFi chips in close range.

      - [Minori-ty/mp4To4K-rust](https://github.com/Minori-ty/mp4To4K-rust) <img src="https://img.shields.io/github/stars/Minori-ty/mp4To4K-rust?style=social"/> : 使用Tauri做的一个将动漫视频转4K视频的软件。

      - [seiKiMo-Inc/Laudiolin](https://github.com/seiKiMo-Inc/Laudiolin) <img src="https://img.shields.io/github/stars/seiKiMo-Inc/Laudiolin?style=social"/> : A "high quality" music player written in TypeScript using Tauri and React.

      - [kingwingfly/bilibili-downloader-rs](https://github.com/kingwingfly/bilibili-downloader-rs) <img src="https://img.shields.io/github/stars/kingwingfly/bilibili-downloader-rs?style=social"/> : Bilibili Downloader. A bilibili video downloader app built by Tauri, Vue and Rust!

      - [pacholoamit/pachtop](https://github.com/pacholoamit/pachtop) <img src="https://img.shields.io/github/stars/pacholoamit/pachtop?style=social"/> : Cross-platform (Linux, WIndows, MacOS) Desktop GUI system monitor, built with Rust & Tauri.

      - [lecepin/douyin-downloader](https://github.com/lecepin/douyin-downloader) <img src="https://img.shields.io/github/stars/lecepin/douyin-downloader?style=social"/> : 使用非常简单的抖音视频无水印下载工具。支持下单个视频，以及下载某个人的所有视频。（采用rust+tauri编写，安装包非常小）。

      - [lecepin/desktop-webcam](https://github.com/lecepin/desktop-webcam) <img src="https://img.shields.io/github/stars/lecepin/desktop-webcam?style=social"/> : 使用 webassembly 通过 tauri 封装的桌面摄相头。

      - [pot-app/pot-desktop](https://github.com/pot-app/pot-desktop) <img src="https://img.shields.io/github/stars/pot-app/pot-desktop?style=social"/> : 🌈一个跨平台的划词翻译软件 | A cross-platform translation software. [pot.pylogmon.com](https://pot.pylogmon.com/)

      - [conaticus/FileExplorer](https://github.com/conaticus/FileExplorer) <img src="https://img.shields.io/github/stars/conaticus/FileExplorer?style=social"/> : Fast file explorer written with Tauri and React.

      - [mxismean/image-tiny-tauri](https://github.com/mxismean/image-tiny-tauri) <img src="https://img.shields.io/github/starsmxismean/image-tiny-tauri?style=social"/> : Tauri 项目：图片压缩应用。一款小而美的图片压缩工具， 支持 png、jpg、gif 三种图片格式压缩。 该工具不依赖服务端，只需在客户端就可以完成压缩工作。您只需拖拽你的图片文件到该应用窗口即可。

      - [BD777/imageview](https://github.com/BD777/imageview) <img src="https://img.shields.io/github/stars/BD777/imageview?style=social"/> : Image viewer by tauri. A image viewer by tauri. 用来看图的软件，当然，看漫画也是很方便的。





    - #### Slint-Related

      - [slint-ui/madewithslint](https://github.com/slint-ui/madewithslint) <img src="https://img.shields.io/github/stars/slint-ui/madewithslint?style=social"/> : This is the website repo listing awesome applications built with Slint. [madewithslint.com/](https://madewithslint.com/)

      - [slint-ui/cargo-ui](https://github.com/slint-ui/cargo-ui) <img src="https://img.shields.io/github/stars/slint-ui/cargo-ui?style=social"/> : This is a project to make a GUI for cargo, built using [Slint](https://github.com/slint-ui/slint).

      - [GaspardCulis/slint-tetris](https://github.com/GaspardCulis/slint-tetris) <img src="https://img.shields.io/github/stars/GaspardCulis/slint-tetris?style=social"/> : Tetris game made with Slint. [gaspardculis.github.io/slint-tetris/](https://gaspardculis.github.io/slint-tetris/)

      - [MohaBeacon/slint-opencv](https://github.com/MohaBeacon/slint-opencv) <img src="https://img.shields.io/github/stars/MohaBeacon/slint-opencv?style=social"/> : slint-opencv.

      - [colelawrence/here-now](https://github.com/colelawrence/here-now) <img src="https://img.shields.io/github/stars/colelawrence/here-now?style=social"/> : A low-resource native app for sharing space with co-workers and friends.

      - [Ouam74/RUST_Real-time_plots_using_SLINT_and_PLOTTERS.rs](https://github.com/Ouam74/RUST_Real-time_plots_using_SLINT_and_PLOTTERS.rs) <img src="https://img.shields.io/github/stars/Ouam74/RUST_Real-time_plots_using_SLINT_and_PLOTTERS.rs?style=social"/> : RUST_Real-time_plots_using_SLINT_and_PLOTTERS.rs

      - [hexiangdong2020/PlcDebugTool](https://github.com/hexiangdong2020/PlcDebugTool) <img src="https://img.shields.io/github/stars/hexiangdong2020/PlcDebugTool?style=social"/> : 使用Rust和Slint编写的Simense S7 PLC的调试工具。

      - [hexiangdong2020/SerialDebugTool](https://github.com/hexiangdong2020/SerialDebugTool) <img src="https://img.shields.io/github/stars/hexiangdong2020/SerialDebugTool?style=social"/> : 使用Rust和Slint开发的串口调试工具。

      - [Damncool0216/slint-stm32f1](https://github.com/Damncool0216/slint-stm32f1) <img src="https://img.shields.io/github/stars/Damncool0216/slint-stm32f1?style=social"/> : small demo using Slint on stm32f1.

      - [vgarleanu/lumiere](https://github.com/vgarleanu/lumiere) <img src="https://img.shields.io/github/stars/vgarleanu/lumiere?style=social"/> : Example video player built with MPV and Slint-UI.

      - [Berrysoft/tunet-rust](https://github.com/Berrysoft/tunet-rust) <img src="https://img.shields.io/github/stars/Berrysoft/tunet-rust?style=social"/> : 清华大学校园网 Rust 库与客户端。


    - #### Makepad-Related

      - [mobilerust/makepad_wechat](https://github.com/mobilerust/makepad_wechat) <img src="https://img.shields.io/github/stars/mobilerust/makepad_wechat?style=social"/> : WeChat-like application implemented with Makepad.

      - [mobilerust/makepad_taobao](https://github.com/mobilerust/makepad_taobao) <img src="https://img.shields.io/github/stars/mobilerust/makepad_taobao?style=social"/> : makepad_taobao.

      - [mobilerust/makepad_social_media_feed](https://github.com/mobilerust/makepad_social_media_feed) <img src="https://img.shields.io/github/stars/mobilerust/makepad_social_media_feed?style=social"/> : Example app of a social media feed for mobile applications, using makepad.

      - [mobilerust/todo_makepad](https://github.com/mobilerust/todo_makepad) <img src="https://img.shields.io/github/stars/mobilerust/todo_makepad?style=social"/> : Example TODO app built with Makepad.









## Blogs

  - 微信公众号「Rust语言中文社区」
    - [2021-08-08，拓展 | Rust语言在嵌入式领域的应用](https://mp.weixin.qq.com/s/4WjGh2JaVlCelGQe-sMEpw)
    - [2023-05-07，【Rust日报】2023-05-06 深度学习框架 Burn 发布 v0.7.0](https://mp.weixin.qq.com/s/VQy-EeM11U7OplRyyZ0Nvw)
    - [2023-05-11，【Rust日报】2023-05-10 llm - 使用Rust在CPU上运行大模型](https://mp.weixin.qq.com/s/73Bz-ZPEo974NH1TrQdJkQ)
    - [2023-05-11，Rust UI 框架：Slint UI 简单入门](https://mp.weixin.qq.com/s/_2rgwK5MHQh5kENi5o-nmA)
    - [2023-05-24，字节跳动：将持续投入Rust，期待更多Rust生态合作和建设](https://mp.weixin.qq.com/s/NvVq3Fq7wi7myr77qo-zwQ)
    - [2023-05-26，【Rust日报】2023-05-25 Scientific Computing in Rust 2023](https://mp.weixin.qq.com/s/g3tcSDFTTnHcrQw02kFbnw)
    - [2023-06-04，【Rust日报】2023-06-03 femtoGPT，纯 Rust 实现的最小化 GPT](https://mp.weixin.qq.com/s/JUH2K4jYEPLlrScmOsqS5g)
    - [2023-06-22，[Rust招聘] 国家智能网联汽车创新中心Rust工程师招聘（车载操作系统）](https://mp.weixin.qq.com/s/dB45f4ty-Ag-XkmggJ6RNQ)
    - [2023-07-14，邀请您参加有偿的Unsafe Rust调研](https://mp.weixin.qq.com/s/6ZJu0vmlNabbyMGD7QCK9A)
    - [2023-08-10，【Rust招聘】【理想汽车】rust高级开发工程师（35K-50K）](https://mp.weixin.qq.com/s/n7RfhW5NyhAlwcD2xJjgFQ)
  - 微信公众号「Rust学习日记」
    - [2022-08-13，【Rust 中级教程】 01 泛型](https://mp.weixin.qq.com/s/jbrgdfLTWOFsh42-CHHuEw)
    - [2022-08-20，【Rust 中级教程】 02 结构体与泛型](https://mp.weixin.qq.com/s/P_weMIXLaULXzlQRlWcRIw)
    - [2022-09-04，【Rust 中级教程】 03 trait (1)](https://mp.weixin.qq.com/s/f05ygOwUzBlj5gFblB0rgw)
    - [2022-09-10，【Rust 中级教程】 04 trait (2)](https://mp.weixin.qq.com/s/f05ygOwUzBlj5gFblB0rgw)
    - [2022-09-18，【Rust 中级教程】 04 trait (3)](https://mp.weixin.qq.com/s/ucRjbLb4wwe5S-ilyGbQeg)
    - [2022-09-24，【Rust 中级教程】 06 trait (4)](https://mp.weixin.qq.com/s/8HBKVwF2gkwYUndrBd49QA)
    - [2022-10-01，【Rust 中级教程】 07 内存](https://mp.weixin.qq.com/s/4su0oZGHPmjHJbsuT4iJYg)
    - [2022-10-16，【Rust 中级教程】 08 所有权（1）](https://mp.weixin.qq.com/s/RFIOCVDUBdmcBus3hktwqA)
    - [2022-10-22，【Rust 中级教程】 09 所有权（2）](https://mp.weixin.qq.com/s/KMjMlOJ4zTHA7LY-3FEV-Q)
    - [2022-10-29，【Rust 中级教程】 10 所有权（3）](https://mp.weixin.qq.com/s/h3oND4-ORGoYp_ipiw01Mg)
    - [2022-11-05，【Rust 中级教程】 11 所有权与trait（4）](https://mp.weixin.qq.com/s/dOKhrmO0a3R1-ZRIm9ocnw)
    - [2022-11-12，【Rust 中级教程】 12 共享所有权](https://mp.weixin.qq.com/s/ab6VJ9A6GKfTzueczLSpjw)
    - [2022-11-19，【Rust 中级教程】 13 引用与借用（1）](https://mp.weixin.qq.com/s/qsI9cMBWKQD8SKl28ZwteQ)
    - [2022-11-26，【Rust 中级教程】 14 引用与借用（2）](https://mp.weixin.qq.com/s/gbYnu1-_vgSluceI-6d50A)
    - [2022-12-17，【Rust 中级教程】 15 引用与借用（3）](https://mp.weixin.qq.com/s/KMf-lRojjdCwzG2WH_exfw)
    - [2022-12-24，Rust 中级教程 第16课——引用的 lifetime（1）](https://mp.weixin.qq.com/s/lWJzvHFbnxLfUoVEXV9new)
    - [2023-01-07，Rust 中级教程 第17课——引用的 lifetime（2）](https://mp.weixin.qq.com/s/jjy0oIHgAwd_tQbJdugjqQ)
    - [2023-01-14，Rust 中级教程 第18课——trait object （1）](https://mp.weixin.qq.com/s/gg4BgH09NcmB_Y46v4F5dA)
    - [2023-02-04，Rust 中级教程 第19课——trait object （2）](https://mp.weixin.qq.com/s/84n4UugKD8a-uPkonaevIQ)
    - [2023-02-18，Rust 中级教程 第20课——Box](https://mp.weixin.qq.com/s/-15jAC241ZaK85J-AOcJxw)
    - [2023-02-25，Rust 中级教程 第21课——Drop trait](https://mp.weixin.qq.com/s/hQFrfnbuQADS0nS0pA9p9A)
    - [2023-03-04，Rust 中级教程 第22课——内部可变性（1）](https://mp.weixin.qq.com/s/fDqac5K4UswoW3qe9r5Row)
    - [2023-03-11，Rust 中级教程 第23课——内部可变性（2）](https://mp.weixin.qq.com/s/K952XivQ0_-EJLrlBIqT1Q)
    - [2023-03-18，​Rust 中级教程 第24课——下划线（Underscore）](https://mp.weixin.qq.com/s/Iy_x_4j6oBeBUDEtx-XDwg)
    - [2023-04-01，【Rust 进阶教程】 01 闭包与所有权](https://mp.weixin.qq.com/s/KiOD7my7CpT-jEcB8LGcqA)
    - [2023-04-08，【Rust 进阶教程】 02 详解迭代器（1）](https://mp.weixin.qq.com/s/wQ0w_z1FpOujm9T7tLGfLQ)
    - [2023-04-15，【Rust 进阶教程】 03 详解迭代器（2）](https://mp.weixin.qq.com/s/ajP-Kamwdd7vUjKyaVT8Hw)
    - [2023-04-22，【Rust 进阶教程】 04 并发编程](https://mp.weixin.qq.com/s/7BMNmVmkhXkXKyii6wuoIQ)
    - [2023-05-06，【Rust 进阶教程】 05 通道](https://mp.weixin.qq.com/s/HovHf5a5bp2mzyG0yN5Eow)
    - [2023-05-13，Rust 进阶教程 第6课——线程安全](https://mp.weixin.qq.com/s/uLWFiUXjCY--SccpjD8KSg)
    - [2023-05-21，【Rust 实战】Rust 与 Python 交互](https://mp.weixin.qq.com/s/X6fZiCuxAGxV0TC4o75yDw)
    - [2023-06-04，【Rust 进阶教程】 07 Mutex](https://mp.weixin.qq.com/s/GGcx4BE-c2nn831mYwWZ8Q)
    - [2023-07-30，Rust 进阶教程 第8课——读写锁](https://mp.weixin.qq.com/s/5ic6XOEjNREJlPJDjAIW5g)
    - [2023-08-05，【Rust 进阶教程】 09 原子类型](https://mp.weixin.qq.com/s/6yEdjJHBISj1PxBJe7OAog)
    - [2023-08-12，【Rust 进阶教程】10 操作符重载](https://mp.weixin.qq.com/s/b0B4PpJ7G-Wy2QifJVdLDA)
    - [2023-08-19，【【Rust 进阶教程】 11 错误处理 - panic](https://mp.weixin.qq.com/s/v60Z_1MzvAGaKBOHySsFXA)
    - [2023-08-26，【【Rust 进阶教程】12 错误处理 - Result](https://mp.weixin.qq.com/s/5-3BUVLb7MGLmhtCS1PaDQ)
    - [2023-08-30，【Rust-SlintUI教程】01 Hello Slint UI](https://mp.weixin.qq.com/s/suz_zn3IL0f74DiTueQ2jA)
    - [2023-09-02，【Rust-SlintUI教程】02 初识 Slint UI](https://mp.weixin.qq.com/s/x91Zwx-Taue3xOZnDAjoyg)
    - [2023-09-06，【【Rust-SlintUI教程】03 元素与标识符](https://mp.weixin.qq.com/s/6QV6Fq9yMpiRHlV-GT6eLg)
  - 微信公众号「兔子写代码」
    - [2023-03-17，Rust 闲聊 | Rust 语言真的会是未来吗？](https://mp.weixin.qq.com/s/wYQYxpR2YA0Q9rI1WezJVw)
    - [2023-03-21，彻底搞懂 Rust 的宏（一）：简介](https://mp.weixin.qq.com/s/lEJaLsHgjdoF6IZmIspS-w)
    - [2023-03-22，彻底搞懂 Rust 的宏（二）：声明宏的组成](https://mp.weixin.qq.com/s/4IFrvmf8dTfRIGlqX4hM-A)
    - [2023-03-28，彻底搞懂 Rust 的宏（三）：声明宏语法全解析](https://mp.weixin.qq.com/s/uzVpdd85dZ8VbwnrpMBBEw)
    - [2023-04-19，彻底搞懂 Rust 的宏（四）：片段分类符](https://mp.weixin.qq.com/s/TR_cje5CorP_uPn3UI3Njw)
    - [2023-04-29，彻底搞懂 Rust 的宏（五）：宏展开](https://mp.weixin.qq.com/s/32Fw643uehtiSPcnUBC3sg)
    - [2023-05-06，彻底搞懂 Rust 的宏（六）：一个小例子及两个注意点](https://mp.weixin.qq.com/s/59iK79G7Njw-oZnKEND6yg)
    - [2023-05-16，彻底搞懂 Rust 的宏（七）：重复元变量](https://mp.weixin.qq.com/s/SHL5eeHwSqJsIjEhN2Gz7A)
    - [2023-05-23，彻底搞懂 Rust 的宏（八）：内建宏](https://mp.weixin.qq.com/s/ZFWiAJgQKHLUdvLQbp09HA)
    - [2023-06-28，Rust 笔记 | 迭代器(一)：Iterator 和 IntoIterator](https://mp.weixin.qq.com/s/y8riTvwAMFt4LmFIfTP0Aw)
    - [2023-07-06，Rust 笔记 | 迭代器(二)：创建迭代器](https://mp.weixin.qq.com/s/Rn_i7aFqV7NfG6xEHr-UPw)
    - [2023-08-03，Rust 笔记 | 迭代器的适配器：map 和 filter](https://mp.weixin.qq.com/s/Za5zWQkvO262bu0ckLvu4g)
    - [2023-08-08，Rust 笔记 | 迭代器的适配器：filter_map 和 flat_map](https://mp.weixin.qq.com/s/mj3ot6Q9QGZgExjPCC506w)
    - [2023-08-11，Rust 笔记 | 迭代器的适配器：flatten](https://mp.weixin.qq.com/s/bHRK87RIOntu7iUNu0q8IQ)
    - [2023-08-16，Rust 笔记 | 迭代器的适配器：take 和 take_while](https://mp.weixin.qq.com/s/sXGdXR-btTUxb5Wx8pMBfQ)
    - [2023-08-18，Rust 笔记 | 迭代器的适配器：skip 和 skip_while](https://mp.weixin.qq.com/s/2swrychEVzGTt6UqvrdBgA)
  - 微信公众号「706青年空间」
    - [2023-05-26，Rust 共学招募 | 跨越 Web2 与 Web3 深入底层重构世界](https://mp.weixin.qq.com/s/xVXDyYcfwH6UscoNt9uUPA)
    - [2023-07-27，Rust 共学第一期结束！七个项目参与最终 Demo Day 分享](https://mp.weixin.qq.com/s/hoJfHqWYod0uRJd9nkKmvA)
    - [2023-08-15，Solana 共学招募 | 聚集 Rust 开发者，一起组队黑客松](https://mp.weixin.qq.com/s/Zxf5UfLTvd7S6OFXcXjL_g)
  - 微信公众号「总有一点知识你需要」
    - [2023-04-09，[翻译] 在2023年，每个学习Rust的人都应该知道的资源](https://mp.weixin.qq.com/s/9lLKBkn2qEOieFGrysWs5A)
    - [2023-09-06，什么是Anchor](https://mp.weixin.qq.com/s/sQpoSi7saTs1uhr0Mbnw7w)
  - 微信公众号「CSDN」
    - [2021-03-24，底层I/O性能大PK：Python/Java被碾压，Rust有望取代C++](https://mp.weixin.qq.com/s/P3Wbw9diEg2xKryUG0KtTQ)
    - [2021-11-09，为什么 Rust 是编程的未来？](https://mp.weixin.qq.com/s/MVQkTjbAACYN6CjFKVjWPw)
    - [2022-06-24，Rust，程序员创业的最佳选择？](https://mp.weixin.qq.com/s/Ok9apMM514T7NORwQsP8zQ)
    - [2023-05-05，将代码从 C 迁移到 Rust，sudo、su 正在行动！](https://mp.weixin.qq.com/s/ZlcuW9EkgbECFHzT71KBQg)
    - [2023-05-15，Mozilla 发布 Rust | 历史上的今天](https://mp.weixin.qq.com/s/zsgFlQ8pG04_ApwMkl6rdQ)
    - [2023-05-16，Windows 11 初尝 Rust，36000 行内核代码已重写！](https://mp.weixin.qq.com/s/Pram-Xdldm3-oe2acm3JeQ)
    - [2023-05-16，可能取代Vulkan和OpenGL的WebGPU为何如此重要？](https://mp.weixin.qq.com/s/Gr3iecrdKtoBQPaPsGJdkw)
    - [2023-06-23，200 行 Rust 代码编写一个向量搜索库，代码已开源！](https://mp.weixin.qq.com/s/yiO3xgenApsdBjOPgMLiFQ)
  - 微信公众号「OSC开源社区」
    - [2019-07-23，微软解释为什么Rust是系统编程的最佳选择](https://mp.weixin.qq.com/s/mapX5iRbjbtBuYlc5_G-TQ)
    - [2023-04-05，Slint 1.0正式发布，Rust编写的原生GUI工具包](https://mp.weixin.qq.com/s/48vKNS0Y4tC7z8Qg2_2Vww)
    - [2023-05-06，Rust重写万物？](https://mp.weixin.qq.com/s/uLJvTh-N19AG0iMMYvJ1qA)
  - 微信公众号「InfoQ」
    - [2023-02-04，雄心勃勃的计划：沃尔沃正在将 Rust 用于其车载软件](https://mp.weixin.qq.com/s/5e34vBklt268asUu54LQQg)
    - [2023-04-28，30年老代码被干掉！微软用18万行 Rust 改写 Windows 系统内核](https://mp.weixin.qq.com/s/7l4Lq4_7m27-UhF7yKQQtg)
  - 微信公众号「码小菜」
    - [2023-05-13，我什么放弃了C/C++，而选择了Rust](https://mp.weixin.qq.com/s/r7v_lYjBmfixENGpFTE-Vg)
    - [2023-05-13，Qdrant不只是高性能向量数据库](https://mp.weixin.qq.com/s/9idV_Q97C852ViusvrW7CQ)
  - 微信公众号「腾讯技术工程」
    - [2022-12-29，大牛书单 | Rust 好书推荐](https://mp.weixin.qq.com/s/q1IsG4VKrhIFLRFleyJA6g)
  - 微信公众号「Parity Tech」
    - [2023-05-23，Substrate 账户、地址和密钥](https://mp.weixin.qq.com/s/GK9XhdVUV__5cSddhKatVQ)
  - 微信公众号「分布式实验室」
    - [2023-02-16，我们选择了Rust，因为它太快了](https://mp.weixin.qq.com/s/YdxNbueReCMAAnEdj-LKUQ)
    - [2023-02-27，跟着Rust语言中文社区联合创始人学Rust](https://mp.weixin.qq.com/s/xJHhHs7-D6iduq7c1xMRFg)
  - 微信公众号「Rust编程指北」
    - [2022-01-31，Rust 到底值不值得学：万字长文对比、特色和理念](https://mp.weixin.qq.com/s/UhNQk2i3xjLbPNOXkssHbA)
  - 微信公众号「51CTO技术栈」
    - [2023-03-28，后端队友选择Rust，爽到了！](https://mp.weixin.qq.com/s/zBCoYTzFYvAU7OEdqYdxpg)
  - 微信公众号「量子位」
    - [2023-05-29，取代C++！3.6万行Rust代码改写Windows内核，这门语言最早竟用来修电梯](https://mp.weixin.qq.com/s/NZm97ZKBl6WF6oALdXkQMQ)
  - 微信公众号「AI前线」
    - [2023-08-11，Python 失宠！Hugging Face 用 Rust 新写了一个 ML框架，现已低调开源](https://mp.weixin.qq.com/s/YMmYnODJObYplDolnhtJZw)
  - 微信公众号「AI工程化」
    - [2023-08-11，Hugging Face偷偷放大招了，Rust版本的ML框架Candle曝光](https://mp.weixin.qq.com/s/iwrV35oq_j8-SqUIMk-m0A)
  - 「[MIT Technology Review](https://www.technologyreview.com/)」
    - [2023-02-14，How Rust went from a side project to the world’s most-loved programming language](https://www.technologyreview.com/2023/02/14/1067869/rust-worlds-fastest-growing-programming-language)
  - 「[Piotr Kołaczkowski](https://pkolaczk.github.io/)」
    - [2023-05-21，How Much Memory Do You Need to Run 1 Million Concurrent Tasks?](https://pkolaczk.github.io/memory-consumption-of-async/)
  - 「[tweede golf](https://tweedegolf.nl/en)」
    - [2023-07-12，Why Rust is a great fit for embedded software - 2023 update](https://tweedegolf.nl/en/blog/96/why-rust-is-a-great-fit-for-embedded-software-2023-update)




