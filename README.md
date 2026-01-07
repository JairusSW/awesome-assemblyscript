# Awesome AssemblyScript 😎

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome AssemblyScript packages, projects, tools, and resources.

AssemblyScript brings TypeScript-like syntax to WebAssembly with a focus on performance and low-level control. This list collects high-quality libraries, real-world projects, and learning resources from the ecosystem.

Inspired by https://github.com/sindresorhus/awesome

---

## Contents

- [Packages](#packages)
  - [Utility](#utility)
  - [Security](#security)
  - [Blockchain](#blockchain)
  - [Web](#web)
  - [Backend](#backend)
  - [Serialization](#serialization)
  - [Game Development](#game-development)
  - [Testing](#testing)
  - [Math & Numbers](#math--numbers)
  - [AST & Transforms](#ast--transforms)
  - [Build Tools](#build-tools)
  - [I/O](#io)
  - [Memory](#memory)
  - [Compression](#compression)
  - [WASI](#wasi)
  - [Lunatic VM](#lunatic-vm)
- [Projects](#projects)
  - [Games](#games)
- [Resources](#resources)


---

## Packages

### Utility

- [as-container](https://github.com/yjhmelody/as-container) - Rust-like Result and Option types.
- [as-variant](https://github.com/MaxGraey/as-variant) - Variant type providing dynamic values.
- [as-string-sink](https://github.com/MaxGraey/as-string-sink) - Efficient string builder.
- [as-random](https://github.com/MaxGraey/as-random) - Random number generators.

### Security

- [wasm-crypto](https://github.com/jedisct1/wasm-crypto) - Collection of hashing algorithms. (Unmaintained)
- [superfasthash](https://github.com/mjethani/superfasthash) - SuperFastHash implementation. (Unmaintained)
- [xoroshiro128starstar](https://github.com/krisselden/xoroshiro128starstar) - Port of xoroshiro128**.
- [rabin-wasm](https://github.com/hugomrdias/rabin-wasm) - Rabin fingerprinting.

### Blockchain

- [subscript](https://github.com/ascontract/subscript) - Subscript blockchain SDK.
- [biturbo](https://github.com/ewasm/biturbo) - Ethereum 1 EE using Turboproofs.

### Web

- [asdom](https://github.com/lume/asdom) - DOM bindings (WIP).
- [ecmassembly](https://github.com/aspkg/ecmassembly) - JavaScript APIs ported to AssemblyScript.

### Backend

- [as-lunatic](https://github.com/lunatic-solutions/as-lunatic) - High-level AssemblyScript bindings for Lunatic.

### Serialization

- [rlp](https://github.com/SteerProtocol/rlp) - RLP implementation.
- [as-json](https://github.com/JairusSW/as-json) - JSON implementation.
- [karmem](https://github.com/inkeliz/karmem) - Fast binary serialization format.
- [fass](https://github.com/JairusSW/fass) - Extremely fast schema-driven serializer.
- [as-proto](https://github.com/piotr-oles/as-proto) - Protobuf implementation.
- [as-msgpack](https://github.com/wapc/as-msgpack) - MessagePack implementation.
- [serial-as-borsh](https://github.com/gagdiez/serial-as/tree/main/borsh) - Borsh implementation.
- [serial-as-json](https://github.com/gagdiez/serial-as/tree/main/json) - JSON implementation. (Unmaintained)
- [assemblyscript-bson](https://github.com/nearprotocol/assemblyscript-bson) - BSON implementation. (Unmaintained)
- [assemblyscript-json](https://github.com/near/assemblyscript-json) - JSON implementation. (Unmaintained)

### Game Development

- [VectorEngine](https://github.com/battlelinegames/VectorEngine) - Vector rendering engine.
- [ASWebGLue](https://github.com/battlelinegames/ASWebGLue) - WebGL bindings.
- [koora](https://github.com/mrchantey/koora) - 3D game framework.

### Testing

- [as-pect](https://github.com/jtenner/as-pect) - Jest-like testing framework. (Unmaintained)
- [as-test](https://github.com/JairusSW/as-test) - WIP testing framework.

### Math & Numbers

- [as-bignum](https://github.com/MaxGraey/as-bignum) - Fixed-size big numbers.
- [as-big](https://github.com/ttulka/as-big) - Arbitrary-precision integers.
- [as-bigint](https://github.com/polywrap/as-bigint) - Big integer math.
- [as-bignumber](https://github.com/polywrap/as-bignumber) - Arbitrary precision integers and decimals.
- [as-mpz](https://github.com/Hypercubed/as-mpz) - Arbitrary-precision integer library.

### AST & Transforms

- [visitor-as](https://github.com/as-pect/visitor-as) - Toolkit for building AssemblyScript transforms.

### Build Tools

- (No entries yet)

### I/O

- (No entries yet)

### Memory

- [as-malloc](https://github.com/fabriciopashaj/as-malloc) - Lightweight malloc, realloc, and free.

### Compression

- [AS-LZMA](https://github.com/01alchemist/AS-LZMA) - LZMA implementation. (Unmaintained)

### WASI

- [wasi-shim](https://github.com/AssemblyScript/wasi-shim) - WASI shim for AssemblyScript.
- [as-wasi](https://github.com/jedisct1/as-wasi) - WASI API layer.

### Lunatic VM

- [as-lunatic](https://github.com/lunatic-solutions/as-lunatic) - WASI-like runtime with processes, IPC, networking, and distribution.

---

## Projects

- [Hoofdkantoor Demoscene](https://wasm-demo.codument.com/demo.html) - 90s demoscene in AssemblyScript.

### Games

- [Project-H](https://github.com/Tugcga/Project-H) - Pathfinding experiments and game.
- [wasmBoy](https://github.com/torch2424/wasmBoy) - Game Boy emulator.
- [atari2600-wasm](https://github.com/ColinEberhardt/atari2600-wasm) - Atari 2600 emulator.
- [wa-spectrum-engine](https://github.com/Dotneteer/wa-spectrum-engine) - ZX Spectrum emulator.
- [chess](https://github.com/mhonert/chess) - Chess engine.
- [gomoku-wasm](https://github.com/jolestar/gomoku-wasm) - Gomoku engine.
- [2d-videogame-in-assemblyscript](https://github.com/ttulka/2d-videogame-in-assemblyscript) - 2D platformer.

