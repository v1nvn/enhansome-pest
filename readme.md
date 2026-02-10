# Awesome Pest. The Elegant Parser [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

[<img src="https://avatars.githubusercontent.com/u/26044607" align="right" width="100">](https://github.com/pest-parser/pest/) ⭐ 5,277 | 🐛 68 | 🌐 Rust | 📅 2026-02-05

> A curated list of resources, projects, and tools using or for the pest parser generator in Rust

pest is a general purpose parser written in Rust with a focus on accessibility, correctness, and performance. It uses parsing expression grammars (or [PEG](https://en.wikipedia.org/wiki/Parsing_expression_grammar)) as input, which are similar in spirit to regular expressions, but which offer the enhanced expressivity needed to parse complex languages.

Contributions welcome! Read the [contribution guidelines](origin/contributing.md) first.

## Contents

* [Resources](#resources)
* [Projects](#projects)
* [Tooling](#tooling)

## Resources

* [Book](https://pest.rs/book) - The recommended way to start parsing with pest is to read this official book.
* [API reference on docs.rs](https://docs.rs/pest)
* [fiddle editor on pest.rs](https://pest.rs/#editor) - Play with grammars and share them on the official website (and format them!).
* [Gitter](https://gitter.im/pest-parser/pest)
* [Discord](https://discord.gg/XEGACtWpT2)
* [GitHub Discussions](https://github.com/pest-parser/pest/discussions) ⭐ 5,277 | 🐛 68 | 🌐 Rust | 📅 2026-02-05

## Projects

Here are some example projects using pest:

* [Vector](https://github.com/timberio/vector) ⭐ 21,299 | 🐛 2,258 | 🌐 Rust | 📅 2026-02-10 - A high-performance observability data pipeline.
* [pest\_meta](https://github.com/pest-parser/pest/blob/master/meta/src/grammar.pest) ⭐ 5,277 | 🐛 68 | 🌐 Rust | 📅 2026-02-05 - The pest itself is bootstrapped using pest.
* [Melody](https://github.com/yoav-lavi/melody) ⭐ 4,744 | 🐛 8 | 🌐 Rust | 📅 2024-11-24 - Melody is a language that compiles to regular expressions and aims to be more easily readable and maintainable.
* [tera](https://github.com/Keats/tera) ⭐ 4,116 | 🐛 192 | 🌐 Rust | 📅 2025-12-11 - A template engine for Rust based on Jinja2/Django.
* [insta](https://github.com/mitsuhiko/insta) ⭐ 2,743 | 🐛 71 | 🌐 Rust | 📅 2026-02-05 - A snapshot testing library for rust.
* [ZoKrates](https://github.com/ZoKrates/ZoKrates) ⭐ 1,881 | 🐛 109 | 🌐 Rust | 📅 2024-08-01 - A toolbox for zkSNARKs on Ethereum.
* [jql](https://github.com/yamafaktory/jql) ⭐ 1,652 | 🐛 3 | 🌐 Rust | 📅 2026-02-03 - A JSON Query Language CLI tool.
* [AutoCorrect](https://github.com/huacnlee/autocorrect) ⭐ 1,542 | 🐛 6 | 🌐 Rust | 📅 2026-02-05 - A linter and formatter to help you to improve copywriting, correct spaces, words, and punctuations between CJK (Chinese, Japanese, Korean).
* [handlebars-rust](https://github.com/sunng87/handlebars-rust) ⭐ 1,451 | 🐛 41 | 🌐 Rust | 📅 2026-02-06 - Rust templating with Handlebars.
* [cicada](https://github.com/mitnk/cicada) ⭐ 1,002 | 🐛 1 | 🌐 Rust | 📅 2026-02-05 - An old-school bash-like Unix shell written in Rust.
* [rs\_pbrt](https://github.com/wahn/rs_pbrt) ⭐ 833 | 🐛 3 | 🌐 Rust | 📅 2024-01-29 - Rust crate to implement a counterpart to the PBRT book's (3rd edition) C++ code.
* [TypeQL Rust](https://github.com/typedb/typeql/tree/master/rust) ⭐ 242 | 🐛 43 | 🌐 Rust | 📅 2026-02-09 - TypeDB's query language, written in Pest
* [json5-rs](https://github.com/callum-oakley/json5-rs) ⭐ 223 | 🐛 4 | 🌐 Rust | 📅 2026-02-07 - A Rust JSON5 serializer and deserializer which speaks Serde.
* [Keadex Mina](https://github.com/keadex/keadex) ⭐ 194 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-08 - Open Source, serverless IDE to code with C4-PlantUML and organize at a scale C4 model diagrams.
* [qubit](https://github.com/abhimanyu003/qubit) ⭐ 95 | 🐛 1 | 🌐 Rust | 📅 2022-01-17 - A handy calculator, based on Rust and WebAssembly.
* [elastic-rs](https://github.com/cch123/elastic-rs) ⭐ 52 | 🐛 1 | 🌐 Rust | 📅 2023-07-21 - Convert bool expressions to Elasticsearch DSL in Rust.
* [hexdino](https://github.com/Luz/hexdino) ⭐ 34 | 🐛 1 | 🌐 Rust | 📅 2025-12-21 - A hex editor with vim like keybindings written in Rust.
* [mt940](https://github.com/svenstaro/mt940-rs) ⭐ 26 | 🐛 1 | 🌐 Rust | 📅 2026-01-21 - A MT940 parser in Rust.
* [caith](https://github.com/Geobert/caith) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2025-03-10 - A dice roller crate.
* [stache](https://github.com/dgraham/stache) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2020-08-31 - A Mustache template compiler.
* [py\_literal](https://github.com/jturner314/py_literal) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2021-04-07 - Rust crate for parsing/formatting Python literals.
* [rouler](https://github.com/jarcane/rouler) ⭐ 18 | 🐛 5 | 🌐 Rust | 📅 2022-01-27 - An easy to use dice rolling library for Rust.
* [AshPaper](https://github.com/shnewto/ashpaper) ⭐ 15 | 🐛 11 | 🌐 Rust | 📅 2023-03-20 - Rust Inpterpreter for Esopo language AshPaper conceived by William Hicks.
* [yaml-peg](https://github.com/aofdev/yaml-peg) ⭐ 10 | 🐛 1 | 🌐 Rust | 📅 2021-08-30 - PEG parser for YAML written in Rust.
* [PTA-Parser](https://github.com/AltaModaTech/pta-parser/) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2024-06-10 - A Plain Text Accounting parser built in Rust for [Beancount](https://github.com/beancount/beancount) ⭐ 5,255 | 🐛 226 | 🌐 Python | 📅 2026-01-30, [Ledger](https://github.com/ledger/ledger) ⭐ 5,833 | 🐛 732 | 🌐 C++ | 📅 2026-02-09, and other PTA formats.
* [Liquid Grammar](https://github.com/rust-utilities/liquid-grammar-pest/) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2024-06-24 - Generate `Pairs` and/or `Rules` for [Shopify](https://shopify.github.io/liquid/) Liquid (hash-tags *not-sponsored* or *affiliated*) for use in consuming crates
* [RuSh](https://github.com/lwandrebeck/RuSh) - RuSh aims to be a bash compatible shell with candies, written in Rust.
* [ws2markdown](https://code.rosaelefanten.org/ws2markdown) - Converts WordStar documents into Markdown files.

## Tooling

### IDE Support

* [pest IDE tools](https://github.com/pest-parser/pest-ide-tools) ⭐ 64 | 🐛 20 | 🌐 Rust | 📅 2026-02-09 - A main repository with LSP server and VSCode extension.
* [pest.vim](https://github.com/pest-parser/pest.vim) ⭐ 39 | 🐛 3 | 🌐 Vim Script | 📅 2024-04-25
* [pest-fmt](https://github.com/pest-parser/pest-fmt) ⭐ 27 | 🐛 4 | 🌐 Rust | 📅 2024-04-08 - It can help to format
  pest grammars.
* [pest web debugger](https://github.com/tomtau/pest-web-debug) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2023-06-23 - Try it [online](https://tomtau.github.io/pest-web-debug/).
* [VSCode Extension](https://marketplace.visualstudio.com/items?itemName=pest.pest-ide-tools)
* [IntelliJ IDEA Plugin](https://plugins.jetbrains.com/plugin/12046-pest)

### Boilerplate reduction and testing

* [pest-ast](https://github.com/pest-parser/ast) ⭐ 90 | 🐛 20 | 🌐 Rust | 📅 2025-12-26 - It can help to reduce boilerplate when converting pest parse trees to abstract syntax trees.
* [pest\_consume](https://crates.io/crates/pest_consume) - This crate can help with the parse tree traversing boilerplate.
* [pest-test](https://crates.io/crates/pest-test) - It is a testing framework for pest grammars.
* [pest\_ascii\_tree](https://crates.io/crates/pest_ascii_tree) - Output `Pairs` in a tree on the console

### CLI Debugger

* [pest\_debugger](https://docs.rs/pest_debugger/latest/pest_debugger/) - It is a crate for debugging pest grammars. It can be used as a CLI tool or as a library. [See instructions for using the CLI debugger](origin/debugger.md).
