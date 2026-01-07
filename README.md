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

- https://github.com/JairusSW/assemble-the-awesome — Rust-like Result and Option types.
- https://github.com/MaxGraey/as-variant — Variant type providing dynamic values.
- https://github.com/MaxGraey/as-string-sink — Efficient string builder.
- https://github.com/MaxGraey/as-random — Random number generators.

### Security

- https://github.com/jedisct1/wasm-crypto — Collection of hashing algorithms. (Unmaintained)
- https://github.com/mjethani/superfasthash — SuperFastHash implementation. (Unmaintained)
- https://github.com/krisselden/xoroshiro128starstar — Port of xoroshiro128**.
- https://github.com/hugomrdias/rabin-wasm — Rabin fingerprinting.

### Blockchain

- https://github.com/ascontract/subscript — Subscript blockchain SDK.
- https://github.com/ewasm/biturbo — Ethereum 1 EE using Turboproofs.

### Web

- https://github.com/lume/asdom — DOM bindings (WIP).
- https://github.com/aspkg/ecmassembly — JavaScript APIs ported to AssemblyScript.

### Backend

- https://github.com/lunatic-solutions/as-lunatic — High-level AssemblyScript bindings for Lunatic.

### Serialization

- https://github.com/SteerProtocol/rlp — RLP implementation.
- https://github.com/JairusSW/as-json — JSON implementation.
- https://github.com/inkeliz/karmem — Fast binary serialization format.
- https://github.com/JairusSW/fass — Extremely fast schema-driven serializer.
- https://github.com/piotr-oles/as-proto — Protobuf implementation.
- https://github.com/wapc/as-msgpack — MessagePack implementation.
- https://github.com/gagdiez/serial-as/tree/main/borsh — Borsh implementation.
- https://github.com/gagdiez/serial-as/tree/main/json — JSON implementation. (Unmaintained)
- https://github.com/nearprotocol/assemblyscript-bson — BSON implementation. (Unmaintained)
- https://github.com/near/assemblyscript-json — JSON implementation. (Unmaintained)

### Game Development

- https://github.com/battlelinegames/VectorEngine — Vector rendering engine.
- https://github.com/battlelinegames/ASWebGLue — WebGL bindings.
- https://github.com/mrchantey/koora — 3D game framework.

### Testing

- https://github.com/jtenner/as-pect — Jest-like testing framework. (Unmaintained)
- https://github.com/JairusSW/as-test — WIP testing framework.

### Math & Numbers

- https://github.com/MaxGraey/as-bignum — Fixed-size big numbers.
- https://github.com/ttulka/as-big — Arbitrary-precision integers.
- https://github.com/polywrap/as-bigint — Big integer math.
- https://github.com/polywrap/as-bignumber — Arbitrary precision integers and decimals.
- https://github.com/Hypercubed/as-mpz — Arbitrary-precision integer library.

### AST & Transforms

- https://github.com/as-pect/visitor-as — Toolkit for building AssemblyScript transforms.

### Build Tools

- (No entries yet)

### I/O

- (No entries yet)

### Memory

- https://github.com/fabriciopashaj/as-malloc — Lightweight malloc, realloc, and free.

### Compression

- https://github.com/01alchemist/AS-LZMA — LZMA implementation. (Unmaintained)

### WASI

- https://github.com/AssemblyScript/wasi-shim — WASI shim for AssemblyScript.
- https://github.com/jedisct1/as-wasi — WASI API layer.

### Lunatic VM

- https://github.com/lunatic-solutions/as-lunatic — WASI-like runtime with processes, IPC, networking, and distribution.

---

## Projects

- https://wasm-demo.codument.com/demo.html — 90s demoscene in AssemblyScript.

### Games

- https://github.com/Tugcga/Project-H — Pathfinding experiments and game.
- https://github.com/torch2424/wasmBoy — Game Boy emulator.
- https://github.com/ColinEberhardt/atari2600-wasm — Atari 2600 emulator.
- https://github.com/Dotneteer/wa-spectrum-engine — ZX Spectrum emulator.
- https://github.com/mhonert/chess — Chess engine.
- https://github.com/jolestar/gomoku-wasm — Gomoku engine.
- https://github.com/ttulka/2d-videogame-in-assemblyscript — 2D platformer.
